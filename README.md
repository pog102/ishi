# ishi - a simple anime downloader for nyaa.si
## Installing Pre-requisites
### Arch Linux
sudo pacman -S transmission-daemon
### Debian & Ubuntu
sudo apt install transmission-daemon
### Fedora
sudo dnf install transmission-daemon
## Features
- Locally stores progress
- Download using transmission
## Quickstart
### Usage
in the file, change the folder directory and the download directoty to your liking
and add the anime entries to `$HOME/<path>/subscriptions`
for example
```
Urusei Yatsura (2022)#12
Chainsaw Man#12
Mob Psycho 100 III#24
BLEACH Sennen Kessen-hen#24
Akiba Meido Sensou#12
```
add the total of epsides for each entry, doing so will remove the entry if the episode treshold is reach.
## TODO
- Check the anime episode total from a database
