# bright

## Introduction

Control and display the screen brightness.

## Requirements

- xorg-xset

## Initialize

Changing the brightness involves modifying a system file, which is owned by
root. As a result, the permissions of the files need to be changed.

Initialize the brightness script with the following command.
```
sudo ./bright --init
```
