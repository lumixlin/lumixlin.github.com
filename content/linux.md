Date: 2014-01-08
Title: Linux utility
Slug: linux 
Tags: note,linux 


- set the screen brightness in ubuntu

		echo 9000 | sudo tee /sys/class/backlight/gmux_backlight/brightness

- set the keyboard background brightness

		echo 10 | sudo tee /sys/class/leds/smc::kbd_backlight/brightness
