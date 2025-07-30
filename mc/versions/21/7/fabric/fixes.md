# Essential
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Debugify](https://modrinth.com/mod/debugify) | Unknown | Fixes Minecraft bugs found on the bug tracker | Both | Also handles some performance optimizations on some versions |
| [Model Gap Fix](https://modrinth.com/mod/QdG47OkI) | Unknown | Fixes gaps in Block Models and Item Models | Client | N/A |
| [Nether Portal Fix](https://modrinth.com/mod/netherportalfix) | None | Ensures correct destinations when travelling back and forth through Nether Portals in Multiplayer. | Server | Also works for the integrated server (Singleplayer / LAN) |
| [Not Enough Crashes](https://modrinth.com/mod/notenoughcrashes) | Unknown | Not Enough crashes is a Minecraft mod that improves crashes in Minecraft. | Both | Might cause more crashes in very specific scenarios, I don't remember. Should be safe to install for all setups. |
| [Title Fixer](https://modrinth.com/mod/8zYE8DiW) | None | Simple client side mod that makes titles displayed on-screen always fit inside the screen space. | Client | N/A |

# Situational
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [PacketFixer](https://modrinth.com/mod/c7m1mi73) | Unknown |  A simple mod to fix various problems with packets and nbt. | Both | Mainly about packet issues with byte sizes. i.e: Packet Too Big |
[XXLPackets](https://modrinth.com/mod/SeCuopwJ) | Unknown |  XXL Packets is a fork of XL Packets which raises the packet size limit from 2MB to the Java Integer limit | Both | Same thing as PacketFixer's "Packet too big" fix. I'm not sure if they conflict. |

# Edge Case
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Disconnect Packet Fix](https://modrinth.com/mod/rd9rKuJT) | Unknown | Works around the MC-271325 bug on Fabric and NeoForge servers (fixes "error sending packet clientbound/minecraft:disconnect") | Server | N/A |
| [Language Reload](https://modrinth.com/mod/uLbm7CG6) | Unknown |  Reduces load times and adds fallbacks for languages | Client | *Very* strong edge case, just makes language changes faster. |
| [NoTextureRotations](https://modrinth.com/mod/h4ktIYQ8) | Unknown |  Prevent Block Texture Rotations | Client | Intended for players on SMPs where PvP is allowed without consent and/or rampant. Very situational mod that prevents coordinate guessing exploits that affect all versions. For a normal user this might not be big, but for anybody who plays on servers where anything could come for you and overanalyze your screenshots, this mod might be important to reduce chances of screenshotss being used to find your base. Not at 0, of course. |
| [ResourcePackCached](https://modrinth.com/mod/d4phKsx2) | Unknown |  Keeps server resource packs loaded, so they don't need to be reloaded when you rejoin. | Client | N/A |
| [Sodium Shadowy Path Blocks](https://modrinth.com/mod/EIa1eiMm) | Unknown |  Reintroduces vanilla-like smooth lighting to non-full blocks (e.g. dirt paths and how they have dark shading when directly next to a full block) when using Sodium.  | Client | N/A |
| [XaeroPlus](https://modrinth.com/mod/EnPUzSTg) | Unknown |  XaeroPlus is a client-side Minecraft mod that depends on and modifies the Xaero's WorldMap and Minimap mods with extra features and performance improvements - particularly for use on anarchy servers like 2b2t. | Client | Main gimmick is a FPS limiter, but also has tools mainly for Anarchy players. Xaero officially says not to use this because it causes crashes and bugs, and is affiliated with a griefing group, but I don't really care. |
| [XaeroZoomout](https://modrinth.com/mod/T6oqPfxF) |  Unknown |  Reduces the minimum zoom of Xaero's World Map from 0.0625x to 0.0025x | Client | May cause performance issues because it loads more of the world map when you zoom out. Lol. |