# DiskSync - Backup your Hifidelio

This repository contains the final version of my backup software for the Hifidelio MP3 player. I keep it for historical reasons.

## Introduction

The program *DiskSync* was written by me to backup the internal disk of my Hifidelio to an external USB drive. It has been designed to create a complete backup of the music data and allow a restore of not only the audio tracks but also the play- and searchlists and the rest of the preferences.

![alt DiskSync welcome screen](https://github.com/smoeding/disksync/Welcome.jpg/gh-pages "DiskSync welcome screen")

## Key Features

* The audio tracks are written as single files to disk and can be accessed on any computer capable of reading EXT3 filesystems.
* Incremental backups save only changes and therefore improve the time needed for subsequent backups.
* The program can be operated from the front panel controls. No need to use a computer or network and type commands after the installation is done.
* Messages on screen are available in german and english depending on the selected locale of the device.
* An indicator in the display shows the progress of the backup or restore operation.
* Details of the backup and restore are written to a logfile into the import folder and can be accessed over the network.
* No changes of the installed software on the Hifidelio are necessary.

The program has been developed and tested with the Hifidelio software versons *2.3.18 PRO* and *2.3.21 PRO*.
