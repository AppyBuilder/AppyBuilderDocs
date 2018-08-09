# Source File Structure

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-L93-jOwVwLojc0B0kcn%2F-LGbYfUMBfZRIMPxNJWg%2F-LGb_9Wd1j8CzHLAYgJL%2Fimage.png?alt=media&token=dde86799-0c64-4048-8119-605ec2bcf859)

Article written by [Peter Mathijssen](http://community.appybuilder.com/u/peter_mathijssen/summary), shows you structure of AppyBuilder .aia and .scr files

Note: _Some text used and adapted from_  
“ENCOURAGING COLLABORATION THROUGH APP INVENTOR” By Katherine Kyle Feeney

AppyBuilder allows users to download the project files \(or source file\) for their projects, which can then be reloaded. The structure will look something like this:

![](../.gitbook/assets/image%20%2849%29.png)

The assets folders hold all files that have been uploaded to the project as an asset. If no assets are associated with a project then there will be no assets folder.  
If you import an extension a folder named external\_comps will be created inside the assets folder. The extension will be uploaded to the external\_comps folder. There will be a folder created inside the external\_comps folder for every extension.

The src/com/appybuilder/\[username\]/\[example\] folder holds a .blk file and a .scm file for every screen in the project. For example every project will have a Screen1.blk file and a Screen1.scm file. The Screen1.blk file holds all information about the blocks associated with Screen1 and the Screen1.scm file holds information about the layout of Screen1.

The youngandroidproject folder holds only one file, the project.properties file. This file holds basic information about the project, such as name, main screen and file structure

![](../.gitbook/assets/image%20%2815%29.png)

The new option of importing and exporting screens gives another fileformat. It’s extension is SCR and you can see the filestructure above. You can see that extensions and assets are not exported with the file.

Instead there is a file with an extension called YAIL added. The following is an explanation from Franklyn Turbak i found on the App Inventor Google Group:

> When your blocks program is executed on your phone, it is _not_ translated to a traditional language like Java/C/JavaScript etc. It is translated to Scheme-like YAIL code and executed in an interpreter on the phone. Ultimately all Android apps are running a version of Java, but App Inventor code is never converted to Java in live development mode. Rather, it’s YAIL code that runs in an interpreter implemented on top of Java. So there’s no way to “see” the Java code associated with your app.

