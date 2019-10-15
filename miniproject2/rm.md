# rm
The description of *rm* according to [computerhope.com](https://www.computerhope.com/unix/urm.htm) states that the command removes each file specified on the command line. By default, it does not remove directories.

When **rm** is executed with the:
*-r
or
*-R
options, it recursively deletes any matching directories, their subdirectories, and all files they contain. See removing directories below for details.

The removal process unlinksa file name in a filesystem from its associated data, and marks that space on the storage device as usable by future writes. In other words, when you remove a file, the date in the file isn't changed, but it's no longer associated with a filename.

The date itself is not destroyed, but after being unlinked with rm, it becomes inaccessible.
