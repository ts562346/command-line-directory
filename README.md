# command-line-directory

## Simple Shell for Linux

## Overview
This project required us to design and implement a C program serving as a shell for Linux. The shell accepts user commands, executes each command in a separate process, and provides a history feature to access recently entered commands.

## Detailed Requirements
### Task 1: Creating a Child Process
Modify the provided `main()` function to create a child process using `fork()` and execute the user's command using `execvp()`. Parse user input into tokens and store them in an array of character strings (`args`).

### Task 2: Creating a History Feature
Enhance the shell to include a history feature, allowing users to save and list recently entered commands along with their process IDs. Save up to 10 commands, with the most recent command always at ID 1.

### Additional Requirements
- Support retrieving and executing commands from history using `!!` or `!N`.
- Implement basic error handling for various scenarios, displaying appropriate messages.
- Utilize the GNU C library (glibc) to implement the required features.
