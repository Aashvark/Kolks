# ![Kolks Logo](/kolks.png "Kolks Logo") Kolks Version 1.3!
## Introduction
### About Kolks:
Kolks is a mostly high-level programming language. The goal of Kolks was to originally create a moderatly good programming language that may used professionally but, the goal of Kolks now is to make it easy to learn while still being capable to create a wide-range of products and programs.

Kolks is created by: Ashton "Pixel" Melvin.

### How to install Kolks:
#### Windows:
1. Download and run the setup file. ``KolksV1.3Setup.exe`` This will also add Kolks to the path.  
2. Start Creating! Have fun with Kolks!

#### Linux:
Install the Linux Package "wine" and attempt to run it.

#### Website: https://kolks.glitch.me/
#### Discord https://discord.gg/vu7bxCHu84 

# Getting Started:
## Hello Kolks!
Make a new folder, this is where our project will be located. Lets name it "HelloKolks". Lets create the main file, which will be called "main.ko".

Lets write "Hello Kolks":
```objectivec
  #write "Hello Kolks!";
```
This should output:
```log
> kolks main.ko
  Hello Kolks!
```
Optionally for single-file projects such as this one you can use a function that only runs the main file. Such as:
```objectivec
  #define *% ~ () {
    #write "This should only show if this is the file your running";
  };
```
This should output the same thing:
```log
> kolks main.ko
  Hello Kolks!
```
