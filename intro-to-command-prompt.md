# Introduction to the Windows Command Prompt

This is a very basic introduction to the Windows Command Prompt. The Terminal on a Mac or Unix system works in a similar way.

## To open the Node.js Command Prompt (at the University)
```
Click Start-> type node, and select the Node.js Command Prompt (not Node.js)
```
The command prompt shows the drive and the path to the current directory e.g.
```
F:\web>
```
In this case I'm working on the in the web directory on the F: drive.

To view the contents of a directory (folder)

type *dir*:
```
F:\web>dir
 Volume in drive F has no label.
 Volume Serial Number is 9061-CF9F

 Directory of F:\web

13/07/2021  16:04    <DIR>          .
13/07/2021  16:04    <DIR>          ..
13/07/2021  17:06             408 index.html
30/08/2021  10:16    <DIR>          blog
               1 File(s)          3,370 bytes
               3 Dir(s)   4,358,488,064 bytes free
```

## To change directory
Type *cd* followed by the directory name e.g.

```
F:\web>cd blog
F:\web\blog
```

Directories are specified relative to the current directory. For example …/ will move up one directory level.
```
F:\web>cd ../
F:\>
 ```

You can also change directory by typing *cd* and then dragging the folder from windows explorer onto the Command Prompt

## To change drive
Type in the drive letter followed by a colon ':'' e.g.

```
F:\web> D:
D:\>
```
## Making a new directory
Type *mkdir* followed by the name for the new directory e.g.

```
D:\> mkdir project
D:\> cd project
D:\project>
```

## Going back to previous command
Instead of re-typing a previous command, you can use the up and down arrow keys to cycle through previous commands.

## Cancelling
Sometimes you will need to stop the execution of the currently running task to do this enter *ctrl+c*.

## Cutting, Copying, Pasting etc.
You can't use the mouse directly to select text in the Command Prompt.

* To select text, right click and choose mark, you will then be able to use the mouse to select text.
* To copy this text right click on the title bar (the top of the window) and select edit>copy.
* You can paste commands into the Command Prompt by right clicking and selecting paste.
Alternatives
* The basic Windows Command Prompt is fairly tedious to use. There are alternatives e.g. powershell, cmder if you are looking for something to install on your own machine.
