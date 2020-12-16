
# ChatBot

This repo contains the final project of the 3rd course of the Udacity Nanodegree. 

The purpose of this project was analyze and modify a ChatBot program, which is able to discuss some `C++` related topics based on the content of a knowledge base. 
The program was optimized from a memory management perspective and the following improvements have been implemented:
- smart pointers
- move semantics
- exclusive ownership and correct memory allocation
- knowledge base extended with `flow control` related topics.
- improved artwork


## Requirements
- compiler support for C++14 (gcc/g++ >= 5.4).
- cmake >= 3.11
- make >= 4.1 (Linux, Mac), 3.81 (Windows)
- wxWidgets library >= 3.0 

## wxWidgets for Linux
Install from App Store:
`sudo apt-get install libwxgtk3.0-dev libwxgtk3`
Or follow the below steps:

- download [wxWidgets](http://wxwidgets.org/)

- setup build environment
```shell
sudo apt-get install libgtk-3-dev build-essential checkinstall
```
- compile wxWidgets 
```shell
mkdir gtk-build
cd gtk-build/
../configure --disable-shared --enable-unicode
make
```
- install with checkinstall
```shell
sudo checkinstall
```

## Get started
```
git clone https://github.com/Agnieszka1994/Linux-System-Monitor
cd Linux-System-Monitor/
mkdir build && cd build/
cmake ..
make
./monitor
```

## Sample usage

[![img]()]()

