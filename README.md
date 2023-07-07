# trarbg

A shell script for searching torrents on RARBG.

![example](example.gif)

## Requirements

 - [hgrep](https://github.com/TUVIMEN/hgrep)
 - xclip

## Installation
    install -m 755 trarbg /usr/bin

## Usage

Just type 'trarbg your search', choose what you want and the magnet link will be copied to your clipboard.

Search for the biggest linux isos

    trarbg -s size linux iso

Search for the smallest linux isos

    trarbg -r -s size -p 2 linux iso

Search for the most seeded linux isos on second page

    trarbg -s se -p 2 linux iso

Search different domain for linux isos and change delimiter to space

    trarbg -D ' ' -d 'http://otherdomain.to' 'linux iso'

Get some help

    trarbg -h
