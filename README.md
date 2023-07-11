`$ clean` easy command for arch linux

🇮🇹 Clean utilizza alla base il comando pacman per gestire la pulizia e la manutenzione del sistema. Questo pacchetto in un semplice script bash verifica la presenza di pacchetti orfani e di dipendenze inutilizzate, grazie al flag -n non elimina dipendenze che sono in uso da altri pacchetti. Clean si occupa anche di rimuovere tutta la cache dei pacchetti, tutta la cache dell'utente comprensiva della cache di yay e di file spazzatura del cestino. e' possibile vedere lo spazio occupato da questi file e lo spazio totale che verra' eliminato. Clean e' un idea per raccogliere tutti i comandi che servirebbero' per eseguire queste azioni in una semplice parola, un comando chiaro da ricordare anche per i meno esperti. Questo progetto e' realizzato dalla comunity italiana Architalia Linux*. Clean e' disponibile su aur.archlinux.org

🇬🇧 Clean uses the pacman command to manage system cleaning and maintenance. This package, in a simple bash script, checks for the presence of orphan packages and unused dependencies. Furthermore, with the -n flag, it doesn't  dependencies that are still used by other packages. Clean also removes all package caches, user caches (including yay cache) and trash files. The amount of space taken up by these files and the total amount of space that will be freed up can be viewed. Clean is an idea to collect all the commands needed to perform these actions in a simple word, a clear command to remember even for the less experienced. This project was created by the Italian community Architalia Linux*. Clean is available on aur.archlinux.org.

![image](https://github.com/ArchItalia/site/assets/117321045/9cbf24c3-54e6-421b-a756-baab1e0bb90f)


## install from AUR
* git clone https://aur.archlinux.org/clean.git
* cd clean
* makepkg -si

## install from GitHub
* git clone https://github.com/architalia/clean.git
* cd clean
* makepkg -si

<br>





