# ![Kolks Logo](/kolks_full.png "Kolks Logo")

Version 1.3, Build: ***Stable***

## Introduction
### About Kolks:
Kolks is a high-level programming language. The goal of Kolks was to originally create a moderately good and functional programming language that may used in professional cases. Instead the goal of Kolks is to make a easy to learn programming language, while still having the capabilities to create a wide-range of products and programs.

Kolks is created by: Ashton "Pixel" Melvin.

### How to install Kolks:
#### Windows:
1. Download and run the setup file. ``Kolks-v1.3.exe`` This will also add Kolks to the path.  
2. Start Creating! Have fun with Kolks!

#### Linux:
Install the Linux Package "wine" and attempt to run it.

# Official Links:
#### Website: https://kolks.glitch.me/
#### GitHub : https://github.com/AshPixel/Kolks/
#### VSCode : https://marketplace.visualstudio.com/items?itemName=KolksTeam.kolks
#### Discord: https://discord.gg/vu7bxCHu84
#### Twitter: https://twitter.com/KensuiE

# Getting Started:
## Hello Kolks!
Make a new folder, this is where our project will be located. Lets name it "HelloKolks". Lets create the main file, which will be called "main.ko".

Lets write "Hello Kolks":
```objectivec
  #write "Hello Kolks!";
```
In order to run it use the command `kolks main.ko`
or go to the folder where the file is held and open it.
This should output:
```log
Hello Kolks
# [time] ms
```

Optionally for single-file projects such as this one you can use a entry function that only runs the main file. Such as:
```objectivec
  #define *% ~ () {
    #write "This should only show if this is the file your running";
  };
```

This should output the same thing:
```log
Hello Kolks
# Kolks Program Terminated: [time]
```

## Group and Assign
After writing your first Kolks Script you will need to learn how to store variables and make functions.
You make can make functions like so:
```objectivec
  #define milk ~ () {
    
  };
```

This is a pretty bland function but since it doesn't have anything in it lets add a variable:
```objectivec
  #define milk ~ () {
    #define coffee ~ "Perfectly done";
  };
```

Okay now that we know how to make functions lets run it!
This should output:
```log
# [time] ms
```

Uh-oh it seems that we don't have a output.
Since we haven't ran our function or used the variable at all! Lets quickly do that.
You run functions like:
```objectivec
  milk();
```

and for now you can use `#write coffee;` to print the current variable.
Your file should now look like:
```objectivec
  #define milk ~ () {
    #define coffee ~ "Perfectly done";
    #write coffee;
  };
  milk();
```
This should output:
```log
Perfectly done
# [time] ms
```
# Beginner Concepts
## Conditions
Conditions (If you don't know already) are statements where the output only runs if the condition is true.
As a example lets set a condition so see if apples are red:
```objectivec
#define apples ~ "red";
#if apples == "red" {
  #write "Apples are red";
};
``` 
If we run the file:
```log
Apples are red
# [time] ms
```
Success!

Since we can do one lets do more ! 
```objectivec
#define apples ~ "red";
#if apples == "red" {
  #write true;
};
#if apples == "blue" {
  #write false;
};
#if apples == "green" {
  #write false;
};
```

As this would work as intended lets trim it a bit by replacing some of the if statements with a elif statement.
This makes the code cleaner and gets rid of unexepected outputs.

```objectivec
#define apples ~ "red";
#if apples == "red" {
  #write true;
} #elif apples == "blue" {
  #write false;
} #elif apples == "green" {
  #write false;
};
```

The result should be:
```log
true
# [time] ms
```

Similar to the if statement we have the while statement:
```objectivec
#while true {
  #write "Hi";
};
```
but unlike the if statement you cannot chain them and they run until the condition isnt true anymore.
