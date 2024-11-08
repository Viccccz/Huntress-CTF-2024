# Description

_#Warmups_<br>
_#Author: @JohnHammond#6971_<br>

When you gaze long into the void, the void gazes also into you... 

## Solution

1. Connect to the server.<br>
   `nc challenge.ctf.games 30124 > aaa`
2. Remove all colorization characters and symbols.<br>
   `cat aaa | sed -r "s/\x1B\[([0-9]{1,3}(;[0-9]{1,2};?)?)?[mGK]//g"`                                                          
3. Get the flag.

