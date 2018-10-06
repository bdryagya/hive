%title: Linux Basic Commands - [Beginner Level]
%author: [credit: hive]
%date: 2018-10-06

-> Some *basic commands*
-> *to start* using Linux/Unix CLI.

---

## pwd
	print working directory

---

## ls
	list content in working directory
	
	- ls
	- ls -l
	- ls -a
	- ls -latr

---

## cd
	change directory, navigate
	
	- cd dir
	- cd ..
	- cd ../dir
	- cd /home/bdryagya

---

## mkdir
	make directory
	
	- mkdir <directory name>

---

## rmdir
	remove directory
	
	- rmdir <directory name>
	- must be empty

---

## cp
	copy files and folders
	
	- cp <src> <dst>

---

## mv
	move/rename files and folders
	
	- mv <src> <dst>

---

## rm
	remove files/folders
	
	- rm <file>
	- rm -r <directory>

---

## cat
	concatenate, print file/s
	
	- cat file
	- cat file1 file2

---

## --help
	help on how to use the command
	
	- <command> --help

---

## man
	manual pages of commands and packages
	
	- man <command>
	- man ls
	- man nginx

---

## locate
	locate files
	
	- locate <filename>
	- usage it's db

---

## find
	find files/folder
	
	- find <path> <flags>
	- find . -name hello

---

## apt-get, yum
	package management
	
	- apt-get install <packagename>
	- apt-cache search <packagename>
	- apt-get remove <packagename>

---

## df
	disk free, disk usage
	
	- df
	- df -h
	- df -m
	- df -i

---

## du
	disk usage
	
	- du
	- du -sh
	- du -sh file
	- du -sh *

---

## tab/double tab
	use for completion
	
	- ls file<tab>
	- cd /home/<tab></tab>

---

## file
	get type of file
	
	- file <file>

---

## sort
	sort content
	
	- sort <filename>

---

## | <pipe>
	pass output to another program/command
	
	- ls|cat
	- cat file|sort

---

## uniq
	unique in sorted data
	
	- uniq <file>
	- cat file|sort|uniq
	- cat file|sort|uniq -c

---

## head
	head portion of file
	
	- head <filename>
	- head -n <number of lines> file
	- head -3 file

---

## tail
	tail portion of file
	
	- tail <file>
	- tail -100 <file>
	- tail -f <file>

---

## vi/vim
	visual editor, simple yet powerful
	
	- vi filename
	- modes
		- normal
		- edit
		- paste
		- ...
	- navigate
		- hjkl
	- some commands
		- i, a, d, dd, yy, 3yy, /

---

## more/less
	paginate
	
	- more <filename>
	- cat <filename>|more
	- less <filemame>

---

-> Thank You! <-


-> [Note can be found here](a.md)
