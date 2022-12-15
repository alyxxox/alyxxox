- I mostly make python scripts but also do some shell scripting and am trying to learn Powershell!

## Current Projects:

### *[discrypt](https://github.com/alyxxox/discrypt)*
An encrypted backend for Discord messenger.
Goals:
- Encrypt/decrypt messages seamlessly
- exchange keys between users outside of discord's servers

### *[alyx-system-utilities](https://github.com/7fours/alyx-system-utilities)*
Quality of life improvements for linux and windows systems. In essence, just a cli wrapper for a multitude of applications
- Alyx's shell wrapper (ash) WIP!
- - Python based shell for asu extensions such as apm
- - Not intended for, but can handle standard sh/ps1 calls as well
```
Usage: [--dir]
```
```
        Alyx's Shell [ash]
        
[user] :: [current_directory] --> _ 
```

- Alyx's Package Manager (apm)
```
        Universal Package Manager/upm     
        [written/maintained by Alyxx]
        
    !! might/should work with winget? !!

Usage: [-I] [-R] [-U] [-P] [-d]
       [--manager] [--sandbox] [--autoremove] [--debug]
       
ex. [upm -I firefox] Would install the firefox from our repository
ex. [upm -I firefox --manager snap] Would install the snap version of firefox

Options:
-I, --install        Installs specified package
-R, --remove         Removes specified package
-U, --update         Updates packages in background then upgrades available packages
-P, --purge          Remove package as well as all dependencies/unused related packages
-d, --details        Gives information on the specified package as well as the dependencies

Long commands only:
--no-confirm         Don't require confirmation for further permissions
--manager            If a specific package manager needs to be used, use this flag
--autoremove         Autoremove unused/unneeded packages from system

Dev tools:
--sandbox            sandbox and test package without installing to system [WIP]
--debug
```

## Future Projects:

- Develop my own coding/scriping language
- 

## My past projects:

### *[Tutorial / Instruction consolidation for ChromeOS' crostini container](https://github.com/7fours/crostini)*
- at this point, basically deprecated as the default Debian build with proper modifications is faster/leaner

### *[Auto Minecraft Server](https://github.com/7fours/auto-mcserver)*:
Auto generate a vanilla, paper, fabric, or a premade paper server with plugins preinstalled.

```
usage: generate.py [-h] [-a] [-g] [-v] [-p] [-f] [-c] [-l] [-pb] [-ap] [-vr VERSION]

options:
  -h, --help            show this help message and exit
  -a, --auto-start      auto-start minecraft server after generated
  -g, --gui             enable gui for auto-start (BY DEFAULT OFF, ONLY USE FLAG IF WANTED)
  -v, --vanilla         create vanilla mc server
  -p, --paper           create papermc server
  -f, --fabric          create fabric mc server
  -c, --custom          create premade custom server
  -l, --local           Local server
  -pb, --public         Public server
  -ap, --add-plugins    add custom plugins set without the whole server file
  -vr VERSION, --version VERSION
                        desired version. by default, set to newest available.
```
## Recommendations!
### *[winutil](https://github.com/7fours/winutil)* 
###### ***not my project and I doubt I will have much to add to it! I forked it simply to keep it on my profile***
- Has various packages along with essential tweaks to the Windows backend and update system
- open Powershell as administrator and use following command to start script:

```
iwr -useb https://windows.alxcore.org | iex
```
`iwr or InvokeWebRequest`: More commonly known as curl or wget

`-useb` or `-UseBasicParsing`: Just a general flag directing iwr how to interpret the incoming data

`windows.alxcore.org`: A redirect for the script i set up for easier remembering. (this will take you to a raw view of the script)

`| iex`: Telling powershell that this is an executable script that is to be ran.

*I highly discourage running random scripts from online, even from ppl you trust, without being able to go through and understand at least a small bit of what is happening so i thought this breakdown would be nice. I am literally only getting started in learning Powershell/ps1 language so im far from an expert but if anyone is weary i can try to run through it.*
