# GKey-Mover
A Script that lets you sort your clips while you're creating them. Also has options for notifications when a clip is saved or moved, and many more features. Currently is configured to work best with either OBS or ShadowPlay.


<br />
<br />
Everything below here is basically the same as what gets generated in your options.txt from Gui Generator 

# README
To edit the options simply chage each line above while following the ```Options for variables``` guide (helps to turn on line numbers in your txt editor)

Only edit varaibles at top of options files if you've read below about what each ones means.

Make sure your folders are actually created when you try to use a bind because sometimes the names can be invalid and nothing will happen

Test to make sure each bind goes to each respected folder

Anything other than "True" is regarded as false

Don't try to rename the folders afterwards, it will only move the files to a folder named exactly what it says in the config (or create new folders if they don't exist)

By default I filled out the variables for what I use,
there will be a copy at the bottom of this txt to reference as an example for the future if you ever need it.

**DO NOT EDIT THE ELEVENTH LINE.** 

`"DO NOT EDIT THIS SINGLE LINE OF TEXT"`
 MUST NOT BE CHANGED TO TELL THE ARRAY THIS IS THE END OF THE VARIABLES\

 <br />
 <br />
 
Go to my Github for updates, posts issues or questions, or request new features.<br />
https://github.com/Bristopher/GKey-Mover








# Options for variables
**EVERYTHING IS CASE SENSITIVE**


Are you using obs obs or shadowplay to record clips?
**First line usage: {obs} or {shadowplay}**

Do you want a log to be generated that logs which file was moved to which G binded folder?
**Second line usage: {True} or {False}**

What folder do you save you videos to?
**Third line usage: {C:\Users\cbuzi\Videos\OBS NVENC Videos}**

Do you want a windows notification when you save a clip with the clip name?
**Fourth line usage: {True} or {False}** 

Do you want a notification sound when you save a clip?
**Fifth line usage: {True} or {False}** 

Do you want a notification sound when you move a clip with a G bind?
**Sixth line usage: {True} or {False}** 

What do you want your bind1 folder name to be?
**Seventh line usage: {funny} or {beastmodeclips}**

What do you want your bind2 folder name to be?
**Eigth line usage: {funny} or {beastmodeclips}**

What do you want your bind3 folder name to be?
**Ninth line usage: {funny} or {beastmodeclips}**

A custom sound's location to play when a clip is saved
**Tenth line usage: {C:\Users\cbuzi\Documents\CrimewaveTone.wav} or leave blank for default**

Do you want a sound played when a Gkey is pressed and doesn't move a video?
**Eleventh line usage: {True} or {False}**

A custom sound's location to play when a GKey is pressed and no file is moved
**Twelvth line usage: {C:\Users\cbuzi\Documents\CrimewaveTone.wav} or leave blank for default**








# NOTES
**First Line:**

>The difference with the options is whether you want to watch subtrees or not because shadowplay seperates clips by game

**Second Line:**

>This just logs when you move files with G binds just to keep a trail if you loose a clips, a new log is created and used everyday for ease of use

**Third Line:**

>Just the locations to tell shadowplay or Obs to save your videos to

**Fourth Line:**

>This is just a standard Windows notifcation the pops up for a couple seconds and lets you be aware the clips did actually save and displays the name of the clip

**Fifth Line:**

>This plays a notificaiton sound when a clip is saved, unless the sound is chaged on the tenth line a default sound will play

**Sixth Line:**	

>This plays a notificaiton sound (Single beep for G1, Double beep for G2, Triple Beep for G3) when a clip moved by a G bind

**Seventh Line:**

>Simply the name of the folder to move clips to

**Eigth Line:**

>Simply the name of the folder to move clips to

**Ninth Line:**

>Simply the name of the folder to move clips to

**Tenth Line:**	 **FIFTH LINE MUST BE TRUE FOR THIS TO WORK**

>Just put the path of a sound to play when you save a clip including the file extension, put {default} in the option.txt for the default sound

**Eleventh Line:**

>This plays a notification sound when no clip was moved / no clip is slected and nothing has moved, helps if you want to spam buttom to make sure a clip moved

**Twelvth Line:** **ELEVENTH LINE MUST BE TRUE FOR THIS TO WORK** 

>Just put the path of a sound to play when you save a clip including the file extension, put {default} in the option.txt for the default sound

**Thirteenth Line:** 

>This must not be chaged it tell the program this is the end of the options part of this txt












# References


My default variables for obs 
**(DON'T EDIT THIS, IT'S A REFERENCE)**
```
obs
True
C:\Users\cbuzi\Videos\OBS NVENC Videos
False
True
True
!! or ! (G1)
odd or checked (G2)
!!! (G3)
default
True
default
DO NOT EDIT THIS SINGLE LINE OF TEXT
```




My default variables for shadowplay
**(DON'T EDIT THIS, IT'S A REFERENCE)**
```
shadowplay
True
C:\Users\cbuzi\Videos
False
True
True
!! or ! (G1)
odd or checked (G2)
!!! (G3)
default
True
default
DO NOT EDIT THIS SINGLE LINE OF TEXT
```
