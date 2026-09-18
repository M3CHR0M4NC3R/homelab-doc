# Witness me.

## Hardware
As it stands, this setup is a single machine until I run out of hard drive space.
- Skylake Dell Optiplex fitted with an nvme boot drive, and a HDD for mass storage
- 2.5Gb switch for wired connnections

## Software
Almost all the services on this machine run on separate users with groups according to what they need access to to function. The OS of choice is Debian just for stability, I never need cutting-edge updates, and almost everything has a Debian tutorial.
Server sits in a corner and all access is handled through SSH with keys instead of passwords.
    - Syncthing (repositories, wallpapers, obsidian vault, digital books)
    - Anki
    - SMB Share (mass storage, music)
    - Jellyfin (streaming locally-stored shows and movies to intranet)
    - Immich (photos storage from phones and computers)
    - PiHole (local DNS server and tracker blocker)
    - TubeArchivist (locally backup youtube channels or videos, streams from Jellyfin)
    - CraftyController (one-click Minecraft server hosting)
    - Tailscale (access server functions from outside home network)

## TODO
All these services are still accessed with port numbers, I'd like to get nginx working again to have nice URL names. Additionally, https is off for all web interfaces for a related reason. After https works, I will be hosting my own password manager.
