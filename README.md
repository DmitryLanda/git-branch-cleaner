Git Branch Cleaner
===================

### This is my personal playground.
#### I am just tried to make work with git more simple

When we have a big or dinamyc project. We have a lot of legacy git branches which was created, modified and merged.
After that this branches become unneded... But in most cases we have no time (or desire) to remove it
from local and remote repositories.

This script should resolve this issues.

### Uses:

```$ git clone```

```$ vim clear-branches``` Open and modify variables in the top of file (it marks as *configurable variables*)

```$ ./clear-branches -h``` to get help

```$ ./clear-branches -c l``` create file with list of your local branches.<br>
    Also it shoud open file for editing after creation

```$ ./clear-branches -d l``` remove all specified branches from local repository

```$ ./clear-branches -c r``` create file with list of your remote branches.<br>
    Also it shoud open file for editing after creation

```$ ./clear-branches -d r``` remove all specified branches from remote repository<br>
    *This action not fully automaticaly yet. <br>
    It require your fingerkey or username/password after each branch for remove*

### TO DO:

* Add full support for removing remote branches
* Make script more flexible