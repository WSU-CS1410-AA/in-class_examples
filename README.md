This repository contains all example programs of this course. The header files are under the `include/` folder whereas the implementation (`.cpp`) files are organized by chapter (or week) under the `scr/` folder.

To compile and run these example programs:
* Open the terminal in the main folder of this repository
* If you are on Windows run:
```
wsl
```
* Go to the build folder
* If this is your first time running these examples, then run the command:
```
cmake ..
```

* To compile all these examples, run the following command. This might take a while as it will compile every single example. 
```
make 
```

* To run an example program, use its chapter number (`chp??`) and example number (`ex??`). For example, under the `src/chp01-Basics` folder there is a program named `ex02-primitives.cpp`. We use the chapter number `chp01` and the example number `ex02` to run this program by doing something like this:

```
./chp01-ex02 
```
