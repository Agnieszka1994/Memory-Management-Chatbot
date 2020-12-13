Dependencies for Running Locally

    cmake >= 3.11
        All OSes: click here for installation instructions
    make >= 4.1 (Linux, Mac), 3.81 (Windows)
        Linux: make is installed by default on most Linux distros
        Mac: install Xcode command line tools to get make
        Windows: Click here for installation instructions
    gcc/g++ >= 5.4
        Linux: gcc / g++ is installed by default on most Linux distros
        Mac: same deal as make - install Xcode command line tools
        Windows: recommend using MinGW
    wxWidgets >= 3.0
        Linux: sudo apt-get install libwxgtk3.0-dev libwxgtk3.0-0v5-dbg
        Mac: There is a homebrew installation available.
        Installation instructions can be found here. Some version numbers may need to be changed in instructions to install v3.0 or greater.


        wxWidgets:
        sudo apt install build-essential
        sudo apt install libgtk2.0-dev             
        sudo apt install libgtk-3-dev


        1.download wxWidgets: wxwidgets.org
        2.setup build environment
        sudo apt-get install libgtk-3-dev build-essential checkinstall
        3. Compile wxWidgets
        $ mkdir gtk-build
        $ cd gtk-build/
        $ ../configure --disable-shared --enable-unicode
        $ make
        4. Install with checkinstall
        $ sudo checkinstall



