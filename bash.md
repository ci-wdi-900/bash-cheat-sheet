# Colin's BASH Cheat Sheet

### `ls`

* Usage: `ls [flags] [directory name]`
* What it does: lists all files and directories in the directory
* Useful flags:
    * `-a`: lists ALL files

---
### `cd`

* Usage: `cd [directory name]`
* What it does: changes location
* Tips and Tricks:
    * `cd ..` goes up a level
    * `cd ~` goes home
    * `cd -` goes back to previous location

---

### `mv`

* Usage: `mv file[...] location`
* What it does: moves chosen file(s) to chosen place
* Tips and Tricks:
    * You can rename a file by having its "destination" be a new filename.

---

### `pwd`

* Usage: `pwd`
* What it does: prints working directory.

---

### `mkdir`

* Usage: `mkdir [directory name...]`
* What it does: Makes a directory or directories.
* Useful flags:
  * `-p`: Makes parent directories given a path.



---

### `touch`

* Usage: `touch [file name...]`
* What it does: Makes a file or files.


---

### `rm`

* Usage: `rm [file name(s)]`
* What it does: Removes files.
* Useful flags:
  * `-rf`: removes directories as well

---

### `cp`

* Usage: `cp file[...] location`
* What it does: copies chosen file(s) to chosen place
* Tips and Tricks:
    * The last item must be a directory if copying multiple files.