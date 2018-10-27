# AntiDuckHunt (BadUSB script)
Script for BadUSBs that stops DuckHunt

Based on the following string from <a href="https://github.com/pmsosa/duckhunt/blob/master/duckhunt.conf">duckhunt.conf</a>:

``threshold = 30 # Speed Threshold between keystrokes in Milliseconds (Default: ~30 Miliseconds) | Anything faster than this is suspicious.``

**ducky_code_1**: this script makes a delay of 35 milliseconds between every keystroke, so DuckHunt won't detect our BadUSB. Then, it stops DuckHunt proccess. 

And:

``size = 25 # Size of array that holds the history of keystroke speeds (Default: 25 Keystokes)``

**ducky_code_2** (Recommended): same as ducky_code_1 but faster.
