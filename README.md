# Lab 1 - A Simple Linux Shell

## Compiling the Source Code and Running the Shell

1. Since this is a linux shell, you first need to be able to access a linux environment. If you do not have a linux kernel installed, you will need to download a linux distribution or a linux emulator.
2. Next, you need to make sure you can access the file myshell.c (if using an emulator). Make sure this file is in a place you can access from the terminal.
3. Once you can access the linux kernel and the specified file, get to the directory where the file is stored using cd to enter a folder, or cd.. to go up one level in the folder structure.
4. Before you can run the program, you need to compile the source code using the following command:
   > gcc -o myshell myshell.c
5. Finally, when the code is successfully compiled, use the following command to run the program:
   >./myshell

## How to Use the Shell

Once you are in the shell, you should see the default prompt switch to **linux (your uanet id)|>**. If it does not switch to this, the program is not running. The program can run a total of 10 commands. Below you can find the list of commands and how to use them.
1. Copy one file to another
   > C ***file1 file2***
2. Delete a file
   > D ***file***
3. Display a comment on the screen
   > E ***comment***
4. Display a the user manual
   > H
5. List the contents of the current directory
    > L
6. Create the named text file
    > M ***file***
7. Display the contents of the specified file
    > P ***file***
8. Quit the shell
    > Q
9. Clear the screen
     > W
10. Run the specified program
    > X ***program***

## List of Functions

- **main()**: The main function that runs the shell and reads/executes the commands entered by the user
- **parseCommand()**: Parses the command line input and populates command_t
- **printPrompt()**: Displays the current user and the machine name for the shell prompt
- **readCommand()**:Reads the command entered by the user
  
## Citations
