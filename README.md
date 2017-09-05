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

Where *user* is the user that will use the brightness script.

To alter the screen brightness, this script modifies a system file, initially
owned by root. Initialization, allows the designated user to modify this file by
changing the ownership to the user.
