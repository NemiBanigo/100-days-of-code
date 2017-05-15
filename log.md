# 100 Days Of Code - Log

### Day 1: April 03, 2017

Bit of PowerShell to get started
+ 2 days missed so far
```powershell
((get-date -date 2017/04/03).AddDays(100 + 2)).ToShortDateString()
2017-07-14
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

