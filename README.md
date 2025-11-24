# [Parus](https://github.com/salvoton/parus)

[![AUR Version](https://img.shields.io/aur/version/parus?style=for-the-badge&logo=archlinux)](https://aur.archlinux.org/packages/parus)
[![AUR Votes](https://img.shields.io/aur/votes/parus?style=for-the-badge&logo=archlinux)](https://aur.archlinux.org/packages/parus)

## Description
A package search TUI for [Paru](https://github.com/Morganamilo/paru), powered by [Skim](https://github.com/skim-rs/skim).
It can install, upgrade, remove, and query packages.

[![asciicast](https://asciinema.org/a/wa7QiPqDWUalqB0mFrLeeBx5D.svg)](https://asciinema.org/a/wa7QiPqDWUalqB0mFrLeeBx5D)

## Usage
| Usage       | Action         |
|-------------|----------------|
| parus       | Default action |
| parus [opt] | Other options  |

The default action is to search for and install packages.<br>
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
* [Bash](https://www.gnu.org/software/bash/bash.html)

## Installation
**Note:**
Before using the Arch User Repository (AUR), make sure you understand how it works and the potential risks involved.

### AUR (via paru)
```sh
paru -S parus
```

## License
This project is licensed under the GNU General Public License v3.0 (GPL-3.0). See the LICENSE file in the project root for the full license text.