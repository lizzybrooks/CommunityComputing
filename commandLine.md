# Get Closer to your Computer with the Command Line

Why the command line? 

#### Anatomy of a command line statement:
![command line diagram from learn enough command line to be dangerous](https://github.com/lizzybrooks/CommunityComputing/blob/master/images/anatomy.png "command line diagram from learn enough command line to be dangerous")


#### Try typing some basic commands
###### This section is forked from [antiboredom/automating-video-itp](https://github.com/antiboredom/automating-video-itp)

----

Make the computer say hi to you. Make the computer say something besides "hi". 

```
echo hi
```

Navigate to a directory (aka folder) on your computer. You may have done this before. (cd stands for change directory). 

```
cd [drag and drop your folder here or type the path] 
```

List contents of current directory 

```
ls 
```

Show name of current directory and full path. 
###### Path means the route that your computer will take to reach a particular file. To the computer, this is a "string" of text that it will follow to find your file. 
###### Fun fact: pwd stands for print working directory. 

```
pwd
```

Go up one

```
cd ..
```

Go to your home directory. (As in, get out of any folder that you're in). 

```
cd
```

Make a new directory. (In this context, directory = folder). 

```
mkdir DIRECTORYNAME
```

Open a file using the default application (mac only)

```
open FILENAME
```

Open the current directory in the Finder (mac only)
(the ```.``` means "here")

```
open .
```

Print the contents of a file to the screen

```
cat FILENAME
```

Print the contents of a file to the screen, with pagination

```
more FILENAME
```

Search for a something in a text file

```
grep "search term" FILENAME
```

