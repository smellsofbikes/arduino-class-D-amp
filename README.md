# arduino-class-D-amp
port of george gardiner's attiny class d amp to a stock arduino uno.
It does not appear to run on a Duemilanove or a Diecemila, and I'm still trying to track down why.  The PWM output is completely hosed on them so I have to go through the timer1 setup configuration and figure out how they're different.
