This is basically a directory w/ cutechess-cli.exe and dlls installed.  It also contans .bat file to lauch cutechess as well as some sub-directories
to hold the generated pgns, training tools, etc.

![alt tag](https://raw.githubusercontent.com/FireFather/fire-zero/master/bitmaps/nnue-auto.PNG)

I recommend mirroring the installation to a networked drive for backup & redundancy. I use a licensed version of Beyond Compare.
![alt tag](https://raw.githubusercontent.com/FireFather/fire-zero/master/bitmaps/nnue-auto-dir.PNG)

The nnue-train directory holds nnue-gui.exe (training management), sf-nnue exectuables (training), and .bat files to organize data  rename nets etc.

![alt tag](https://raw.githubusercontent.com/FireFather/fire-zero/master/bitmaps/nnue-train.PNG)

The 'run' scripts which launch cutechess-cli to generate self-play games automatically renames the pgn with a unique signature: MMDDYYYY-HHMMSS.pgn
![alt tag](https://raw.githubusercontent.com/FireFather/fire-zero/master/bitmaps/pgns.PNG)

