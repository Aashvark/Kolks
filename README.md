# Pre Version 1.5 Beta: Kolks

## We have a website! https://kolks.glitch.me.
## Here you can donate, and apply for a non-paying job. 

### About Kolks:
Kolks is a high-level programming language. The goal of Kolks is to make programming as simple as possible. It was designed to have a simple syntax and familiar feel compared to other languages although many advanced techniques are possible. The goal of Kolks is to make programming possible for a wide range of developers while still offering features that let powerful programs be built.

Kolk is created by: Ash "Pixel" Melvin.

##### *note: Kolks only has a windows build at the moment.*
### How to install Kolks:
#### Windows:
1. Download and run the setup file.
``KolksSetup-pre-v1.5-beta.exe``
This will also add Kolks to the path.  
2. Start Creating!
Have fun with Kolks!

#### Linux:
Install the Linux Package "wine" and attempt to run it.

### How to use Kolks:
#### How to run Kolks:
```
> kolks [filename].ko
```

#### Writing to the Terminal (Writing Things.):  
In order to write things you need a simple line of code:

```
#write "Hello Kolks!";
```

##### *note: Valid value types are strings, integers, floats, and bools (true, false).*

#### Traceing to the Terminal (Debug):  
In order to write things you need a simple line of code:

```
#trace "Hello Kolks!";
```

##### *note: Valid value types are strings, integers, floats, and bools (true, false).*
#### Variables:
In order to store data you need a line of code:

```
#define variable = "Hello Kolks!";
```

Use the same line of code with a different value to reassign the variable. such as:

```
#define variable = "Cliche Statement";
```

You can write the value of the function with this command:

```
#write variable;
```

##### note: Valid value types are strings, integers, floats, and bools (true, false);

#### Comments:
To comment surround anything with '$':
```
$ This is a comment! $
```

#### Functions:
In order to make a function you need these lines of code:

```
#define function():
  $ any value here $
#end
```

You can call the function using:

```
#run function();
```

In order to arguments you can:

```
#define function(x):
  $ any value here $
#end
```

You can call the function using:

```
#run function("Hello Kolks");
```

#### Delays:
In order to delay data you need a line of code:

```
#delay 3;
```

#### Conditions:
To make conditional statements:

```
#if variable == 3 #then
  $ write any value here $
#end
```

#### Loops:
To make loops:

```
#while variable == 3 #then
  $ write any value here $
#end
```

#### Imports:
You can import files with:
```
#import [File Name Here];
```

#### Builtin Functions:
These functions are:
```
&len
&str
&int
&float
&input
&random
&time
```

'&len' Gives length of a object. &len [obj]

'&str' Tranforms object to string. &str [obj]

'&int' Tranforms object to integer. &int [obj]

'&float' Tranforms object to float. &float [obj]

'&input' Tranforms object to integer. &int [obj]

'&random' Returns a value between 2 numbers. &random [obj1] [obj2]

'&time' Returns time. &time [format]
