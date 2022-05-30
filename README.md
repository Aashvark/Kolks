# Kolks Version 1.1!
### This is a proformace update, mainly to fix things that was horribly done in v1!

## Website: https://kolks.glitch.me/.
## Here you can donate, and apply for a non-paying job.
## And a official discord https://discord.gg/vu7bxCHu84. 

### About Kolks:
Kolks is a high-level programming language. The goal of Kolks is to make programming as simple as possible while also being able to make programming possible for a wide range of developers while still offering features that let powerful programs be built. It was designed to have a simple syntax and familiar feel compared to other languages although many advanced techniques are possible.

Kolks is created by: Ash "Pixel" Melvin.

##### *note: Kolks only has a windows build at the moment.*
### How to install Kolks:
#### Windows:
1. Download and run the setup file.
``KolksV1.1Setup.exe``
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

```md
#write "Hello Kolks!";
```

##### *note: Valid value types are strings, integers, floats, and bools (true, false).*

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

```
#delay 3;
```

#### Conditions:
To make conditional statements:

```
#if variable == 3 {
  $ write any value here $
}
```

you can now chain them!

```kolks
#if variable == 3 {
  $ write any value here $
#elif variable == 4 {
  $ write something else $
}
```

#### Loops:
To make loops:

```
#while variable == 3 {
  $ write any value here $
}
```

#### Imports:
You can import files with:
```
#import [File Name Here];
```

#### Builtin Functions:
These functions are:
```
&cast.len(obj)
&cast.str(obj)
&cast.int(obj)
&cast.float(obj)
&input(str)
&random(int, int)
&time(format) - (same as python's datetime strftime formatting)
&list.get(obj, index)
&list.add(obj, value)
&list.remove(obj, value | index)
```
