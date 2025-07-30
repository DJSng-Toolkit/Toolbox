<!-- TODO add these to 1.19.2 enhancements

- [Better End Sky](https://github.com/PinkGoosik/better-end-sky)
- [Borderless Mining](https://github.com/comp500/BorderlessMining)
- [Custom LAN](https://modrinth.com/mod/custom-lan)
- [ExtraSounds](https://www.curseforge.com/minecraft/mc-mods/extrasounds)
- Guardian
- [MultiConnect](https://earthcomputer.net/)
- [No Chat Reports](https://www.curseforge.com/minecraft/mc-mods/no-chat-reports)
- [Screenshot to Clipboard](https://www.curseforge.com/minecraft/mc-mods/screenshot-to-clipboard-fabric)
- [Simple RPC](https://www.curseforge.com/minecraft/mc-mods/simple-discord-rpc)
- [Skin Swapper](https://www.curseforge.com/minecraft/mc-mods/skin-swapper)
- TitleChanger

-->

# Visual
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [3D\-Skin\-Layers](https://modrinth.com/mod/3dskinlayers) | Unknown | Render the player skin layer in 3D! | Client | Works with CustomSkinLoader after installing [this mod](https://modrinth.com/mod/skinlayers3d-customskinloader-bridge). No Lunar Client support. Understandable, they stole your mod. |
| [AppleSkin](https://modrinth.com/mod/appleskin) | None | Food/hunger-related HUD improvements | Client | Also installable on the server for saturation and exhaustion values (not necessary on singleplayer). Paper version is available, see the mod page. [VanillaTweaks](https://vanillatweaks.net/) has an alternative in the form of a Resource Pack, but is basic and does not show saturation or exhaustion, only the food's hunger values. |
| [Boosted Brightness](https://modrinth.com/mod/boosted-brightness) | Unknown | Set your brightness beyond default levels. | Client | May have incompatibility issues with some video option mods. |
| [Chat Heads](https://modrinth.com/mod/chat-heads) | Servers that use custom chat plugins [^1] | See who you're chatting with! | Client | Cracked servers work, but your skin may not update properly, especially if using SkinsRestorer. |
| [LambDynamicLights](https://modrinth.com/mod/lambdynamiclights) | Unknown | Adds dynamic lights to Minecraft as the most feature-complete and optimized dynamic lighting mod for Fabric. | Client | Implementation of OptiFine's "Dynamic Lights" feature. If you use shaders, use your shader pack's dedicated option instead. |
| [TipTapShow](https://modrinth.com/mod/tiptapshow) | Unknown | A mod for Fabric to show your keystrokes ingame | Client | Replacement for "Keystrokes" in most Client Launchers |
| [WaveyCapes](https://modrinth.com/mod/wavey-capes) | Unknown | The cape shouldn't be a static slab | Client | N/A |



# Quality of Life
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Client Tweaks](https://modrinth.com/mod/client-tweaks) | Unknown |  Various optional tweaks to improve Minecraft Quality of Life. | Client | A bunch of random building related tweaks. Users with media key keyboards might experience issues with their volume slider hiding their offhand item. |
| [Not So Essential](https://modrinth.com/mod/notsoessential) |  Unknown | Keeps only what's Essential  | Client | Good for killing telmetry and a lot of features in Essential for those who use it as a dependancy, but you should really still avoid Essential entirely. |
| [Zoomify](https://modrinth.com/mod/zoomify) | Unknown | A zoom mod with infinite customizability. | Client | Reimplementation of OptiFine's Zoom feature. You may also prefer [OK Zoomer](https://modrinth.com/mod/ok-zoomer) instead. |


# Integration 
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [No Chat Reports](https://modrinth.com/mod/no-chat-reports) | Unknown | Makes chat unreportable (where possible) | Both | If you cannot install NCR on the server, install [FreedomChat](https://modrinth.com/plugin/freedomchat) instead, which is plugin compatible. Can be installed on either or, but if only the client has it and the server is unconfigured, the game might still force chat reports. A necessary addition since Gaslight. **On this version, NCR will not let you join servers unless you agree to sign messages. That is your one and only warning that chat reports are enabled..** |
| [Notes](https://modrinth.com/mod/notes) |  Unknown | Fully functional, clientside, in-game notepad. | Client | N/A |
| [Recursive Resources](https://modrinth.com/mod/recursiveresources) | Unknown | Enhances the Resource Pack menu with folder support. | Client | Requires a folder.json file to add descriptions and custom icons. Read the mod page for more information. |
| [VTDownloader](https://modrinth.com/mod/vtdownloader) | Unknown | Pick and download Vanilla Tweaks resource packs directly from your Minecraft client! | Client | N/A | 
| [Xaero's Minimap](https://modrinth.com/mod/xaeros-minimap) | Unknown | Displays a map of the nearby world terrain, players, mobs, entities in the corner of your screen. | Client | If you plan to use on servers and you have OP/Teleport permissions, open Default Teleport Command and change it to `tp x y z`. Also has waypoints. Please change the default controls. |
| [Xaero's World Map](https://modrinth.com/mod/xaeros-world-map) |  Unknown | Adds a full screen world map which shows you what you have explored in the world.  | Client | N/A | 

# Vanilla+
(for transparency reasons, these mods cannot be required on both to count. must be one or the other only!!)
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Presence Footsteps](https://modrinth.com/mod/presence-footsteps) | Unknown | ..An Overly complicated Sound Mod... | Client | Some versions may require you to use a non-normal version of the Java JDK (i.e: JDK 17 when JDK 16 is the only supported version for some launchers). If you are using Prism, you may need to enable "Skip java compatibility checks". Do not do this unless you are sure you need to. |

# Required by other players
(but not required by server)

| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |

# Dangerous mods
These mods do things that either could get you banned from some servers, could harm the game or could do very harmful things.  
Beware!

| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |


[^1]: Servers that override how chat messages sent by players are formed may cause issues with Chat Heads and make them not render.