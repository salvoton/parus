# [Parus](https://github.com/salvoton/parus)
A package search TUI for [Paru](https://github.com/Morganamilo/paru) using [Skim](https://github.com/skim-rs/skim).
It can be used to install, upgrade, query and remove packages.

## Usage
| Usage       | Action         |
|-------------|----------------|
| parus       | Default action |
| parus [opt] | Other options  |

The default action is to search and install packages.<br>
'*' means that the package is already installed.

### Options:
| Option   | Description                          |
|----------|--------------------------------------|
| h        | Print help message                   |
| p        | Print only; do not install           |
| u        | Upgrade upgradable packages          |
| q        | Show installed packages              |
| Q        | Show explicitly installed packages   |
| r        | Remove installed packages            |
| R        | Remove explicitly installed packages |

### Multiple Selection:
| Bind     | Action            |
|----------|-------------------|
| Tab      | Select / Deselect |
| Ctrl + i | Select / Deselect |
## Requirements
* [Paru](https://github.com/Morganamilo/paru)
* [Skim](https://github.com/skim-rs/skim)
* Bash

## Installation
### AUR (via paru)
```sh
paru -S parus
```
### Direct Download
```sh
sudo curl -o /usr/bin/parus https://raw.githubusercontent.com/salvoton/parus/master/parus
sudo chmod +x /usr/bin/parus
# To uninstall, remove '/usr/bin/parus'
```
