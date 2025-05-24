# [Parus](https://github.com/salvoton/parus)
A package search TUI for [Paru](https://github.com/Morganamilo/paru), powered by [Skim](https://github.com/skim-rs/skim).
It can install, upgrade, remove, and query packages.

[![asciicast](https://asciinema.org/a/720673.svg)](https://asciinema.org/a/720673)

## Usage
| Usage       | Action         |
|-------------|----------------|
| parus       | Default action |
| parus [opt] | Other options  |

The default action is to search for and install packages..<br>
A '*' indicates that the package is already installed.

### Options:
| Option   | Description                          |
|----------|--------------------------------------|
| h        | Print help message                   |
| p        | Print only; do not install           |
| u        | Upgrade upgradable packages          |
| r        | Remove installed packages            |
| R        | Remove explicitly installed packages |
| q        | Show installed packages              |
| Q        | Show explicitly installed packages   |

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
