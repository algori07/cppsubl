# C/C++ Build System

## Installation
On Windows, you need to open every file in folder `windows`, and replace `D:\\mingw32` with MinGW path (not inside `bin` subfolder).

Copy all file in folder `windows`(or `linux` if you use linux) to `%appdata%\Sublime Text\Packages\User\` (or `~/.config/sublime-text/Packages/User/` if you use linux).

## Dependencies
Windows: MinGW, [ConsolePauser](https://github.com/algori07/ConsolePauser) in your PATH. For beginner, you can copy `ConsolePauser.exe` into MinGW PATH (inside `bin` subfolder).

Linux: gcc, g++, make and [ConsolePauser](https://github.com/algori07/ConsolePauser) in your PATH. You can built it from source.

## Usage
Open C/C++ source file in Sublime Text, press `Ctrl + Shift + B` and select `C Algori` or `C++ Algori` (or with `- Run` or `- Build and Run`).

The next time, you just need to `Ctrl + B`.

Action:
`C Algori` or `C++ Algori`: Compile the source file
`C Algori - Run` or `C++ Algori - Run`: Run the executable without compiling.
`C Algori - Build and Run` or `C++ Algori - Build and Run`: Compile and run the executable.

