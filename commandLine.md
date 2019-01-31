# Get To Know Your Computer Better with the Command Line

Why the command line? 
###### The command-line interface, sometimes referred to as the CLI, is a tool into which you can type text commands to perform specific tasks—in contrast to the mouse’s pointing and clicking on menus and buttons. Since you can directly control the computer by typing, many tasks can be performed more quickly, and some tasks can be automated with special commands that loop through and perform the same action on many files—saving you, potentially, loads of time in the process. (This explanation is from [Lee Tusman's introduction to command line class](http://leetusman.com/intermediate-programming/posts/intro-to-command-line/), which offers a more thorough explanation of what and how). 

Windows People: your interface is slightly different. You may want to install a [terminal emulator](http://cmder.net/)

### Anatomy of a command line statement 
```
Elizabeths-MacBook-Pro:~ elizabethbrooks$ echo hello 
```
###### The first piece is the PROMPT (including your current location in your computer, e.g. you're ready to write a command in the elizabethbrooks directory)$  
###### Then you have a COMMAND (what do you want the computer to do? echo, which means repeat something) 
###### And finally you've got an ARGUMENT (do it to what? echo the word hello).

```
Elizabeths-MacBook-Pro:~ elizabethbrooks$ cd documents
```
###### In the above line, I start in my home folder, like the big folder that holds everything on my computer and I cd or change directory to go to the documents folder. 

```
Elizabeths-MacBook-Pro:documents elizabethbrooks$ mkdir whyamihere
```
###### Then, you can see the prompt changes to show that I'm in documents. And then I use the mkdir command to make a directory (or folder) called whyamihere.

Try this yourself! 

-----

## Try typing some basic commands 
###### This section is forked from [antiboredom/automating-video-itp](https://github.com/antiboredom/automating-video-itp)


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

Now go to desktop

```
cd desktop
```

Make a new directory. (In this context, directory = folder). 

```
mkdir DIRECTORYNAME
```

Make a new text file. Call it whatever you want. 
```
cat > lovewilltearusapart.txt
```
When you push enter this time, you don't go back to the prompt. You get a cursor. You can now add text to your file.
Type some song lyrics that you like, or write down what you ate for breakfast.
```
When you're finished, push CONTROL D. 
```
Now go check to see if your file is there. 

Open your file using the default application (mac only)

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


Okay. You're basically a pro now. You're ready to: 
# Download and run software from the Command Line

There are lots of programs that you can run through the command line interface, so feel free to explore and try things out.

A good one to start with is a video editor called ffmpeg. [You can find a tutorial on downloading and using ffmpeg over here.](https://github.com/antiboredom/automating-video-itp/blob/master/FFMPEG.md)

Congratulations on your new knowledge. Remember, it's just the beginning. If you want to explore more of what the command line can do, [here is a good, thorough tutorial](https://www.learnenough.com/command-line-tutorial/basics). 

