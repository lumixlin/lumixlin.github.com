Date: 2014-01-08
Title: Linux utility
Slug: linux 
Tags: note,linux 


- set the screen brightness in ubuntu

		echo 9000 | sudo tee /sys/class/backlight/gmux_backlight/brightness

- set the keyboard background brightness

		echo 10 | sudo tee /sys/class/leds/smc::kbd_backlight/brightness

- tmux note
  tmux login the shell as a login shell, so it dose not run `~/.bashrc`. some alias in that file do not work, such as `alias ls='ls --color=auto'`. so, you should insert `case $- in *i*) . ~/.bashrc;; esac` in `~/.bash_profile` to run `~/.bashrc` in tmux


### Linux shortcut
- `Ctrl-Alt-l` = Lock screen
