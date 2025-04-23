## 🐧 Ubuntu/Linux (Debian-based)

1. Update package list:

	`sudo apt update`

2. Install g++:

	`sudo apt install g++`

3. Verify installation:

   	`g++ --version`

## 🪟 Windows (via MinGW)

1. Download MinGW:

        Visit: https://sourceforge.net/projects/mingw/

2. Install MinGW:

        Run the installer.

        Select mingw32-gcc-g++ under "Basic Setup".

        Click Installation > Apply Changes.

3. Add MinGW to PATH:

        Add C:\MinGW\bin to your system Path.

 4. Verify installation: Open Command Prompt:

        `g++ --version`


After install GCC, clone the GitHub: `https://github.com/HSw109/ofdma-doxygen-logging`

Then install the additional library:

`sudo apt install libspdlog-dev`


Then compile with command: `g++ main.cc transmission.cc destination.cc packet.cc event.cc -o main -lfmt`

Then run with command: `./main --log_level=<info/trace/debug>` each is level of logging




