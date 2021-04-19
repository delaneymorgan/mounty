# mounty
An AppleScript for re-mounting servers under MacOS.

Mounty checks for a specified server to come on-line and remounts it when it appears.  By default it checks every 60 seconds via the AppleScript idle event.

You will need to modify the script to specify the server, the target volume, and also the user/password combination.

Use File->Export... to save the modified script as an application.  Check "Stay open after run handler".

In the Finder, Cmd-I the application to modify its icon (optional).

Double-click to start, or make the application a login item so it automatically starts when you log in.

If you notice the occasional double mounting of volumes, tune idlePeriod to prevent overlapping idle events.  The default is 60 seconds which should be long enough for mounting most SMB volumes.

You can quit the script any time with Cmd-Q.