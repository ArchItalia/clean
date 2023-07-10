This Bash script checks for obsolete packages and dependencies on a system and removes them if found. It also calculates the total space taken up by cache, package cache, and trash from different directories and prompts the user to remove all files from cache and unused repositories. If the user agrees, it removes all files from the cache directory, trash folder, and clears the package cache using 'pacman -Scc' command. The script also displays the current total space taken up by these directories before and after cleanup.

![image](https://github.com/ArchItalia/clean/assets/117321045/73fade9a-c96e-4348-9328-a01d3bbc2b91)


- official site https://architalia.github.io/site/scripts/clean/
- archlinux.org: https://aur.archlinux.org/packages/clean

## install from AUR
* git clone https://aur.archlinux.org/clean.git
* cd clean
* makepkg -si

## install from GitHub
* git clone https://github.com/architalia/clean.git
* cd clean
* makepkg -si

<br>

`$ clean` easy command for arch linux



