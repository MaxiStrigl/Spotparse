# Spotparse
A small utility programm written in python which converts the xml output of spotbugs in a readable format and prints it the command line


## Installation
- Clone the repository 
- Make the script execuable 
```bash
chmod -x /path/to/the/script
```

To make the script accessible from anywhere, you need to add the script's directory to PATH.
You can do this by adding this line in your .bashrc or .zshrc.

```bash
export PATH=$PATH:/path/to/the/script
```

After doing that you need to reload your config. You can do this by simply closing and reopening your terminal or by running nohup.outnohup.out

```bash
source ~/.bashrc # or source ~/.zshrc
```

Now you should be able to use the command

```bash
spotparse build/spotbugs-report.xml
```
