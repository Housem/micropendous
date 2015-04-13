**PATH** is a list of directories Windows searches in for programs when you attempt to run a program in a _Command Prompt_.  Each directory is separated with a semicolon `;`.

You may need to be logged in as Administrator to perform the following.

  1. Get to _System Properties_.  You can either right-click on _My Computer_ and click _Properties_, or you can go to _Start_, then _Control Panel_, then _System_.
  1. Select the _Advanced_ tab and click _Environment Variables_.
  1. Double-click **PATH** under _System Variables_
  1. Add `;C:\Program Files\WinAVR\bin` and `;C:\Program Files\WinAVR\utils\bin` to the end of the list in _Variable Value_.  This value will be different if you installed WinAVR somewhere else.

Here is an over-lapped picture of the above:

![http://micropendous.googlecode.com/svn/trunk/Pictures/Windows_SetPATH_WinAVR.jpg](http://micropendous.googlecode.com/svn/trunk/Pictures/Windows_SetPATH_WinAVR.jpg)