### GDB: GNU Debugger
GDB is mainly used for debugging the C language. Below are the commands I have used in C prograaming to help my debugging. Some of these are hard to come by when searching online.

### Start GDB
1. To Enable Debugging, Compile Program With: ```gcc -g program.c```
2. To Start Debugging: ```gdb ./<executable_name>```
3. Run the program with the debugger attached with: ```run <arg1> <arg2>```

### Commands
- set break point with: ```b <line_number>```
- set conditional break points with: ```b <line_number> if i == <number_of_loops>```
  - useful for big loop iterations,  MAKE SURE TO USE '==' NOT '=' 
- set breakpoint of a function: ```b <function_name>```
  - works well if function is in seperate file
- show all break points with: ```info break```
- delete break point with: ```del <breakpoint_number>```
  - breakpoint number is found with the info break command
- To set a break point in a different file you are currently in, use: ```b FileName.c:<line_number>```
- show variable value once with: ```print <variable_name>```
- show variable value with each step: ```display <variable_name>```
- step into a function with: ```s```   
- go to next line with: ```n```
- continue to next break point with: ```c```
- repeat previous command with: ```<enter_key>```
- restart debugger from the beginning with: ```r```
- quit the debugger with: ```q```
- view stack with: ```bt```
- once viewing the stack, move up the stack with: ```up```
