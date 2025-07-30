# Essential
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Model Gap Fix](https://modrinth.com/mod/modelfix) | Unknown | Fixes gaps in Block Models and Item Models | Client | N/A |

# Situational
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [XXLPackets](https://modrinth.com/mod/SeCuopwJ) | Unknown |  XXL Packets is a fork of XL Packets which raises the packet size limit from 2MB to the Java Integer limit | Both | Same thing as PacketFixer's "Packet too big" fix. I'm not sure if they conflict. |
| [XLPackets](https://www.curseforge.com/minecraft/mc-mods/xl-packets-fabric) | Unknown | Fixes https://bugs.mojang.com/browse/MC-185901 by raising the packet size limit from 2MB to 2GB, so that servers with large datapacks, packets, etc don't kick the client. | Client | Original version of XLPackets. You should use XXLPackets instead. | 