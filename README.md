# FiSH module for irssi

Based on official from http://fish.secure.la/ (DEAD?)

Changed to use GMP by Dcoder

Basic autoconf/automake support by falso

## Requirements
* GNU MP - http://gmplib.org/
* Glib 2.x - http://www.gtk.org/
* irssi source code - http://irssi.org/

## Build instructions
First download the irssi source code and extract it for example in your home, lets say: **/home/jacinto/irssi-0.8.15**
```
# ./regen.sh

# ./configure --with-irssi-source=/home/jacinto/irssi-0.8.15

# make

# sudo cp src/.libs/libfish.so /usr/lib/irssi/modules
```
## To run
Inside irssi you just need to run
```
/load fish
```
## BUGS
* Some crashes when the terminal is set to UTF-8 and irssi recode is enabled
