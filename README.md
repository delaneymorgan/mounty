# mounty
An AppleScript for re-mounting servers under MacOS.

Mounty checks for a specified server to come on-line and remounts it when it appears.  It checks every 30 seconds via the AppleScript idle event.

You will need to modify the script to specify the server, the target volume, and also the user/password combination.

Use File->Export... to save the modified script as an application.  Check "Run Only".

In the Finder, Cmd-I the application to modify its icon.

Double-click to start, or make the application a login item so it automatically starts when you log in.

You can quit the script any time with Cmd-Q.