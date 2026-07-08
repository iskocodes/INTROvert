# INTROvert
A small program to make intros for other programs

## INTROduction
(get it?)  
<img src="https://github.com/iskocodes/INTROvert/blob/main/introvert%20gif.gif" alt="demo">  
Introvert allows you to choose any .ogv file to dispaly before opening ANY executable in your computer.
As you can probably guess from the files, this is a linux only program, reasons why stated later.

## Setting Introvert up
Setting Introvert up is really simple!  
Step 1 : Open it. This creates the necessary files for its usage.  
Step 2 : Close the program and find the configuration files. If alt + f4 doesnt work, try killing it or closing it through the app dock. 
The configuration files are located at ~/.local/share/godot/app_userdata/INTROvert  
Step 3 : Configure the Configuration files. There are two configuration files : destination.txt and video.txt  
Firstly, insert the path to the executable in destination.txt, staring from / (root)
Secondly, insert the path to the ogv video in video.txt, again, starting from /

And you're ready to use introvert!

## Unnecessary Files
Currently, when you download Introvert, you only actually need two of the files to use it, excluding the files created when you open it for the first time : Introvert.pck and Introvert.x86_64

## Using Introvert
To use introvert easily, just create a .desktop file pointing to it and put it on you desktop or OS's app drawer folder. If you do not know how to do this, please just use a youtube tutorial.  
Also there is a pixelated skip button on the bottom left corner that is normally invisible exceft for when you are hovering over it.  
Note that Introvert is currently borderless and maximized.

## OS Support
Introvert is currently tested on Ubuntu, but it should work just fine on any linux operating system.  
Windows support will be implemented later, and the link, when availiable, will be in this repository's README. My current estimate for Windows support is for August/September.  
Support for MacOS is unlikely to happen, since I or anyone I know has a personal Mac to install my software on.  

## Possible Questions
Q : Can't you just get a windows VM to test it and release it more easily?  
A : I could but I don't wanna contaminate my ssd lol  
  
Q : There is no video being displayed.  
A : Check the previous sections, if it still doesnt work, try to recreate the files by going in the filepath mentioned above.  
