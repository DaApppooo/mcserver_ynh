
# Official Vanilla Minecraft Server

The official vanilla Minecraft server.

## Notes on default setup

rcon (to interact with the server outside of the stdin shell interface) is on
by default. You technically can spawn multiple instances of this server, but
make sure the ports are different. Also, you need to open the ports yourself,
both on your ISP and on your yunohost configuration. By default, the ports are
25565 for the minecraft server, and 25575 for the rcon server.

## Plan for this app

- Implementation of a dynamic interface for the rcon server.
