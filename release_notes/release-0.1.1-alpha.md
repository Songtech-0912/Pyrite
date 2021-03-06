# Pre-Release 0.1.1 alpha

## TL;DR

* This release is for mainly for previewing purposes
* Pyrite is nowhere near production-ready (but basic functionalities should work)
* Help the project by trying our Pyrite and reporting bugs

## Download it

* [Linux](https://github.com/Songtech-0912/Pyrite/releases/download/v0.1.1-alpha/Pyrite-GNU-Linux.tar.xz)
* [MacOS](https://github.com/Songtech-0912/Pyrite/releases/download/v0.1.1-alpha/Pyrite-MacOS-installer.zip)
* [Windows (64-bit)](https://github.com/Songtech-0912/Pyrite/releases/download/v0.1.1-alpha/pyrite-win-64-bit.zip)

You can find all of these, and other downloads, on the [releases page](https://github.com/Songtech-0912/Pyrite/releases).

## Summary

This is Pyrite's **first** release, intended as a proof-of-concept for the concept. It's a *very* eary release, so bugs are expected...well, practically everywhere. There is a lot that has to be done:

* Code errors need to be fixed
* JavaScript code refactoring needs to be done (because some functions are over 50 lines long)
* Implement more of `Eel`'s native APIs to make it a true desktop application (because Pyrite is heavily dependent on web APIs at the moment)

In addition, the features are limited:

* Due to browser permission issues, pasting text may behave erratically
* There is no option to rename files
* Saving files is a very cumbersome process
* No syntax highlighting/code indentation/autocomplete yet
* UI design is not totally fleshed out

With all that being said, feel free to try Pyrite out! If you find any bugs, please report them on Github immediately ([here's how](#reporting-issues)). It would help greatly in the development process. 

In addition, from this point on, I will continue to release a new version of Pyrite every 2 weeks (if all goes well). I want everyone to test out Pyrite, not just programmers experienced in getting and compiling code.

## Reporting issues

To report a bug or an issue:

### Step 1

From the main repository page, click on the *issues* button.

![](https://guides.github.com/features/issues/navigation-highlight.png)

### Step 2

Press the green *new issue* button

### Step 3

Copy and paste this markdown markup into the editing box:

```markdown
## Expected Behavior


## Actual Behavior


## Steps to Reproduce the Problem

  1.
  1.
  1.

## Specifications

  - Version:
  - Platform:
  - Subsystem:
```

### Step 4

Fill in the main content of your issue

