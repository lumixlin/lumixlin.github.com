Date: 2014-01-02
Title: Command Line note
Slug: cml
Tags: note,linux

#### Login and authentication
- `passwd` = change local password

------

#### Infomation
- `date` = show date and time
- `info` = online document for GNU grograms
- `whoami` = who is logged onto this terminal

------

#### File management

------

#### Data manipulation
- `tr` = translate characters
- `cut` = cut out columns from a files
- `paste` = paste columns into a files

------

#### Networking/communications
- `lftp` = easy use ftp client

------

#### System management
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

