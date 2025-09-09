Linux -> open source , free , more secure , powerful CLIs , fast performance





Architecture of Linux



+------------------------------------------+

|         User Applications (Top Layer)    |

|  (e.g., browsers, text editors, games)   |

+------------------------------------------+

|            Shell / CLI / GUI             |

|   (User interacts via bash, zsh, GNOME)  |

+------------------------------------------+

|          System Call Interface (SCI)     |

|  (Gate between user space and kernel)    |

+------------------------------------------+

|             Kernel Space                 |

| +--------------------------------------+ |

| |      Process Management              | |

| |      Memory Management               | |

| |      File System                     | |

| |      Device Drivers                  | |

| |      Network Stack                   | |

| +--------------------------------------+ |

+------------------------------------------+

|            Hardware (CPU, RAM, I/O)      |

+------------------------------------------+













\# Linux , windows and mac differences



Linux,MAC -> more secure than windows , powerfull CLI then the windows , limited gaming support but excellent in windows



Linux case sensititve file name but not for the windows











\# completed the basic commands like

ls , mkdir , mv , pwd , cd , cp(copies) , rm , chmod(Chnage mode like read , write and execute)



**touch filename.txt** -> to create a new file



**echo** "This is the content of my file." > filename.txt   -> to write a line inside the created file



**cat > filename.txt**  -> it waits for a input from our side after giving input do ctrl+D to save and exit



**wc filename.txt** -> used to find out the number of new lines, word count, byte, and characters count in a file



**history** -> to show the history of the all the commands used by you



**clear** -> to clear the terminal



**diff file1.txt file2.txt**  -> compares two files line by line to find differences. The output will be the lines that are different.



**exit** -> this command is used to exit the current shell



**compgen -c** -> to see the list of all commands of Linux









