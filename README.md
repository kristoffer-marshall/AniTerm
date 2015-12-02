# AniTerm

[![screenshot](https://github.com/kristoffer-marshall/AniTerm/raw/master/screenshot-zoidberg.gif)]

## Displays colorful animations in your terminal

Wouldn't it be cool to display an animated gif in your terminal each time you log into a server? Well now you can! Throw the executable "aniterm" into ~/bin and the ".aniterm/" directory into your home directory. chmod +x ~/bin/aniterm, then execute!

## Run AniTerm
**Usage:** `aniterm [loop_times] [timeout seconds] DIRECTORY_OF_FRAMES`

Default loop_times: 3

Default timeout: .1

Example: `aniterm 5 .2 banana`


###To actually make your own animations:
1. Download Fabulous from https://pypi.python.org/pypi/fabulous or https://github.com/jart/fabulous (python.org looks to be newer).
2. Copy the "fabulous" script into something in your $PATH, say $HOME/bin
3. Edit the "fabulous" script to point to the actual path where the program resides (this is a hack)
4. Copy the gifToAnimation script to that same directory
5. Run the gifToAnimation script on a gif: ex. gifToAnimation banana.gif

After all of this is done, you can use aniterm to show the animation: ex. aniterm banana

Please email me if you have any issues and I'll be happy to add/modify code to make this easier to deploy.
