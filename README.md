## Good Shepherd (currently WIP)

Copyright &copy; 1984 Simon Springett

![Gameplay](http://f.cl.ly/items/2M1715460c3L263E0i28/GoodShepherd.mov.gif)

### How do I get this running?

First, you'll need a ZX Spectrum emulator, like [Fuse](http://fuse-emulator.sourceforge.net/). Versions are available for Mac, Linux and PC.

Next, download the binary TAP (tape) file

* [GoodShepherd.tap](https://github.com/paulspringett/GoodShepherd/raw/v1.0/GoodShepherd.tap)

and load this into the emulator.

Then type `RUN` (the emulator may autocomplete `R` to `RUN`) and press `ENTER`.

### How do I modify source and re-compile?

You'll need to clone down this repository

    git clone git://github.com/paulspringett/GoodShepherd.git
    cd GoodShepherd/

and open the `GoodShepherd.bas` file, which contains the source code for the game, written in 48k BASIC.

To run the code in an emulator you'll need to compile the BASIC into a TAP file.

I've included the `bas2tap` (Copyright M. van der Heide) utility for doing this. I've already compiled the C code into a binary for Mac OS X. There's also a Windows EXE version. If you're on another version Mac OS X or Linux you may need to compile your own version.

To compile

    ./bas2tap/bas2tap GoodShepherd.bas

### Is there anything else that needs doing?

Yes! It would be great to include a WAV file, so people could load the program onto a cassette tape to play for real!

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/InteractiveResource" property="dct:title" rel="dct:type">Good Shepherd</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Simon Springett</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/deed.en_US">Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License</a>.
