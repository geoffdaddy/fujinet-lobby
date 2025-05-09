# fujinet-lobby
The canonical set of Lobby clients and Lobby server for the FujiNet Game System

This repo was created in October 2024 and combines both the Lobby Go server from the 'servers' repo and the client code from the 'fujinet-apps' repo. It is hoped that by combinging them into one common repo it will allow faster and easier code contributions for the FujiNet Game System.




# lobby

The FujiNet Game Lobby/Game board client.

The goal of the Lobby is to make it easy to find and play online games that span multiple platforms.

The FujiNet Game Lobby Client displays a real time list of online game servers.

##  Use
On startup, enter your name (on first run), then pick from a list of available online servers. The Lobby will download and mount and boot the correct client for that server, after storing the server details in an **AppKey**. 

The client will read the **AppKey**, connect to the server, and start the game.

## Lobby Server
Details about implementing a game server or client and working with the Lobby Server can be viewed at https://github.com/FujiNetWIFI/fujinet-lobby.



