# Arduino controlled fuel pump deactivation when driving on LPG
**Simple Arduino Nano Shield for shutting off car fuel pump when driving on LPG (gas).**

My fuel pump failed twice in three years because I mostly drive on LPG and forget to keep some gasoline in the tank. So I had to repace a fuel pump twice in three years :)
I came up with a simple idea to control a fuel pump with an Arduino Nano. It would shut off the pump wen LPG kicks in.
Then, it would turn the pump on for short periods of time (3s) every 5 minute or so, just to maintain the preasure to the fuel injestors line.
It should also turn the pump back on when switching from LPG to gasoline.
