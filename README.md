# Gui for sqlmap
# SQLmap Command Builder

[![Python 3.x](https://img.shields.io/badge/python-3.x-yellow.svg)](https://www.python.org/) [![License](https://img.shields.io/badge/license-GPLv2-red.svg)](https://github.com/omlinky/sqm/blob/main/LICENSE)

This is simple GUI for sqlmap based on old Chinese version of SQLmap Command Builder.

## Supported OS:

- Windows
- Kali Linux by default XFCE (qterminal only)
- macOS users go [here](https://github.com/omlinky/sqm_macos)


## Requirements:

- Python 3
- Qterminal on any Linux OS

## How to run on Windows:

- [Install Python 3](https://www.python.org)
- Verify you python 3 instalation:
```sh
python3 --version
```
- [Install GIT](https://gitforwindows.org/)
- [Install sqlmap](https://github.com/sqlmapproject/sqlmap)
```sh
git clone --depth 1 https://github.com/sqlmapproject/sqlmap.git sqlmap-dev
```
- Put all files of SQLmap Command Builder in sqlmap installation folder
- Run sqm.pyw like other Windows programs 

## How to run on Kali:

- Choose XFCE Desktop Environment during installation process instead of GNOME to run and use SQLmap Command Builder out of the box.

![Alt text](https://github.com/user-attachments/assets/491ffdb8-3ce6-43fe-b1fa-faced21c2b11)
- Check your python version
```sh
python3 --version
```
- Get the last sqlmap from Git repository
```sh
git clone --depth 1 https://github.com/sqlmapproject/sqlmap.git sqlmap-dev
```
- Move all files of SQLmap Command Builder in sqlmap folder.
- Go to your sqlmap folder
```sh
cd /home/kali/sqlmap-dev
```
- Run SQLmap Command Builder
```sh
cd /home/kali/sqlmap-dev
python3 sqm.pyw
```

## For other Linux users:
- Install Qterminal
```sh
sudo apt update
sudo apt install qterminal -y
```
- Test it:
```sh
qterminal
```
- Get the last sqlmap from Git repository
```sh
git clone --depth 1 https://github.com/sqlmapproject/sqlmap.git sqlmap-dev
```
- Move all files of SQLmap Command Builder in sqlmap folder
- Go to your sqlmap folder
```sh
cd /home/kali/sqlmap-dev
```
- Run SQLmap Command Builder
```sh
cd /home/kali/sqlmap-dev
python3 sqm.pyw
```

## Simple usage out of the box on Kali
- move sqm to /usr/bin/
```sh
cd /home/kali/sqlmap-dev
sudo mv sqm /usr/bin/
```
- Give necessary permissions
```sh
sudo chmod u+x /usr/bin/sqm
```
- in Terminal input command
```sh
sqm
```

All video instructions and updates announces you can find on my twitter 
```sh
@omlinky
