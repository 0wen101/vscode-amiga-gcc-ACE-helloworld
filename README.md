VS Code Amiga GCC ACE Example
===

ACE - Amiga C Engine - is a C based Amiga game and demo engine. Check out the [ACE Github Repo](https://github.com/AmigaPorts/ACE/tree/main) which has lots of information on it.

Continuing from the helloworld gcc [example](https://github.com/0wen101/vscode-amiga-gcc-example-prb28), this repo contains pre configured VS Code helloworld and Starfield projects on windows from the ACE github page.

The aim is to show how to set all this up and configure VS Code to compile and run the examples in a Windows environment via WinUAE

To build ACE, a build system called CMake is used. This can be configured within reason to generate  Makefiles compatible with GCC and more specifically Bebbos updated version of the Amiga GCC cross compiler.

The source files can be built either from the command line or using VS Code.

Refer to docs for setup and build instructions 

1. [install and setup](docs/1_install_and_setup.md)<br>
2. [build](docs/2_build.md)<br>
3. [run](docs/3_run.md)<br>
<br>
<br>

![alt text](docs/images/Starfield_001.gif "Starfield")