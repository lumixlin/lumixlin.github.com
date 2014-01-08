Date: 2014-01-02
Title: Command Line note
Slug: cml
Tags: note,linux

### Skills
- `cat <(ls)` = use `<(ls)` as a file. Process `ls` used as a file.
- `ls > >(cat)` = redirect ls to file `>(cat)`.


### Login and authentication
- `passwd` = change local password

------

### Infomation
- `date` = show date and time
- `cal` = display calendar and date
- `info` = online document for GNU grograms
- `whoami` = who is logged onto this terminal

------

### File management
- `feh` = image viewer

------

### Data manipulation
- `tr` = translate characters
- `cut` = cut out columns from a files
- `paste` = paste columns into a files
- `xclip -sel clip < data` = put data into clipboard

------

### Networking/communications
- `lftp` = easy use ftp client
- `nc` = simple TCP/IP server for file sharing. close after one connect
- `python -m SimpleHTTPServer` simple web server for file sharing. can browse all files in current directory

------

### Package management
- `apt-get`
	+ `install name` = install or update a pakage

	----------

	+ `update` = update your package list
	+ `upgrade ` = upgrade all package in your system
	+ `disk-upgrad` = upgrade system

	-----------------

	+ `remove name` = unistall a package but keep the configure files
	+ `--pure remove name` = unistall a package and its configure files
	+ `autoclean` = clean the installed or unistalled package backup
	+ `clean` = clean the installed package backup
	
	+ `dpkg --force-all --pure name` = unistall a package ,it is dangerous

	---------------

- `apt-cache`
	+ `showpkg name` = show package infomation
	+ `show name`  = show package infomation

	+ `pkgname name` = list all package with preceding name `name`
	
	+ `dpkg -l package-name-pattern` = list the package name with pattern

	+ `dpkg -S file` = show the package who has file `file`
	+ `dpkg -L name` = list all file belong to package `name`

-------

- `aptitude` = a better pakage manage tool
	+ `search string` = search package

	+ `install name` = install package
	
	+ `update` = update package list
	+ `upgrade` = upgrade package
	
	+ `remove name` = unistall package
	+ `pure name` = unistall package and remove configure file

