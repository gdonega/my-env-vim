# Copied from...
- [ThePrimeagen/init.lua](https://github.com/ThePrimeagen/init.lua) (I've change somethings)

# Necessary to install befor using it...
- [Neovim](https://neovim.io/)
- [packer.nvim](https://github.com/wbthomason/packer.nvim) 
- [python](https://www.python.org/downloads/) 
    - You need to change the path to python exe on the file **.\after\plugin\ultisnips.lua**

# Config this project in your pc
1. Clone this project
1. Cut and paste all files to **C:\Users\{user_folder}\AppData\Local\nvim**
1. Go to the file **.\after\plugin\ultisnips.lua** and change the path to python3 
1. Go to folder **.\lua\configs** 
    1. Open terminal
    1. execute: **nvim packer.lua**
    1. Open the vim's command mode 
    1. Execute: **:so**
    1. Open the vim's command mode (again)
    1. Execute **:PackerSync**

# Disclaimer
There are probably errors and problems in this enviroment... I'm still learning the vim's basics and configuring my dev enviroment :)