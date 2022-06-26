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

#### How to run Kolks:
```
> kolks [filename].ko
```

#### Website: https://kolks.glitch.me/
#### Discord https://discord.gg/vu7bxCHu84 

# Getting Started:
## Hello Kolks!
With Kolks installed go to your desired IDE (or Notepad if you want :D)

#### Traceing to the Terminal (Debug):  
In order to write things you need a simple line of code:

```md
#trace "Hello Kolks!";
```

##### *note: Valid value types are strings, integers, floats, and bools (true, false).*
#### Variables:
In order to store data you need a line of code:

```md
#define variable ~ "Hello Kolks!";
```

Use the same line of code with a different value to reassign the variable. such as:

```md
#define variable ~ "Cliche Statement";
```

you can make atoms (Variables with the same name and value, only works with string currently):
```md
#define :: ~ "greatness"
```

you can run these as you would down there.

You can write the value of the function with this command:

```md
#write variable;
```

##### note: Valid value types are strings, integers, floats, and bools (true, false);

#### Comments:
To comment surround anything with '$':
```md
$ This is a comment! $
```

#### Functions:
In order to make a function you need these lines of code:

```md
#define function ~ () {
  $ any value here $
}
```

You can call the function using:

```md
function();
```

In order to arguments you can:

```md
#define function ~ (x) {
  $ any value here $
}
```

You can call the function using:

```md
function("Hello Kolks");
```

You can make A self running FUNCTION with:
```md
#define *% ~ () {
  $ value not found $
}
```
you don't run this. you can't make multiple.

#### Delays:
In order to delay data you need a line of code:

```md
#delay 3;
```

#### Conditions:
To make conditional statements:

```md
#if variable == 3 {
  $ write any value here $
}
```

you can now chain them!

```md
#if variable == 3 {
  $ write any value here $
#elif variable == 4 {
  $ write something else $
}
```

#### Loops:
To make loops:

```md
#while variable == 3 {
  $ write any value here $
}
```

#### Imports:
You can import files with:
```md
#import [File Name Here];
```

#### Clear:
You can clear the terminal with:
```md
#clear;
```

#### Builtin Functions:
These functions are:
```md
&cast.len(obj)
&cast.str(obj)
&cast.int(obj)
&cast.float(obj)
&input(str)
&random(int, int)
&time(format) - (same as python's datetime |  strftime formatting)
&list.get(obj, index)
&list.add(obj, value)
&list.remove(obj, value | index)
&access.file(fn, type (w, r), (w only) value)
```
