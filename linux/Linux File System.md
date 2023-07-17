A [[File System]] controls how data is stored

Each group of data is called a [[Project 1]] and the structure and the logic rules used to manage files and their names are called a [[File System]].

A File System is a logical collection of files on a [[Partition]] or disk

On a [[Linux]] system, everything is considered to be a file.  (even psychical devices)

On [[Linux]] file and directory names are case-sensitive.


## Directory Structure

The root directory is named `/`


## The Filesystem Hierarchy Standard - 1

[Filesystem Hierarchy Standard](https://refspecs.linuxfoundation.org/fhs.shtml)

[[/bin]] contains binaries or user executable files which a available to all users.
[[/sbin]] contains applications that only the superuser (hence the initial s) will need.
[[/boot]] contains files required for starting your system.
[[/home]] is where you will find your users' home directories. Under this directory there is another directory for each user, if that particular user has a home directory. root has a home directory separated from the rest of the users' home directories and is [[/root]]
[[/dev]] contains device files.
[[/etc]] contains shared library files used by different applications.
[[/lib]] contains shared library files used by different applications.
[[/media]] is used for external storage will be automatically mounted.
[[/mnt]] is like [[/media]] but it's not very often used these days. 


## File status




