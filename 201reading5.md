### Brandons Ops Reading Notes
## Ops201 Readings
# Reading #5

1. How can you list the files in the current directory using the command prompt?

	Use the dir function

2. How might the “sfc” command and the “gpupdate” command help in troubleshooting on Windows?

	SFC AKA System File Checker scans the system files of Windows to see if the core OS files are corrupted which maybe causing the problem. You can use scannow to attempt to fix the corrupted files. 

	gpupdate allows you to update the group policy of a user. A user may not have the access they need to perform the function they are looking to do and authorized to do so. You can use gpupdate to force a group policy change that allows the user to then perform the action they are atttempting to perform.

3. What advantages does the “robocopy” command offer over the “xcopy” command, and why is it useful for file transfers in certain situations?

	XCOPY allows you to copy multiple files and directories through a simple command line. Robocopy is an advanced version of Xcopy that allows additional functions. If you're on a network with unreliable connectivity then xcopy allows you to resume transfer incase of connectivity loss.

4. Think about any real-life scenarios from your cultural context where the use of command line tools could be beneficial. Describe one such scenario and explain how a specific command line tool would help address the situation.

	Sometimes windows cannot boot up properly. In the case, you would boot up in command line safe mode where you would just get the command line terminal and not the windows GUI that most are used to. Knowing how to use the command line tool inside the terminal can help you troubleshoot issues that is preventing Windows from fully loading. It maybe that there is a corrupted system file that you can use the command line to fix through sfc and boot back up into windows properly. 


## Things I want to know more about
