# AddCustomMusic
**Quick tutorial on how to add custom music to Anno 1800**
You can find all the triggers and scripts used in the Return to the Orient Mod here,
but the key takeaway is this:

- Have a Wwise Soundbank with Start and Stop Events for a Random Container (have a look [here](https://www.youtube.com/watch?v=jIPWDSSsG2I) for a Wwise Tutorial)
- Trigger a script everytime you enter *any* session, which checks if it's the correct session
- If so, trigger the Start Event
- When leaving any session, fire the Stop Event
- A lua script running in the background stops the music when exiting to the Main Menu
