# 🛠️ Initial Setup & Linux Commands

---

## 📋 Table of Contents

- [1. Download & Install VMware](#1-download--install-vmware)
- [2. Download Kali Linux](#2-download-kali-linux)
  - [Windows](#-windows)
  - [macOS](#-macos)
  - [Linux](#-linux)
- [3. Setting Up Kali in VMware](#3-setting-up-kali-in-vmware)
- [4. Starting & Logging Into Kali](#4-starting--logging-into-kali)
- [5. Linux Terminal Commands](#5-linux-terminal-commands)

---

## 1. Download & Install VMware

VMware Workstation Player lets you run Kali Linux as a virtual machine on your existing OS — no need to wipe your computer.

1. Go to **[https://www.vmware.com/products/workstation-player.html](https://www.vmware.com/products/workstation-player.html)**
2. Click **Download for Free**
3. Choose the version for your operating system (Windows or Linux)
4. Run the installer and follow the on-screen steps
5. Restart your computer when prompted

> 💡 **macOS users:** VMware Fusion is the macOS equivalent — available at **[https://www.vmware.com/products/fusion.html](https://www.vmware.com/products/fusion.html)**

---

## 2. Download Kali Linux

Go to the official Kali Linux download page:
👉 **[https://www.kali.org/get-kali/](https://www.kali.org/get-kali/)**

Select **Pre-built Virtual Machines** for the easiest setup with VMware.

---

### 🪟 Windows

1. Visit [https://www.kali.org/get-kali/#kali-virtual-machines](https://www.kali.org/get-kali/#kali-virtual-machines)
2. Download the **VMware** 64-bit image (`.7z` file)
3. Extract the `.7z` file using [7-Zip](https://www.7-zip.org/)
4. Open the extracted `.vmx` file directly with **VMware Workstation Player**

---

### 🍎 macOS

1. Visit [https://www.kali.org/get-kali/#kali-virtual-machines](https://www.kali.org/get-kali/#kali-virtual-machines)
2. Download the **VMware** image (`.7z` file)
3. Extract using [The Unarchiver](https://theunarchiver.com/) or `p7zip` via Homebrew:
   ```bash
   brew install p7zip
   7z x kali-linux-*.7z
   ```
4. Open the `.vmx` file with **VMware Fusion**

---

### 🐧 Linux

1. Visit [https://www.kali.org/get-kali/#kali-virtual-machines](https://www.kali.org/get-kali/#kali-virtual-machines)
2. Download the **VMware** image (`.7z` file)
3. Extract via terminal:
   ```bash
   sudo apt install p7zip-full   # Debian/Ubuntu
   7z x kali-linux-*.7z
   ```
4. Open the `.vmx` file with **VMware Workstation Player**

---

## 3. Setting Up Kali in VMware

1. Open **VMware Workstation Player** (or Fusion on macOS)
2. Click **Open a Virtual Machine**
3. Navigate to the extracted Kali folder and select the `.vmx` file
4. Click **Play Virtual Machine** to boot it up
5. If prompted about the machine being moved, select **I Copied It**

---

## 4. Starting & Logging Into Kali

1. Once Kali boots, you will see the login screen
2. Enter the default credentials:

   | Field    | Value    |
   |----------|----------|
   | Username | `kali`   |
   | Password | `kali`   |

3. Click **Log In** — you are now inside Kali Linux ✅
4. To open the **Terminal**, right-click the desktop and select **Open Terminal** or press the terminal icon in the taskbar

> 🔐 **Tip:** It is good practice to change the default password after your first login:
> ```bash
> passwd
> ```

---

## 5. Linux Terminal Commands

The table below covers the most commonly used Linux commands you will encounter throughout this course.

| Command | Description |
|---------|-------------|
| `adduser` | Add a new user |
| `arch` | Print machine architecture |
| `awk` | Find and replace text within file(s) |
| `bc` | Arbitrary precision calculator language |
| `cal` | Display a calendar |
| `cat` | Concatenate files and print to standard output |
| `chdir` | Change working directory |
| `chgrp` | Change the group ownership of files |
| `chkconfig` | Maintain the `/etc/rc[0-6].d` directory hierarchy |
| `chmod` | Change access permissions of files and directories |
| `chown` | Change user and group ownership of files |
| `chroot` | Change root directory |
| `cksum` | Print CRC checksum and byte counts |
| `clear` | Clear the terminal screen |
| `cmp` | Compare two files |
| `comm` | Compare two sorted files line by line |
| `cp` | Copy one or more files to another location |
| `cron` | Daemon to execute scheduled commands |
| `crontab` | Schedule a command to run at a later time |
| `csplit` | Split a file into context-determined pieces |
| `cut` | Divide a file into several parts |
| `date` | Display or change the date & time |
| `dc` | Desk calculator |
| `dd` | Data dump — convert and copy a file |
| `df` | Display free disk space |
| `diff` | Display differences between two files |
| `diff3` | Show differences among three files |
| `dir` | Briefly list directory contents |
| `dircolors` | Colour setup for `ls` |
| `dirname` | Convert a full pathname to just a path |
| `du` | Estimate file space usage |
| `echo` | Display a message on screen |
| `ed` | A line-oriented text editor |
| `egrep` | Search file(s) for lines matching an extended expression |
| `eject` | Eject CD-ROM |
| `env` | Display, set, or remove environment variables |
| `expand` | Convert tabs to spaces |
| `expr` | Evaluate expressions |
| `factor` | Print prime factors |
| `false` | Do nothing, unsuccessfully |
| `fdformat` | Low-level format a floppy disk |
| `fdisk` | Partition table manipulator for Linux |
| `fgrep` | Search file(s) for lines matching a fixed string |
| `find` | Search for files that meet a desired criteria |
| `fmt` | Reformat paragraph text |
| `fold` | Wrap text to fit a specified width |
| `format` | Format disks or tapes |
| `free` | Display memory usage |
| `fsck` | Filesystem consistency check and repair |
| `gawk` | Find and replace text within file(s) |
| `grep` | Search file(s) for lines matching a given pattern |
| `groups` | Print group names a user is in |
| `gzip` | Compress or decompress named file(s) |
| `head` | Output the first part of file(s) |
| `hostname` | Print or set system name |
| `id` | Print user and group IDs |
| `info` | Help info |
| `install` | Copy files and set attributes |
| `join` | Join lines on a common field |
| `kill` | Stop a process from running |
| `less` | Display output one screen at a time |
| `ln` | Make links between files |
| `locate` | Find files |
| `logname` | Print current login name |
| `lpc` | Line printer control program |
| `lpr` | Off-line print |
| `lprm` | Remove jobs from the print queue |
| `ls` | List information about file(s) |
| `man` | Help manual |
| `mkdir` | Create new folder(s) |
| `mkfifo` | Make FIFOs (named pipes) |
| `mknod` | Make block or character special files |
| `more` | Display output one screen at a time |
| `mount` | Mount a file system |
| `mv` | Move or rename files or directories |
| `nice` | Set the priority of a command or job |
| `nl` | Number lines and write files |
| `nohup` | Run a command immune to hangups |
| `passwd` | Modify a user password |
| `paste` | Merge lines of files |
| `pathchk` | Check file name portability |
| `pr` | Convert text files for printing |
| `printcap` | Printer capability database |
| `printenv` | Print environment variables |
| `printf` | Format and print data |
| `ps` | Process status |
| `pwd` | Print working directory |
| `quota` | Display disk usage and limits |
| `quotacheck` | Scan a file system for disk usage |
| `quotactl` | Set disk quotas |
| `ram` | RAM disk device |
| `rcp` | Copy files between two machines |
| `rm` | Remove files |
| `rmdir` | Remove folder(s) |
| `rpm` | Remote package manager |
| `rsync` | Remote file copy (synchronize file trees) |
| `screen` | Terminal window manager |
| `sdiff` | Merge two files interactively |
| `sed` | Stream editor |
| `select` | Accept keyboard input |
| `seq` | Print numeric sequences |
| `shutdown` | Shutdown or restart Linux |
| `sleep` | Delay for a specified time |
| `sort` | Sort text files |
| `split` | Split a file into fixed-size pieces |
| `su` | Substitute user identity |
| `sum` | Print a checksum for a file |
| `symlink` | Make a new name for a file |
| `sync` | Synchronize data on disk with memory |
| `tac` | Concatenate and write files in reverse |
| `tail` | Output the last part of files |
| `tar` | Tape archiver |
| `tee` | Redirect output to multiple files |
| `test` | Evaluate a conditional expression |
| `time` | Measure program resource use |
| `touch` | Change file timestamps |
| `top` | List processes running on the system |
| `traceroute` | Trace route to host |
| `tr` | Translate, squeeze, and/or delete characters |
| `true` | Do nothing, successfully |
| `tsort` | Topological sort |
| `tty` | Print filename of terminal on stdin |
| `umount` | Unmount a device |
| `uname` | Print system information |
| `unexpand` | Convert spaces to tabs |
| `uniq` | Uniquify files |
| `units` | Convert units from one scale to another |
| `unshar` | Unpack shell archive scripts |
| `useradd` | Create new user account |
| `usermod` | Modify user account |
| `users` | List users currently logged in |
| `uuencode` | Encode a binary file |
| `uudecode` | Decode a file created by uuencode |
| `vdir` | Verbosely list directory contents (`ls -l -b`) |
| `watch` | Execute/display a program periodically |
| `wc` | Print byte, word, and line counts |
| `whereis` | Report all known instances of a command |
| `which` | Locate a program file in the user's path |
| `who` | Print all usernames currently logged in |
| `whoami` | Print the current user ID and name |
| `xargs` | Execute utility, passing constructed argument list(s) |
| `yes` | Print a string until interrupted |

---

> 📖 Back to [Main README](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/README.md)
