Install & Setup
===
This assumes you have the Bebbo GCC compiler setup already working (see [here](https://github.com/0wen101/vscode-amiga-gcc-example-prb28)). This will be extended to build ACE.

To build ACE examples (and the ACE engine itself), some more tools are needed to be installed and configured.

1. [**CMake for Windows**](https://cmake.org/download/) - the build system used by ACE

2. [**MinGW**](https://sourceforge.net/projects/mingw/files/Installer/mingw-get-setup.exe/download) - Minimalist GNU for Windows -  allow Windows CMake to create Windows make files


3. [**AmigaCMakeCrossToolchains**](https://github.com/AmigaPorts/AmigaCMakeCrossToolchains) - the configuration for GCC. Assuming git is installed use this command to clone this repo to c for example:

    ```
    git clone https://github.com/AmigaPorts/AmigaCMakeCrossToolchains /c/AmigaCMakeCrossToolchains/
    ```

    as per [instructions](https://github.com/AmigaPorts/AmigaCMakeCrossToolchains) 
    , copy Generic.cmake to AmigaOS.cmake (i.e. make a copy of file Generic.cmake and rename it to AmigaOS.cmake)<br>


**File Path**
<br>After installing these it's necessary to add them to the path. You can either use your Windows path or set it in VS Code.
To set the path in VS Code, press Ctrl Shift P for the command palette, type '**Preferences Open User Settings JSON**' and then select it when appears to open the  settings file.

Edit the path as show:

![alt text](images/vscode-settings-path.jpg "path settings")





VS Code plugins
--

Next, install these extensions in VS Code.   Press Ctrl Shift X to access Extensions in VS Code.

![alt text](images/cmake.jpg "CMake")

![alt text](images/cmakeTools.jpg "CMakeTools")


That should be all that's required to start building, clone the workspace if haven't already:

```
git clone https://github.com/0wen101/vscode-amiga-gcc-ACE-helloworld
```
and it open vs code. Usually you will get a CMake message:

![alt text](images/cmake-tools-kit-message.jpg "CMake re-configure")

Can ignore this for now.




