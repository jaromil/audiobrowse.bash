# audiobrowse.bash
simple commandline audio preview/copy/move of (sample)directories for sample-artists / musician and producers

<center><img alt="" src="audiobrowse.bash.png"/></center>

# Why

Because deadsimple audition of directories with samples should be easy peasy like so:

# Installation 

In your terminal type:

     wget "https://github.com/coderofsalvation/audiobrowse.bash/raw/master/audiobrowse.bash"
     chmod 755 audiobrowse.bash
     ./audiobrowse.bash

# Features

* pressing enter tries to play the audio (when playback utils are available)
* easy directory navigation using arrowkeys + '.' (=directory up)
* pressing 'c' will copy selected file to particular dir (prompted once)
* pressing 'm' will move selected file to particular dir (prompted once)
* pressing 'f' will filter results
* pressing '?' will give statistics on the current file like so:

<img alt="" src="audiobrowse.bash.stats.png"/>

# Dependancies

* bash (so any *NIX system)

# Hint

Install the 'sox' and 'mpg123' for stats and mp3-playback.

copy audiobrowse.bash to ~/bin and add ~/bin to your PATH like so:

    export PATH=$PATH:~/bin

This way you can type 'audiob\<TAB\>' from any directory

## Why

Sometimes less is more and faster.

# Credits 

audiobrowse.bash was built upon the [lscd project](https://github.com/hut/lscd)

