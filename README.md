# Jellyfin

Jellyfin is a media server that can be used to stream self-hosted movies and shows. It can also be used to display other media, such as music videos, music, books, and photos. It is an open-source equivalent to Plex and Emby, but could also be a replacement for streaming services, such as Netflix and Hulu.

## Setup

- This setup utilizes the [LinuxServer.io image](https://hub.docker.com/r/linuxserver/jellyfin).
- Media stored on a NAS can be accessed by mounting the network shares to `./movies/`, `./tvshows/`, and `./music-videos/` directories. 
