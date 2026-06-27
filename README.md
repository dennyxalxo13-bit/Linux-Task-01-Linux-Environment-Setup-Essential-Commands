Linux Task 01 — Linux Environment Setup & Essential Commands

Intern: Denny Xalxo
Track: Cyber Security / Ethical Hacking Internship
Task: Linux Environment Setup & Essential Commands (Task 01)

 Overview

This repository documents the first task of my Cyber Security internship, focused on getting comfortable with the Linux environment. It covers installing and verifying a Linux setup, practicing essential terminal commands, managing directories and files, collecting system information, and researching why Linux is foundational to cybersecurity and ethical hacking work.

 Objectives


Set up and verify a working Linux environment
Practice core navigation and terminal commands
Create and manage a structured directory layout using the CLI
Perform common file operations (create, copy, move, rename, delete)
Collect and record key system information
Understand why Linux is the operating system of choice in cybersecurity


Task Breakdown

Part A — Linux Installation & Verification

Verified the Linux setup with screenshots of the desktop environment, terminal window, and system information.

Part B — Basic Navigation Commands

Practiced foundational commands for moving around and inspecting the system:

CommandPurposepwdDisplays the current working directorylsLists files and directories in the current directoryls -laLists all files, including hidden ones, with detailscdChanges the current directoryclearClears the terminal screenhistoryDisplays previously executed commandswhoamiDisplays the current usernamehostnameDisplays the system hostname

Part C — Directory Management

Built the following directory structure using mkdir, cd, and tree:

CyberSecurity_Lab/
├── Networking/
├── Linux/
├── CyberSecurity/
├── EthicalHacking/
└── Reports/

Part D — File Management

Created notes.txt, commands.txt, and report.txt inside the folders above, then practiced creating, copying, moving, renaming, and deleting files using:

CommandFunctiontouchCreates a new empty filecpCopies files/directoriesmvMoves or renames filesrmDeletes files/directoriesmkdirCreates directoriestreeDisplays directory structure

Part E — System Information Collection

Ran the following commands and recorded the output:


uname -a — Kernel version
hostname — Hostname
whoami — Username
date — Current date and time
uptime — System uptime
pwd — Current directory


Part F — Linux Research Activity

Researched and documented:


What is Linux? — An open-source operating system based on Unix that manages hardware and software resources, accessible via GUI or command-line.
Why is Linux important in cybersecurity? — It offers strong security, stability, flexibility, and powerful CLI tools; most security tools and servers run on Linux.
Linux vs. Windows — A comparison of openness, cost, security, customizability, and primary user base.
What is a Linux distribution? — A Linux version bundled with software, package managers, and desktop environments (e.g., Ubuntu, Kali Linux, Parrot OS).
Why ethical hackers prefer Linux — Open source, tool compatibility, system control, lightweight performance, scripting support, and strong networking/security features.


 Repository Contents

FileDescriptionLinux_Task_01_Denny_Xalxo.docxFull task report with explanations, command outputs, and screenshots

 Tools Used


Linux Terminal
tree utility for directory visualization


 Key Learnings


Built confidence navigating and managing a Linux filesystem entirely from the command line
Understood how directory structures and file operations form the basis of organized system administration
Gained context on why Linux underpins most cybersecurity and ethical hacking workflows


 Author

Denny Xalxo
Cyber Security Intern
