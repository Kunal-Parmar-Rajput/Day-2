# 1  Introduction

Today is Day 2 of my training. This repository will serve as my learning journal and quick‑reference for Linux fundamentals.
---
# 2 What is Booting?
Booting is the process of starting a computer. When you switch on your computer, the system loads the operating system (like Windows or Linux) from the hard drive into the RAM (memory), so you can use the computer.
---
Booting Process :
Power On – You turn on the computer. POST (Power-On Self-Test) – System checks hardware (RAM, keyboard, etc.). BIOS/UEFI Loads – Basic system firmware starts. Boot Loader Activated – BIOS/UEFI finds and runs the boot loader. OS Loading – Boot loader loads the operating system into RAM. System Ready – Operating system starts, and the computer is ready to use.
---
Types of Booting:
Cold Booting (Hard Booting):
Happens when the computer is started from the power-off state. Example: You press the power button to turn on your PC.
---
Warm Booting (Soft Booting):
Happens when the system restarts without turning off the power. Example: You click Restart or press Ctrl + Alt + Del.
---
# 3  What is the Kernel?

The kernel is the core component of any operating system. It:

manages hardware resources (CPU, memory, devices),

provides secure, abstract interfaces (system calls) for user programs
---
# 4 kernel and shell diagram.
![Kernel and Shell Animation](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*7Rp8NQIF6LwUfIurYrevew.gif)
---
# 5 File System structure.
##  Kernel & Shell Communication – Animated Overview
The Linux file system is structured hierarchically, starting from a root directory denoted by /.

![Kernel-Shell Demo](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*1J8PSDx4TETLbTGKEH6-Rw.gif)
---
# 6 Basic shell commands in linux.
##  Linux Command Reference

| Command   | Description                                     | Syntax                         |
|-----------|-------------------------------------------------|--------------------------------|
| `ls`      | Lists files and folders                         | `ls [options]`                 |
| `cd`      | Changes directory                               | `cd [directory]`              |
| `mkdir`   | Creates a new folder                            | `mkdir [folder_name]`         |
| `rmdir`   | Removes an empty folder                         | `rmdir [folder_name]`         |
| `touch`   | Creates a new empty file                        | `touch [file_name]`           |
| `rm`      | Removes files or folders                        | `rm [file/folder]`            |
| `cp`      | Copies files/folders                            | `cp [source] [destination]`   |
| `mv`      | Moves or renames files/folders                  | `mv [source] [destination]`   |
| `cat`     | Displays contents of a file                     | `cat [file_name]`             |
| `whatis`  | Gives a one-line description of a command       | `whatis [command]`            |
| `whereis` | Shows location of binary, source, and man page | `whereis [command]`           |
| `clear`   | Clears the terminal screen                      | `clear`                       |
| `man`     | Shows manual/help for a command                 | `man [command]`               |
| `exit`    | Closes the terminal session                     | `exit`                        |
| `pwd`     | Shows current directory path                    | `pwd`                         |

---
## 📸 Terminal Snapshot – Linux Commands

![Linux Terminal Commands](assets/linux-commands.png)

