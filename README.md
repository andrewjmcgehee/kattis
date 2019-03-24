# Kattis
Problems I have solved, and cool things I have learned on open.kattis.com 

I will try to always push solutions/snippets with detailed comments. This repo is for learning purposes. Feel free to use my solutions, 
change them, steal them and rip them off as your own, whatever you like... as long as you learn from them!

## Conventions:
All kattis solutions are named by their problem id on kattis and are enclosed in a directory by that name. If they have sample inputs
or expected outputs those will be included in the directory. All files that are not enclosed in a directory are some kind of code
snippet which I find helpful or interesting.

NOTE: Ratings listed in solutions are tentative. They constantly change and update as new submissions are made.

# Installation of Katti Automation (Mac / Linux)

To install the Katti command line tool, simply clone or download this repo and do the following:

NOTE: Python 3 is required and "python3" must be linked.

**1. Login to Kattis and download or copy and paste your personal .kattisrc file from:**
```
https://icpc.kattis.com/download/kattisrc
```
**2. Move your .kattisrc to your home directory:**
```
$ mv .kattisrc $HOME
```
**3. Run the katti installer script:**
```
$ python3 installer.py
```

Please note that katti is installed to `/usr/local/opt/katti.py`, writes a shell script to `/usr/local/bin/katti`, and stores its config files
in `/usr/local/etc/katti`

## Zsh or Oh-My-Zsh Completions

If you would like zsh or oh-my-zsh to complete katti's options for you, replace step three with the command below.
Otherwise it is safe to discard the `_katti` file.

```
$ python3 installer.py --zsh
```
