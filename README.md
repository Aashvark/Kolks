# Version 1.3 Beta: Kolks

### About Kolks:
Kolks is a high-level programming language. The goal of Kolks is to make programming as simple as possible. It was designed to have a simple syntax and familiar feel compared to other languages although many advanced techniques are possible. The goal of Kolks is to make programming possible for a wide range of developers while still offering features that let powerful programs be built.

Kolks is Windows Only for the moment :(

Kolk is created by: Ash "Pixel" Melvin.

### How to install Kolks:
1. Download and run the setup file.
``KolksSetup1.3-beta.exe``
2. Open the command prompt and type in:    
```
setx /M PATH "%PATH%;c:\Programs\Kolks"
```
This will add Kolks to the path.  
3. Start Creating!
Have fun with Kolks

### for linux users:
install wine, uh- yea thats it. install wine try running it uh yeah.

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
#define function:
  $ any value here $
#end
```

You can call the function using:

```
#run function;
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
