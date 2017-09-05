# BRIGHT

## What is it?

Control and display the screen brightness.

## Requirements

```
- xset
```

## Installation

```
$ sudo ./bright --init --user=<user>
```

Where *<user>* is the user that will use the brightness script.

To alter the screen brightness, this script modifies a system file, initially
owned by root.

Initialization, allows the designated user to modify this file by changing the
ownership to the user.

Initializing the script will change the ownership of the brightness file, to the
designated user, thus allowing them to modify the file. The brightness file is
located at:

```
/sys/class/backlight/intel_backlight/brightness
```
