# MagnetFlow-TorrentServer
MagnetFlow is a cross-platform torrenting infrastructure designed to streamline the downloading of torrent files via magnet links. Available on Windows, Mac, and Linux, the application aims to provide users with a seamless experience for managing their downloads while ensuring data privacy.


## Features
- **VPN Protection**: Keep yourself anonomus while downloading torrent content online.
- **Secure and Open Source Torrent Client**: open source torrent client so you have the power to know how your torrent files are being handled.

## Technologies
- **qmcgaw/gluetun** -> https://hub.docker.com/r/qmcgaw/gluetun
- **rqbit** -> https://github.com/ikatson/rqbit 


## Configuration Instructions (TEMP LOCATION)
https://github.com/qdm12/gluetun-wiki/tree/main/setup


## TEMP SETUP
While the bulk of development is underway. We will currently be using the rqbit server exactly. However, once we have a working prototype that is doing its main function we will split off from rqbit and fork rqbit to build a different communication solution. As one of the only means of communication is over HTTP. We prefer a gRPC appraoch. HTTP will be temperary while we continue to develop the application system!