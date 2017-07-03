# 100 Days Of Code - Log

### Day 1: April 03, 2017

Bit of PowerShell to get started
+ 3 days missed so far
```powershell
((get-date -date 2017/04/03).AddDays(100 + 3)).ToShortDateString()
2017-07-15
```

**Today's Progress**: Re-learning everything about python, had to google how to define a variable.
Also had to read up on how public/private instance variables work (they don't, everything is public in python).
Lots to re-read about, lists, dicts, classes etc. Not come very far but think an idea of how the game will be structured are begining to take place.

**Thoughts:** Need to make using objects feel more natural

**Link to work:** [Game Project](https://github.com/Wrexthor/Game01)

### Day 2: April 04, 2017

**Today's Progress**: Defined lots of classes for NPC's using inheritance. Starting to get a hang of how it works.
Also read a bunch of stuff on balancing game stats/exp gain etc. Not really relevant at this stage, need to get more stuff working before worrying about it. Done some minor functions for damage for the player as well, hard to figure out the best way to solve the problem. The code is the easy part, the how is whats hard.

**Thoughts:** Less thinking about feature K when im still implementing feature B, build a core, then expand.

**Link to work:** [Game Project](https://github.com/Wrexthor/Game01)

### Day 3: April 05, 2017

**Today's Progress**: Did a bunch of class methods and started working on an event class. Have done alot of "drawing" out how to handle the mechanics of the game class wise. 

**Thoughts:** The hard part is always defining the problem and how to solve it, the code part, so far, is easy.
Already i feel my grip on OOP has become much better when not following a tutorial or a guide. When i have to define a problem, solve it and then code it the reason for using OOP suddenly feels much more natural than just following guides on how to use them.

**Link to work:** [Game Project](https://github.com/Wrexthor/Game01)

### Day 4: April 06, 2017

**Today's Progress**: Banging my head against super in multiple class inheritance. It runs now, not sure if im doing it right...

**Thoughts:** Bloody forehead..

**Link to work:** [Game Project](https://github.com/Wrexthor/Game01)


### Day 5,6,7: April 09, 2017

**Today's Progress**: Weekend to Paris, managed to code on the plan both ways but missed saturday.

**Thoughts:** Coding without google is HARD!

**Link to work:** [Game Project](https://github.com/Wrexthor/Game01)


### Day 8: April 10, 2017

**Today's Progress**: Fought with using threads to read user input while preserving the while loop game thread. Like always the solution, once in hand, was quite simple.

**Thoughts:** Threads are awesome, lets abuse them and break everything!

**Link to work:** [Game Project](https://github.com/Wrexthor/Game01)

### Day 9: April 11, 2017

**Today's Progress**: Fixed typed commands to fully work, tried different methods of exiting the program (seems os.exit() works best in multiple threads). Fixed a few errors showing up once more methods worked and discovered more needing fixing. Guess thats the downside of getting more of the code thats never actually been run to run, you realised it does'nt work :)

**Thoughts:** Writing code without testing it NEVER works once you test it.

**Link to work:** [Game Project](https://github.com/Wrexthor/Game01)

### Day 10: April 12, 2017

**Today's Progress**: Could not muster motivation to work on my current game today, so instead made a tic tac toe game. Managed to get everything except the vitctory condition running. Did most of it with no tutorial as i don't want to copy code but actually have to solve problems on my own.

**Thoughts:** Don't follow tutorials too much.

**Link to work:** [Tic Tac Toe](https://github.com/Wrexthor/Tic-Tac-Toe)

### Day 11: April 13, 2017

**Today's Progress**: Basically completed the game with uninportant features like winning, preventing cheating, keeping the game running, score and input validation.

**Thoughts:** if not worked wierd today, will have to read further as why it did not work..

**Link to work:** [Tic Tac Toe](https://github.com/Wrexthor/Tic-Tac-Toe)

### Day 12: April 14, 2017

**Today's Progress**: Bad motivation today. Started with an ant simulator game but got stuck at pathfinding and generating random objects on a map grid. Might take it up again later but pathfinding might need to be a module or something rather than done from scratch, it seems HARD!

**Thoughts:** Sometimes wanting too much makes you hit a wall, KISS (keep it simple, stupid)!

**Link to work:** Did't upload it yet

### Day 13: April 15, 2017

**Today's Progress**: Running out of ideas so i took to the internetz and started going through the projects over at http://www.dreamincode.net/forums/topic/78802-martyr2s-mega-project-ideas-list/
Only did the reverse string and a semi working pig-latin today. Feels like it will be a good way to develop, even if the projects are a bit boring at times. Pig latin will continue tomorrow.

**Thoughts:** Going outside of ones comfort zone is always a good way to learn.

**Link to work:** Not wasting space on github, so no link

### Day 14: April 16, 2017

**Today's Progress**: Did a simple RSS feed reader (mostly stole the code tbh, but at least i understood it) and a few simple count words/vowels functions. Still doing the bare minimum, need to get that motivation back for longer sessions.

**Thoughts:** If you steal code, understand every part of it before running it.

**Link to work:** Not wasting space on github, so no link


### Day 15: April 17, 2017

**Today's Progress**: Redid RSS reader with my own "words", making the code a lot shorter and, for me, easier to read. Struggling to sort articles by date when having multiple sources. Seems different sites use different time/date standards so might have a bit of issue to get it right. Right now i get it in input order, which is chronological by site.

**Thoughts:** Make code your own by writing it yourself.

**Link to work:** Not wasting space on github, so no link

### Day 16: April 18, 2017

**Today's Progress**: So, jumping between projects like a mad man. Did lots of reading today on ciphers from the excellent https://inventwithpython.com/hacking/
Then i did some tutorials on server/client sockets, which has absolutly nothing to do with ciphers. Mostly copying code while trying to understand what it does so far, will see if/where i take it. Have an idea to write some form of peer to peer program, doing something smart with the connections.

**Thoughts:** My attention is about as stable as a rabbit on speed.

**Link to work:** Not wasting space on github, so no link

### Day 17: April 19, 2017

**Today's Progress**: Made a simple FTP client that i never tested (did not want to set up an FTP server just for testing it). Simple as in takes server/username/password/ftps as input and connects then does a dir, so no downloading/uploading. Also attempted to make CLI utilities using Click. Have some issues using PyCharm as the tutorials are all using something else.

**Thoughts:** Im getting tired of tutorials written for python 2x...

**Link to work:** Not wasting space on github, so no link

### Day 18: April 20, 2017

**Today's Progress**: Based on what i learned earlier about Click i made a password generator command line utility. It needs some polish to work correctly but all the features are there.

**Thoughts:** Learning modules seems to be a lot more intense than learning python itself, soo many modules...

**Link to work:** Not wasting space on github, so no link

### Day 19: April 21, 2017

**Today's Progress**: Complete PW gen CLI utility and managed to package it as exe, also managed to create most of an rss reader cli utility, working partially. Goal is to create several CLI utility, single purpose, that can be chained, used dayly and that are simple/portable/independend on python.

**Thoughts:** No thoughs, head empty.

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 20: April 22, 2017

**Today's Progress**: Some fixing of the RSS reader, so from working decently it now does not work at all. Bunch of problems converting between tuple and list before pickling the data. Managed to get it working (?) but now when it reads it reads nothing. More fun to be had! Also broke some other stuff when trying to fix the features.

**Thoughts:** So tired...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 21: April 23, 2017

**Today's Progress**: So more debugging, managed to fix a few issues by old school type variable values and types to console. Also switched from Pickles to JSON as i read there is no major point in using pickle vs JSON. Not sure how accurate that is but since JSON is more universal i might just as well learn that instead.
Fixed appending data, added clear all data. Still problems with remove item and the Live thingy is probably really broken, but thats for future Jack to sovle!

**Thoughts:** Debugging is not great.

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 22: April 24, 2017

**Today's Progress**: Even more debugging! I think i see the light, time to think of new features that wont work! :D

**Thoughts:** Debugging, still not great...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 23: April 25, 2017

**Today's Progress**: Tried and tried to get a live feature (watching for updates and posting them) to work but unless i build my own solution it does not seem like it's possible to get a simple check if there is a change on the feed (because no one use the standards in place for it...). Removed the feature and now all the other features SHOULD be working properly, even the match part. Also added some color coding that probably wont work for anyone, yay!

**Thoughts:** Standards, who needs em...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 24: April 26, 2017

**Today's Progress**: Begun building a unit converter that attempts to find a unit and number in a text and then convert it. Managed to get some basic (broken) functionality working. Need more failstates when it does not find the correct values etc.

**Thoughts:** Regex, listcomprehensions and other stuff, seems to be many ways to do things. Which one to learn tho...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 25: April 27, 2017

**Today's Progress**: So text parsing works, conversions work, added rounding to decimals (works). Now all that is needed is to add more than pounds and kg's.

**Thoughts:** Sometimes a true/none return is better than a detailed return.

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 26: April 28, 2017

**Today's Progress**: Gave learning regex an honest try today. Understand some basics of it but not getting it to do what i want. Basically a word should follow a white space or a digit and match a variable. This will leave some room for errors for some of the unit measurements but should work a lot better than just if word in text like im using now (which for things like L for litre, will work terribly).

**Thoughts:** Regex seems powerful, but slightly confusing, lots of syntax to learn.

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 27: April 29, 2017

**Today's Progress**: Bad focus today, built a quick stock gathering app, parsing a list for names, getting the stock price for each item and updating a list. Mostly broken so far, will save to json as well and compare to earlier prices once i get the basics working.

**Thoughts:** Some days complex things are just not a good idea

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 28: April 30, 2017

**Today's Progress**: Another bad day for coding it seems. Did some extremly minor work on the stock program.
**Thoughts:** Some days complex things are just not a good idea

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 29-30: May 01-02, 2017

**Today's Progress**: Programming on my surface without internet, no quality code resulting, but at least i did some coding. Last days i have stagnated in my development. While doing things repeatedly is a good way to learn, i also need to challenge myself more. It's not that what i have been writing is to easy, it's rather that is has been the same as ive written before. Repetition is good but i need to do something more challenging soon to continue developing. Might start with some simple graphical programming, thinking about trying out pygame..
**Thoughts:** Just doing something over and over gets you nowhere, it needs to be challenging as well.

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 31: May 03, 2017

**Today's Progress**: Made a whois script, which was mostly reading the documentation for a whois module and writing a few lines for it.
It works but doest not get any decent information (seems to be that of my ISP rather than the owner of the domain).
**Thoughts:** Bad day again, pls staph!

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 32: May 04, 2017

**Today's Progress**: Started following the awesome https://inventwithpython.com/pygame/chapters/ book. No free-will coding yet, still learning pygame stuff from the book, but i will count it as coding anyways as ive learned alot from it already. 
**Thoughts:** Graphical feedback can be great for seeing results, however using coordinates can also be extremly tedious.


### Day 33: May 05, 2017

**Today's Progress**: Continued following the book. Almost exclusivly wrote code from the book line by line today. While i do not belive it to be a great way of learning in the long run, i do belive it can be useful from time to time to just write large amounts of code, just to see how it can be done and to get it into your fingers. Finished the memory game, although i think i made misstakes somewhere as it's acting a bit wonky.
**Thoughts:** Lots of typing, good?


### Day 34: May 06, 2017

**Today's Progress**: First day i did not write a single line of code. I only read through the book explaining each piece i wrote yesterday. While the official rules do not allow this, i think it counts because it makes me think in terms of code and also explains some of the things i did not understand yesterday very well.
**Thoughts:** Lots of reading, better?


### Day 35: May 07, 2017

**Today's Progress**: Missed todays session because i simply forgot it.


### Day 36: May 08, 2017

**Today's Progress**: Reading up on unicode, doing more reading in the python game book. Need to find a project to work on soon.


### Day 37: May 09, 2017

**Today's Progress**: Wanted to make a RDP client using an SSH tunnel, but the RDP module was python 2.x only so gave up on the idea for now. Instead built a check outgoing port script (well wrapped around a module already doing it). Might look at his code and simple make the same thing my own instead tomorrow.

**Thoughts:** Acctually coding feels a lot more stimulating than reading tutorials/books

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 38: May 10, 2017

**Today's Progress**: After doing a daily security challenge using file handles i became curious and wanted to see if i could list all file handles in windows using python. It can probably be done in a much better (and faster!) way using windows API calls or pywin32 but i settled for psutil. It's slow listing each handle for each process and i would love a quick way to get handles of a specific file but i think both requires using a more in depth module or api calls.

**Thoughts:** Combinning windows interals with python, not as easy as i though, powershell would be much easier for this.

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 39: May 11, 2017

**Today's Progress**: Did a ssh tunnel script that opens rdp against the local bind address. Problem is i haven't tried it at all so it is 100% not to work. Will have to try it between 2 computers later. Need to set up an open port and a server as well.

**Thoughts:** Learned a lot about ssh, bindings etc. 

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 40: May 12, 2017

**Today's Progress**: Followed a guide to create a tcp flooding script and made it into a cmd util. Tried it on my server and it seems to work just fine.

**Thoughts:** Nothin much

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 41: May 13, 2017

**Today's Progress**: Built a keylogger, made it work, wanted to add more features, broke it. Tomorrow i will try to implement them so it can be useful.

**Thoughts:** Python versioning and packages can be a bitch sometimes.

**Link to work:** https://github.com/Wrexthor/jacks_util

### Day 42-43: May 15, 2017

**Today's Progress**: Continued work on keylogger. Added checking os version (will work on linux as well soon) and managed to get it running again. Having lots of problems with click. A friend recommended dockopt so will look in to that, less magic going on it seems.
Also read a bit on writing to google sheets from python. Requires registering which defeats the mobility of the program. Will either have to look to another solution or just make fix it and then leave the fields blank.

**Thoughts:** Magic behind the scenes can be bad when stuff does not work.

**Link to work:** https://github.com/Wrexthor/jacks_util

### Day 44-45: May 17, 2017

**Today's Progress**: Did some more work on keylogger and docopt. Also started a launcher project. It uses WMI to watch for process creation events, records them and, in the future, will make the user able to launch a program from the "index" of recently used programs. I might also include start menu items to make it more useful. Will be terminal based for now but might make it graphical at some point. I hope i can keep working on this project since i love using launchers and the ones currently around are never "good enough" for me.

**Thoughts:** WMI is hard...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 46: May 18, 2017

**Today's Progress**: Got most of the stuff working (searching, writing, reading to files). Tried getting autocomplete but seems to be easier on linux. Also im questioning how good of an idea it is to use windows process creationg events. Both for the performance and the results. It seems windows has several registry keys with information on manually started applications that i can query instead. So today was a lot of failing to query the registry with winreg. I guess i realised its better to let the makers of windows track user behaviour than to try to build a tracking system..

**Thoughts:** Registry is also hard...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 47-49: May 19-21, 2017

**Today's Progress**: Made reading regkeys work, also reading content of directories for filepaths AND reading target of lnk files (shortcuts). So now instead the program reads recent exe files from registry (same as recent on start menu), recent files from the recents folder (files opened) and next up is conent of start menu.

**Thoughts:** So much to know about how windows works...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 50: May 22, 2017

**Today's Progress**: Made getting files from folder recurcive and realised there are a LOT of files under recent fodler (20k+) so need to add a limit to how many are processed to prevent getting stuck too long at that point (most are junk files anyways).

**Thoughts:** They see me learnin, they be hatin...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 51: May 23, 2017

**Today's Progress**: Some changes to launcher so it now works decently. Started a new project (again...), a bulk renaming utility. Not tested yet and i know it's not quite working, but im on the right track. Just need to figure out how to make patterns work and how to validate them. Also needs to figure which patterns i want available.

**Thoughts:** Some regex up next...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 52: May 24, 2017

**Today's Progress**: Rewrote how files and filepaths are stored. Went with a dict storying key = filname and value = directory path. After making changes to the name the key is a tuple with oldname, newname. Had to rewrite a few functions to handle the new data input but feels good to have a standardized way to handle it. Next up i need to get click to work (setuptools are wonky on windows it seems) so i can test it, and then add some options for pattern matching, cusomt naming formats etc. Also added a strip exif data function for images as i have had need for it.

**Thoughts:** Python is not made for windows :(

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 53: May 25, 2017

**Today's Progress**: Rewrote how files are stored again, realised it was easier to just use a list of objects. First time i acctually feelt i really NEEDED a class rather than just a bunch of fuctions. Good way to understand the need for them. Also now click runs and i have tried the program on a testfolder and it works (upper/lower at least).

**Thoughts:** Class was needed, kewl!

**Link to work:** https://github.com/Wrexthor/jacks_util

### Day 54: May 26, 2017

**Today's Progress**: Fixed Exif remover and added a date appender function only to realised the file paths started breaking in the os.rename. Need to switch to using os.path but thats a problem for tomorrow me...

**Thoughts:** I bet linux would be so much easier to develop on...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 55: May 27, 2017

**Today's Progress**: Cleaned up the code and added a custom rename that will use a bunch of rules for renaming based on user input.
Tricky to plan and trickier yet to implement but fun :)

**Thoughts:** None really

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 56: May 28, 2017

**Today's Progress**: So there is an add date to filename function, but it only works partially. But it's something! :)

**Thoughts:** i miss switch from other languages...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 57: May 29, 2017

**Today's Progress**: Date time works and simulate works better :)

**Thoughts:** Love when the better solution is shorter..

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 58: May 30, 2017

**Today's Progress**: Colon breaks formating and i can't understand why...

**Thoughts:** I hate weird bugs...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 59: May 31, 2017

**Today's Progress**: Did not attempt to fixe the colon breaks, instead added verbose output and filter functionality to filter which files should be renamed.

**Thoughts:** Sometimes ignoring errors makes them go away (from your mind).

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 60: June 01, 2017

**Today's Progress**: Added tofolder to move x to y folder (using a match filter for x) and a change filending function. It feels as if adding new things are quite easy now that i have a solid base to work from. I just need to come up with new things. Might also want to check that it works on linux later on, most functions are built with it in mind but something will probably break on linux.

**Thoughts:** When the base is done, it's easier to add new features.

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 61: June 02, 2017

**Today's Progress**: Implemented append, replace and reverse, cleaned up the code more and started looking at implementing logging. Also thinking about some kind of threading to improve working with many files (have not tested performance, might be good enough already but would be cool with multi thread).

**Thoughts:** Moar features! Too many options to be useful soon...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 62: June 03, 2017

**Today's Progress**: Added a remove function and then felt done with the project (for now at least). Next up is to build a simple peer to peer client that sends chat messages between clients. Started reading up on sockets and experiment very lightly, will continue tomorrow.

**Thoughts:** Soo tired...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 63: June 04, 2017

**Today's Progress**: Begun a new project with a chat server and client using sockets. Mostly read tutorials and borrowed code. Will do more experimenting tomorrow to see how it works and make it my own to be able to send more fun stuff.

**Thoughts:** Sometimes you realise when going deeper that most concepts are faily simple but added to other simple concepts and eventually become very complex.

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 64: June 05, 2017

**Today's Progress**: Made a chat server and client, or rather a socket sendin text and showing it. Will work out how to make a stand alone application for chatting next, need to figure out if i should use a client/server for each direction or one connection for both directions.

**Thoughts:** Hmmm

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 65: June 06, 2017

**Today's Progress**: Followed a tutorial to make an IRC style chat, only to realise (when done) that it only works on linux due to how select works on io in windows (only works with sockets). Oh well, i learned a bit about how select works in python at least.

**Thoughts:** Again with the windows thing...

**Link to work:** https://github.com/Wrexthor/jacks_util


### Day 66: June 07, 2017

**Today's Progress**: So i switched language today. The reason being that i want to start playing in Unity eventually making simple games. Unity supports javascript and C#. I have worked in both but C# feels more future proof and diverse when it comes to non-web programming. Also i have a university course that begun in januari for C# (completed one last fall) and a bunch of assignments. I listed the pro's and con's of continuing python vs resuming C#.
Pro's of C#
Offical university grade
Structured course with heavy OOP direction
Can do Unity
.Net (i mainly work on windows)

Con's C#
Have to "start over" as i have forgotten/learned python instead
It's harder to learn (imo)

Pro's of Python
Easy to learn
I have learned a few things already/Fresh in mind
Incredibly diverse
Better for Linux

Con's
No unity
Not great on windows (works 90%, for a beginner 10% is a lot of breakage to troubleshoot)
No real structure to my learning, i tend to abandon projects, not challenge myself enough etc, miss out on some basic CS concepts etc

So i spent today remembering how to use Visual Studio, the syntax, started doing some parts of the first submission program.
It returns quite quick, even if i have Python fresh in mind, but some things will be difficult to accept how they work (some for the better, some for worse).
Also a bit booring working on pre-defined tasks but probably good for me.

**Thoughts:** back to basics..

**Link to work:** Nope


### Day 67: June 08, 2017

**Today's Progress**: Lots of reading, learning and not much coding today. Relearning C# takes a while it would seem (not that i knew it to begin with).

**Thoughts:** SeeeeeeeeeaaaaaaShaaaaarp

**Link to work:** Nope


### Day 68-69: June 09-10, 2017

**Today's Progress**: Missed day 68, day 69 i added inheritance in constructors to subclasses in assignment and read a bit on dynamic and static binding, trying to get a feel for what it really means

**Thoughts:** Tired

**Link to work:** Nope


### Day 70: June 11, 2017

**Today's Progress**: Just had time for a short tutorial today

**Thoughts:** Tired

**Link to work:** Nope


### Day 71 June 12, 2017

**Today's Progress**: Added a bunch of constructor to all the classes, read up on constructors, understood more about constructors, CONSTRUCTORS CONSTRUCTORS CONSTRUCTORS CONSTRUCTORS EVERYWHERE!

**Thoughts:** CONSTRUCTORS!

**Link to work:** Nope


### Day 72 June 13, 2017

**Today's Progress**: No coding today, only learning C# stuff.

**Thoughts:** LEARNING!

**Link to work:** Nope


### Day 73 June 14, 2017

**Today's Progress**: More tutorials today.

**Thoughts:** Sometimes having a harder task creates a motivational wall.

**Link to work:** Nope


### Day 74-76 June 15-17, 2017

**Today's Progress**: Have had a pretty bad week creationwise, learned a lot from tutorials, but really need to get back to typing code.
Might need to change from trying my assignment to my own projects for a while to avoid getting stuck again.

**Thoughts:** So much tutorials

**Link to work:** Nope


### Day 77 June 18, 2017

**Today's Progress**: Trying to get started with more small projects, so today i tried out some WPF instead of windows forms. I made a simple browser (which sounds harder than it is) using the .Net browser control. Simple way to get to use some basic WPF functions and getting more used to using .Net libraries (which i feel will be very important when using C#).

**Thoughts:** NOT a tutorial!

**Link to work:** Nope


### Day 78 June 19, 2017

**Today's Progress**: Started working on the GUI of a WPF file renamer utility. As i have already created a file renamer in python i feel it's a good way to learn c# and WPF. Converting the concepts to the "new" language shifts focus more to the language and less to the implementation of the code.

**Thoughts:** GUI'ing today.

**Link to work:** Nope


### Day 79-84 June 20-24, 2017

**Today's Progress**: Have had a few even worse days and been bouncing between projects. Not really "feeling" any of them but have had some success in following along a tutorial for a file explorer (good way not to get stuck) and, on midsummers eve when drunk, i started working on a simple password generator (because it's easy).

**Thoughts:** Im bad and i feel bad...

**Link to work:** Nope


### Day 85 June 25, 2017

**Today's Progress**: Following along a tutorial today, just writing a bunch of stuff and making sure that i understand it after having written it. In a way i think writing things you don't understand and then trying to understand it is a good way to learn more advanced patterns of coding. You realise how it all comes together in a way you would never have done it on your own.
Im often left with the feeling that "there must be an easier way to do this!" but i doubt im right about that...

**Thoughts:** So many classes and properties and inheritances and stuff....

**Link to work:** Nope


### Day 86 June 25, 2017

**Today's Progress**: Started on a Unity tutorial, the coding is rather minimal so far but i really feel it can be a boost to motivation so ill keep at it and coding will probably become more and more advanced as i go along

**Thoughts:** Unity, fun stuff so far!

**Link to work:** Nope


### Day 87-91 June 26-29, 2017

**Today's Progress**: Kept working in Unity, the programming is not the main focus but it is interesting to see how it is implemented in unity and how easy it is to leverage code to get stuff done. Will continue with unity stuff since it motivates me much better than other things in C# so far.

**Thoughts:** Unity, fun stuff so far!

**Link to work:** Nope


### Day 92 June 30, 2017

**Today's Progress**: More Unity, first game completed yesterday, begun working on a pong game tutorial today.

**Thoughts:** Unity, fun stuff so far!

**Link to work:** Nope


### Day 93-94 July 1-2, 2017

**Today's Progress**: Even more unity, almost completed pong (tough to convert from the tutorial javascript) and now started on a unity text based adventure game (weird huh?). Still rather light on the C# part but it's fun stuff. Tomorrow i might create more of a framework for what i need to practise in C# to get a solid in the basics.

**Thoughts:** Unity everywhere!

**Link to work:** Nope


### Day 95 July 3, 2017

**Today's Progress**: Unity stuffz

**Thoughts:** Unity everywhere!

**Link to work:** Nope
