Date: 2014-01-08
Title: A Script to Play Pictures and Musics
Slug: playmusic
Tags: linux,shell


*I learn this script from*  [blog](http://hongjiang.info/script-for-wedding/) *and make a littile change.*

		#!/bin/bash 

		#kill screensaver
		killall "screensaver"

		function clean() {
			#kill mplayer
			killall "mplayer"
			killall "feh"
		}

		function show_pic() {
			#bg music
			mplayer -playlist "list" &
			#show pictures
			feh --cycle-once -FD8 "/home/long/Pictures/long"
		}

		function play() {
			#play music
			clean 2>/dev/null
			show_pic
		}

		play
