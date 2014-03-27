#Popcorn time [![Dependency Status](https://david-dm.org/popcorn-team/popcorn-app.svg?theme=shields.io)](https://david-dm.org/popcorn-team/popcorn-app)

### Intro ###

100% Working build of Popcorn time from Popcorn Team's RC1.

### About ###
This project will be a pet project of mine, to constantly improve and add to Popcorn time's functionality.
I have tons of plans to make this application even better than ever, and add additional features & tweaks.

### Builds & Downloads ###
Check back soon for download links to working builds for Mac, and Linux.

-Windows XP/7/8
https://mega.co.nz/#!vNgAwC7Z!apZeYcGFXrBKIErPV0AZ73lQUus8iUH0BEQ3Rd1Ksyk

### Status  ###
Currently RC1 barebones till I get my hands on it :-)

### Current APIs Providers  ###
- [YIFY](http://yts.re/api) movie torrents API.
- [YifySubtitles](ysubtitles.com) for subtitles
- [Trakt.tv](https://trakt.tv/) for movies metadata.

### Development ###
This praticular project will be just me for now, but if you would like to help out
in Popcorn time's development, or have a hand in it, visit Popcorn team to lend a hand.
https://github.com/popcorn-team/popcorn-app/wiki/Development

### Known Bugs ###
You shouldn't have any problems, but some might.

- Missing libudev.so.0
Search for libudev.so.0 on your distribution. Most of the time it can be easily fixed by creating a symbolic link from libudev.so to libudev.so.0

- "Gtk-WARNING **: cannot open display:"
Try running `export DISPLAY=:0.0`

- "The video format is not supported"
See: https://github.com/rogerwang/node-webkit/wiki/Support-mp3-and-h264-in-video-and-audio-tag
