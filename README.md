# developer-shortcut-toolkit
The goal of this project is to create custom aliases (shortcuts) in Linux to make common developer tasks faster and easier. Instead of typing long commands repeatedly, you create short commands .


## Project Overview

The Developer Shortcut Toolkit is a Linux administration project that improves productivity by creating custom Bash aliases for frequently used commands. Instead of repeatedly typing long commands, users can execute simple shortcuts to perform common administrative and development tasks efficiently.

---

## Objective

The objective of this project is to create a developer productivity toolkit using custom Bash aliases. The project demonstrates how Linux aliases can simplify repetitive tasks, reduce typing effort, and improve command-line efficiency.

---

## Skills Covered

- Bash Aliases
- .bashrc Configuration
- .bash_profile
- Linux Command Line
- Terminal Customization
- Redirection
- Linux Administration
- Productivity Automation

---

## Aliases Created

### 1. startweb

**Command**

```bash
alias startweb='sudo systemctl start apache2'
```

**Purpose**

Starts the Apache web server using a simple shortcut command.

---

### 2. goproj

**Command**

```bash
alias goproj='cd ~/projects'
```

**Purpose**

Navigates directly to the project directory.

---

### 3. clogs

**Command**

```bash
alias clogs='tail -f /var/log/syslog'
```

**Purpose**

Displays live system logs for monitoring and troubleshooting.

---

### 4. updateall

**Command**

```bash
alias updateall='sudo apt update && sudo apt upgrade -y'
```

**Purpose**

Updates all installed packages using a single command.

---

## Technologies Used

- Ubuntu Linux
- Bash Shell
- Linux Terminal
- Apache Web Server
- Systemctl
- APT Package Manager
- Linux File System

---

## Folder Structure

```text
developer-shortcut-toolkit/
│
├── README.md
│
├── bashrc/
│   └── bashrc_commands.txt
│
├── outputs/
│   ├── alias-list.txt
│   ├── alias-test.txt
│   └── productivity-report.txt
│
└── screenshots/
    ├── 01-bashrc-edit.png
    ├── 02-source-bashrc.png
    ├── 03-alias-list.png
    ├── 04-startweb-output.png
    ├── 05-goproj-output.png
    ├── 06-clogs-output.png
    ├── 07-updateall-output.png
    └── 08-alias-goproj.png
```

---

#Output
Screenshots of output are uploaded in outputs folder

---

## Learning Outcome

Through this project, I gained practical experience in:

- Creating custom Bash aliases
- Configuring the `.bashrc` file
- Customizing the Linux terminal environment
- Improving command-line productivity
- Simplifying repetitive administrative tasks
- Managing Linux services and package updates efficiently

This project strengthened my understanding of Linux shell customization and demonstrated how aliases can improve workflow efficiency for developers and system administrators.
