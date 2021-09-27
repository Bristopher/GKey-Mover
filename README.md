# GKey-Mover
Once you double click GKey Mover it will unpack its files so I suggest putting it in its own folder first. After double clicking it, use Gkey Mover Config Generator Gui to create a config file to start using the program.

<br />

__Everything below here is basically a rip from what gets generated in your options.txt from Gui Generator which you will get access to when you double click GKey Mover__ 


# README
By default the binds for your GKey's are f13, f14, and f15. I use my keyboards software ICue to bind these to my GKeys and you will have to do something similar if you want to be able to use this program's GKey's

To edit the options simply chage each line above while following the ```Options for variables``` guide (helps to turn on line numbers in your txt editor)

Only edit varaibles at top of options files if you've read below about what each ones means

Make sure your folders are actually created when you try to use a bind because sometimes the names can be invalid and nothing will happen

Test to make sure each bind goes to each respected folder

Anything other than "True" is regarded as false

Don't try to rename the folders afterwards, it will only move the files to a folder named exactly what it says in the config (or create new folders if they don't exist)

By default I filled out the variables for what I use,
there will be a copy at the bottom of this txt to reference as an example for the future if you ever need it.

**DO NOT EDIT THE EIGHTEENTH LINE.** 

`"DO NOT EDIT THIS SINGLE LINE OF TEXT"`
 MUST NOT BE CHANGED TO TELL THE ARRAY THIS IS THE END OF THE VARIABLES

 <br />
 <br />
 
Go to my Github for updates, posts issues or questions, or request new features.<br />
https://github.com/Bristopher/GKey-Mover








# Options for variables
**EVERYTHING IS CASE SENSITIVE**


Are you using OBS or ShadowPlay to record clips?
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

Do you want to be prompt whether to use OBS or ShadowPlay when you launch GKey Mover?
**Thirteenth line usage: {True} or {False}**

Location where ShadowPlay folder is if the checkbox above is checked
**Fourteenth line usage: {C:\Users\cbuzi\Videos}**

Add the option to push Ctrl + GKey to open up gui to rename file
**Fifthteenth line usage: {True} or {False}**

Add the option to play a noise X miliseconds after a clip is recorded
**Sixteenth line usage: {True} or {False}

Amount in miliseconds to delay a sound being played after a clip is recored
**Seventeenth line usage: {70000} 

A new bind other than F13 for your G1GKey
**Eighteenth line usage: {^g} or {F16} 

A new bind other than F14 for your G2GKey
**Ninteenth line usage: {^h} or {F17} 

A new bind other than F15 for your G3GKe
**Twentieth line usage: {^j} or {F18} 

A new bind other than Ctrl + G1Key for renaming clips
**Twenty-First line usage: {+b} or {F19} 

Do you want to log when you rename clips?
**Twenty-Second line usage {True} or {False}




# NOTES
**First Line:**

>The difference with the options is whether you want to watch subtrees or not because shadowplay seperates clips by game

**Second Line:**

>This just logs when you move files with G binds just to keep a trail if you lose a clip, a new log is created and used everyday for ease of use

**Third Line:**

>Just the location to tell shadowplay or Obs to save your videos to

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

>Just select if you use both ShadowPlay and OBS, this lets you select which one your using when you launch GKey Movie

**Fourteenth Line:** **THIRTEENTH LINE MUST BE TRUE FOR THIS TO WORK**

>Just put the path of where ShadowPlay folder is including the file extension, put {default} in the option.txt to not use this

**Fifthteenth Line:**

>This adds the option to push Ctrl + GKey to open window to add text to the end of your clip's file name

**Sixteenth Line:** 

>This add option for a noise to be played to remind you that it's been x seconds since the last clip so if you want to record everything to edit your clips it into a continous clip record another clip now. To use the renaming feature hold Ctrl and whatever folder you moved your last clip to and a box will popup so you can add a name to the end of the file

**Seventeenth Line:** 

>This is the time in miliseconds to set the timer for, I reccomend 5 less seconds than your shadowplay time just to give some wiggle room for you to react and for other varaibles in the timing of all the code executing. For example I have shadowplay record 1:15 at a time so I want a sound notfication after 1:10 so i would put 70000 in the box 

**Eighteenth Line:**
>This allows you to change the default bind for your G1Gkey from F13 to whatever you want if you dont know the format click the bottom at the bottom of the gui

**Ninteenth Line:**
>This allows you to change the default bind for your G2Gkey from F14 to whatever you want if you dont know the format click the bottom at the bottom of the gui

**Twentieth Line:**
>This allows you to change the default bind for your G3Gkey from F15 to whatever you want if you dont know the format click the bottom at the bottom of the gui

**Twenty-First Line:** **FIFTEENTH LINE MUST BE TRUE FOR THIS TO WORK**
>This allows you to change the default bind for renaming clips from Ctrl + G1Gkey to whatever you want if you dont know the format click the bottom at the bottom of the gui

**Tenty-Second Line:**
>This will log any clip renaming, it will log the original name and the new name

**Twenty-Third Line:**
>This must not be chaged it tell the program this is the end of the options part of this txt

**Eighteenth Line:** 
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
False
default
True
70000
default
default
default
default
True
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
False
default
True
70000
default
default
default
default
True
DO NOT EDIT THIS SINGLE LINE OF TEXT
```



My default variables for shadowplay AND obs
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
True
C:\Users\cbuzi\Videos
True
True
70000
default
default
default
default
True
DO NOT EDIT THIS SINGLE LINE OF TEXT
```

