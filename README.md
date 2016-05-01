# gpmdp [![Build Status](https://travis-ci.org/iandrewt/gpmdp-bash.svg?branch=master)](https://travis-ci.org/iandrewt/gpmdp-bash)

Get info about the current playing song in Google Play Music Desktop Player

I made this for use in [`neofetch`](https://github.com/dylanaraps/neofetch)

## Installation

### OS X

- Run `brew install iandrewt/tap/gpmdp-bash`

### Arch Linux

- Install [gpmdp-bash](https://aur.archlinux.org/packages/gpmdp-bash) from the AUR

### Others

Clone the repo and run `make install`

## Uninstallation

Uninstall with your package manager, otherwise run `make uninstall`

## Usage

    usage: gpmdp <option>

    info            Print info about now playing song
    title           Print current song title
    artist          Print current song artist
    album           Print current song album
    album_art       Print current song album art URL
    time_current    Print current song time in milliseconds
    time_total      Print total song time in milliseconds
    status          Print whether GPMDP is paused or playing
    current         Print now playing song in "artist - song" format
    help            Print this help message
 
