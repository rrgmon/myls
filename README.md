# Simple File Explorer written with C++

This is a simple file-explorer that lists the files and directories in the PWD. It also lists the size of each individual file.
The program was written using C++ and uses the std::filesystem library for most of its functionality.

How to use?
1. Run the 'make' command to build the executable.
2. Run ./myls to run the program.
3. To make it a universal terminal command - `sudo mv myls /usr/local/bin/`
Now you can use the command 'myls' from any directory. Just type in 'myls'.

What's missing?
- Not visually appealing and it is cluttered.
- No other functionality besides the aforementioned one.

TODO:
- Make the output look cleaner.
- Add further options mimicking the existing 'ls' command.