Using a Shell and commands

pwd - print working directorty: It tells you what your current or present working directory is.
ls - list: Tells us whats in our current location
cd - change directory: without any arguments will take you back to the home directory.
A -l after the ls command tells us that we going to do a long list. A long listing has the following.
1. First character indicates whether it is a normal file ( - ) or directory ( d )
2. Next 9 characters are permissions for the file or directory (we'll learn more about them in section 6).
3. The next field is the number of blocks (don't worry too much about this).
4. The next field is the owner of the file or directory (ryan in this case).
5. The next field is the group the file or directory belongs to (users in this case).
6. Following this is the file size.
7. Next up is the file modification time.
8. Finally we have the actual name of the file or directory.
/etc - tells the ls not to list our current directory but instead to list that directories contents.

A path is a means to get to a particular file or directory on the system. There are two types of paths, absolute and relative.
Absolute paths always begin with a foward slash ( / ).
~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
. (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
.. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

file
obtain information about what type of file a file or directory is.
ls -a
List the contents of a directory, including hidden files

Everything is a file under Linux
Even directories.
Linux is an extensionless system
Files can have any extension they like or none at all.
Linux is case sensitive
Beware of silly typos
