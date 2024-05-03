This repository contains all the example programs referenced in the lecture notes of the course. The header files are located under the `include/` folder, while the implementation (`.cpp`) files are organized by chapter (or week) under the `src/` folder.

To ensure compatibility across platforms, this repository utilizes a Docker-based devcontainer. To run it, make sure you have the following installed first:

- The [Docker desktop application](https://www.docker.com/products/docker-desktop/). You don't need to do anything with Docker other than installing it on your operating system.
- [Visual Studio Code](https://code.visualstudio.com), which is the recommended code editor.
- Then, open Visual Studio Code and install the Dev Containers extension.

These tools are set up once at the beginning of the semester. Once all the above tools are installed, follow these steps:

To clone this repository, run the command:

```
git clone https://github.com/WSU-CS1410-AA/in-class_examples
```

This will create a folder named **in-class-examples**. Open this folder in Visual Studio Code. If you see a popup with an option for "Reopen in Container," click that. Otherwise, click the Dev Container icon at the bottom left corner and select "Reopen in Container." If this is the first time you are running this command, it will create a linux-based development container with all the tools you need to write, debug, and run C++ programs. If you've used this container before, the container will run without rebuilding, and it will start faster.

Having done that, to compile and run these example programs:

- Open the terminal in the main folder of this repository, and go to the build folder:

```
cd build
```

- If this is your first time running these examples, then run the command:

```
cmake ..
```

- To compile all these examples, run the following command. This might take a while as it will compile every single example:

```
make 
```

- To run an example program, use its chapter number (`chp??`) and example number (`ex??`). For example, under the `src/chp01-Basics` folder, there is a program named `ex02-primitives.cpp`. We use the chapter number `chp01` and the example number `ex02` to run this program by doing something like this:

```
./chp01-ex02 
```
