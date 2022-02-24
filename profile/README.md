# Olympa
Olympa was a multi-game Minecraft server. We were about 25 volunteers, including 5 developers.

We proposed mainly 4 types of games :
- ZTA (GTA Minecraft revisited)
- Creative (Free construction, with command blocks, redstone, mobs...)
- PvP-Kit (Fight between players with different Minecraft objects)
- Warfare (FPS in Minecraft, with 3D models implemented in Minecraft)

## Operation
To add content to the Minecraft game, we used an API called Spigot that allows us to interact with the Minecraft environment.
We had several Minecraft servers linked together to offer several types of content to our players.
Each Minecraft server contained the OlympaCore (which itself contains OlympaAPI) and a plugin related to the use of this server. For example, for the management of our lobbies, there was OlympaCore and OlympaHub on it.
We used the PaperSpigot (fork of Spigot) api on the development side, and its fork Purpur in production. To link Minecraft servers together, we used WaterFall, a fork of Bungeecord.
Our Minecraft plugins are developed in Java 17 (Minecraft was coded in Java) and built with Gradle.
We also created a bot discord to manage our community but to have internal tools that link our Minecraft server and our Discord.
Finally, we have created bash scripts to manage our production server.
The communication between the different applications was done with Redis. We used MariaDB as a DBMS.

Our servers and our website were hosted at OVH, on a powerful dedicated machine.

## Notes
~~The server is now closed and here are some archived repos. All repo are licensed under the GNU GPLv3.~~
**We were originally on GitLab. We chose to archive our repos on GitHub. The transfer and the writing of the README is in progress ...**
