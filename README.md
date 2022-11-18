# ubuntu-in-termux

[![DISCORD](https://img.shields.io/badge/Chat-On%20Discord-734BD7.svg?style=for-the-badge)](https://discord.gg/Xaqkdeh)

## What is  This About?

This is a script that allows you to install Ubuntu in your termux application without having to root your android  device

## Updates

**• Updated to ubuntu 22.04**

## Important

 If you have to use ubuntu in termux with a x86/i\*86 architecture or prefer ubuntu 19.10 or other minimal options, you can use this branch from MFDGaming  -> https://github.com/MFDGaming/ubuntu-in-termux/tree/ubuntu19.10**

 If you get an error message that says "Fatal Kernel too old" you have to uncomment the line that reads "command+=" -k 4.14.81"" (remove the # that is located in front of the line) in the "startubuntu.sh" file**

### Installation steps for the MFDGaning option

1. Update termux: `apt-get update && apt-get upgrade -y`
2. Install wget: `apt-get install wget -y`
3. Install proot: `apt-get install proot -y`
4. Install git: `apt-get install git -y`
5. Go to HOME folder: `cd ~`
6. Download script: `git clone https://github.com/MFDGaming/ubuntu-in-termux.git`
7. Go to script folder: `cd ubuntu-in-termux`
8. Give execution permission: `chmod +x ubuntu.sh`
9. Run the script: `./ubuntu.sh -y`
10. Now just start ubuntu: `./startubuntu.sh`

### Ubuntu 22.04  magic installation  command;

```
echo "deb https://termux.mentality.rip/termux-main stable main" > $PREFIX/etc/apt/sources.list && cat $PREFIX/etc/apt/sources.list && pkg update -y && pkg install git wget curl proot tar -y && git clone https://github.com/ugoMusk/Onelr.git && cd Onelr && ./onelr && cd && git clone https://github.com/ugoMusk/ubuntu-in-termux.git && cd ubuntu-in-termux && chmod +x ubuntu.sh && ./ubuntu.sh && cat unminimize >> startubuntu.sh && ./startubuntu.sh && apt install man-db manpages -y

```
