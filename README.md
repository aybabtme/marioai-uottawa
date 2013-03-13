# MarioAI - uOttawa

## Introduction
Ready to use projects for MarioAI development using Eclipse or IntelliJ.

You will need a Unix/Linux system to follow this guide.  If you run Windows, install [Github for Windows]() and use their provided shell. Otherwise, figure it out yourself :)

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

*    Create a repo on your Github, choose whatever name you feel like.  Say you called your repo `sunflower-ai`, and your Github handle be `sunlover`.  Now, ignore all the instructions Github tells you about initializing stuff and adding README and whatever else.  Do this instead:

```
$ git remote add origin git@github.com:sunlover/sunflower.git
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

## Command Line

So you're that courageous, you can't get out of your `vim` screen and all you care about is monospaced black and white screens?

Fine!  All you got to do is:

```
$ git pull upstream master
$ git push origin master
```

And for the rest, figure it all yourself!  After all, if you wish to do Java development without an IDE, you should be able to setup your environment yourself!

I thought for a while about providing Ant scripts, but figured it would be irrelevant to anybody who uses their custom stuff anyway.