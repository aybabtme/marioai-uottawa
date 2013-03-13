# MarioAI - uOttawa

## Introduction
Ready to use projects for MarioAI development using Eclipse or IntelliJ.

You will need a Unix/Linux system to follow this guide.  If you run Windows, install [Github for Windows](http://windows.github.com/) and use their provided shell. Otherwise, figure it out yourself :)

# Installation

Using your favourite shell, follow these steps.

*    Create a folder where you feel your project will grow in happiness.

```
$ mkdir -p path/under/the/sun/
$ cd path/under/the/sun/
```

*    Initialize an empty repo in there!

```
$ git init
```
*    Add this repository as your `upstream` remote:
    
```
$ git remote add upstream git@github.com:aybabtme/marioai-uottawa.git
```

*    Create a repo on your Github, choose whatever name you feel like.  Now, ignore all the instructions Github tells you about initializing stuff and adding README and whatever else.  Do this instead :

```
$ git remote add origin git@github.com:<username>/<reponame>.git
```
Say you called your repo `sunflower-ai`, and your Github handle be `sunlover`.  

```
$ git remote add origin git@github.com:sunlover/sunflower-ai.git
```

__Now do nothing else!__ Move to the next section.

# IDE Specifics

If you followed properly last section, you're ready to setup your project in a specific manner, depending your IDE (or lack thereof).
 
## IntelliJ
Let's start out with IntelliJ, because I've been told that all the cool kids use IntelliJ, or so they say.  And you do want to be a cool kid, don't you?

If you don't have IntelliJ, grab the Community Edition for free [here](https://www.jetbrains.com/idea/download/index.html).

Still in your project folder, do:

```
$ git pull upstream idea
$ git push origin master
```

__Then follow the rest of the instructions in the [IntelliJ Guide](idea.md).__

## Eclipse
You're used to Eclipse because for whatever reason, you're used to Eclipse?  No problem.

If for some reason, you're used to Eclipse but you don't have it installed, no worries, follow [this link](#intellij).

If you already have Eclipse installed, still in your project folder do:

```
$ git pull upstream eclipse
$ git push origin master
```

__Then follow the rest of the instructions in the [Eclipse Guide](eclipse.md).__

## Dr. Java & Netbeans

You love Dr. Java since the first day you met it in ITI1120/ITI1520?

Or you like the net and you eat beans everyday, and that was enough to convince you that Netbeans is the shit?

__Follow the [Dr. Java Guide](https://www.youtube.com/watch?v=oHg5SJYRHA0) and [Netbeans Guide](https://www.youtube.com/watch?v=oHg5SJYRHA0).__

## Command Line

So you're that courageous, you can't get out of your `vim` screen and all you care about is monospaced black and white screens?

Fine!  All you got to do is:

```
$ git pull upstream master
$ git push origin master
```

And for the rest, figure it all yourself!  After all, if you wish to do Java development without an IDE, you should be able to setup your environment yourself!

I thought for a while about providing Ant scripts, but figured it would be irrelevant to anybody who uses their custom stuff anyway.