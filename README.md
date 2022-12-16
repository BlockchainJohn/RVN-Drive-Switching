# RVN-Drive-Switching
How to Switch your Ravencoin Drive from C: to D:


To move a Ravencoin node from the C drive to the D drive, you can follow these steps:

Stop the Ravencoin daemon by running the raven-cli stop command.

Locate the Ravencoin data directory on the C drive. This is typically located at 
C:\Users\<username>\AppData\Roaming\Raven.

Copy the entire Ravencoin data directory to the desired location on the D drive. 
You can use a tool like Windows Explorer or the xcopy command to do this.

Create a new text file in the Ravencoin data directory on the D drive and name it raven.conf.

Open raven.conf in a text editor and add the following line to specify the location 
of the data directory: datadir=D:\Ravencoin\Data

Save and close the raven.conf file.

Start the Ravencoin daemon by running the ravend command or manually by starting the program.

Your Ravencoin node should now be running from the D drive. Note that you may need to 
update any shortcuts or scripts that you use to start the node to reflect the new location 
of the data directory.
