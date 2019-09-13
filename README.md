# open-jamf-pro-server-tools
A simple Automator applet to open the new Jamf Pro Server Tools

[Download here](https://github.com/PaperFixie/open-jamf-pro-server-tools/raw/master/Jamf%20Pro%20Server%20Tools%20Launcher.dmg)

This applet executes a simple shell script to open the new Jamf Pro Server Tools with a single click.

Currently the workaround as stated on [Jamfnation](https://www.jamf.com/jamf-nation/articles/578/jamf-pro-server-tools-overview):

> ## Open the Jamf Pro Server Tools GUI by performing the following steps:
>
> 1. Open a command terminal and enter the following: `java -jar`
> 2. Drag the Jamf Pro Server Tools .jar file into the window to add the path to the .jar file to the java -jar command.
> 3. Press Enter.

To make things easier this applet runs:

```
#!/bin/zsh

java -jar /Library/JSS/bin/server-tools-gui.jar
```

I threw a nice icon on the file and that's it.

Free to use, this'll be fixed by Jamf soon, probably.
