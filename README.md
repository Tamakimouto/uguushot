# uguushot #
This is a shell script that takes a screenshot with scrot and uploads it to [uguu.se](uguu.se) the flow is quite similar to puush, infact this a minimalized adaption of puush4linux.

Unlike the original this one uses a 3rd party temporary file hosting server to cut out the need for API keys and the need to log in. Alot of error checking has also been cut out. This is mainly for personal use, but if anyone finds it useful, feel free to do whatever.

You pretty much run it with an option below, and it will upload the resulting screenshot and put a link in your clipbaord that you can share with friends.

## Dependencies ##
* `scrot`

* `curl`

## Usage
`uguushot <options>`

Alternatively, if you add the script to your $PATH, and bind it to a key, you can have it working at a keypress.

## Options
`-a` - Take a screenshot of an area and then upload it.

`-f` - Take a screenshot of the entire screen and upload it.

`-w` - Take a screenshot of the active window and upload it.

