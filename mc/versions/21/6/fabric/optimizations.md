# Essential
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Better Fps - Render Distance](https://www.curseforge.com/minecraft/mc-mods/better-fps-render-distance-fabric) | Async, Very Many Players | Better FPS Render Distance is a mod which adds a few performance improvements to increase fps. | someaddon | Client | Incompatible with Async, as Async is incompatible with this mod's dependancy (Cupboard). |
| [Cull Particles MultiLoader](https://modrinth.com/mod/cull-particles-multiloader) | Unknown | MultiLoader particle culling mod to improve performance | commander | Client | Fork of [a mod of a similar name](https://www.curseforge.com/minecraft/mc-mods/cull-particles-fabric)  |
| [Entity Culling](https://modrinth.com/mod/entityculling) | Unknown | Using async path-tracing to hide Block-/Entities that are not visible | tr7zw | Client | N/A |
| [FerriteCore](https://modrinth.com/mod/ferrite-core) | Unknown | Memory usage optimizations | malte0811 | Both | N/A |
| [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast) | Unknown | Speed up immediate mode rendering in Minecraft | RaphiMC | Client | Effect is most noticable on CPU bottleneck and old CPU setups, according to the author | 
| [Lithium](https://modrinth.com/mod/lithium) | Unknown | No-compromises game logic optimization mod. | CaffeineMC | Both | N/A |
| [Modernfix](https://modrinth.com/mod/modernfix) | None | All-in-one mod that improves performance, reduces memory usage, and fixes many bugs. | embeddedt | Both | 1.21.5+ builds can be obtained from Simply Optimized. |
| [Moonrise](https://modrinth.com/mod/moonrise-opt) | C2ME, ScalableLux, Async | Optimisation mod for the dedicated/integrated server. | spottedleaf | Server | Ports some of PaperMC's server patches. Also works on Singleplayer / LAN servers if the host has the mod. My testing with this mod has been pretty spotty before, YMMV. |
| [Nvidium](https://github.com/drouarb/nvidium) [^1] | VulkanMod, Non-Sodium rendering engines | Fast nvidia only rendering engine for sodium | cortex | Client | For GTX 16XX and RTX cards only. If the game crashes more often mid-game, remove this mod. |
| [Particle Core](https://modrinth.com/mod/particle-core) | Unknown | Particle culling, rendering optimizations, configurable particle-type-specific spawn reduction, and potion particle disabling. | fzzyhmstrs | Client | N/A |
| [Sodium](https://modrinth.com/mod/sodium) | VulkanMod | The fastest rendering optimization mod for Minecraft. | CaffeineMC | Client | N/A |

# Situational
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Async](https://modrinth.com/mod/async) | Moonrise, Cupboard | Async is a Fabric mod designed to improve the performance of entities by processing them in parallel threads. | AxalotLDev | Server | Based on MCMTFabric / JMT-MCMT. | 
| [AsyncParticles](https://modrinth.com/mod/asyncparticles) | OptiFine | Async particle tick/rendering | Harvey_Husky | Client | Disables some of Particle Core's optimizations when installed. |
| [Concurrent Chunk Management Engine](https://modrinth.com/mod/c2me-fabric) | ViaFabricPlus, Moonrise | Improve the chunk performance of Minecraft | ishland | Both | Essential if not using VFP. VFP developer often advises users to remove C2ME to fix bugs. |
| [Cull Leaves](https://modrinth.com/mod/cull-leaves) | None | Adds culling to leaf blocks, providing a huge performance boost over vanilla. | Motschen | Client | N/A |
| [Debugify](https://modrinth.com/mod/debugify) | Unknown | Fixes Minecraft bugs found on the bug tracker | isxander | Both | This is mainly a bugfix mod, but some mods such as ForgetMeChunk and Entity Collision FPS Fix are included in this mod, so it counts. |
| [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) | Unknown | Reduce resource usage while Minecraft is in the background | juliand665 | Client | Also applies to battery mode and idle mode. Overrides Vanilla's "AFK Mode" setting. |
| [GPU Tape](https://modrinth.com/mod/gputape) | Video Tape | Fix VRAM leaks. Based on VideoTape. | Mr. Toad | Client | Vulkan compatible fork of Video Tape available on more setups (older versions, Forge setups) |
| [Ixeris](https://modrinth.com/mod/ixeris) | Unknown | Off-thread event polling | decce6 | Client | Not very effective on idle | 
| [MoreCulling](https://modrinth.com/mod/moreculling) | Unknown | A mod that changes how multiple types of culling are handled in order to improve performance | FX | Client | N/A |
| [NoCollision](https://modrinth.com/datapack/no-collision) | Unknown | Removes collision from a few passive mobs to increase FPS and TPS! | sniffercraft34 | Unknown | Has a mod as an option, but description is about the datapack variant. More information needed. |
| [ScalableLux](https://modrinth.com/mod/scalablelux) | Moonrise | https://modrinth.com/mod/scalablelux | ishland | Both | Might not be as efficient as Starlight, as 1.20+ has most of Starlight's enhancements already added. |
| [ServerCore](https://modrinth.com/mod/servercore) | Unknown | A mod that aims to optimize the minecraft server | Wesley1808 | Server | Also works on Singleplayer / LAN servers if the host has the mod |
| [Sodium Extra](https://modrinth.com/mod/sodium-extra) | Unknown | A Sodium addon that adds features that shouldn't be in Sodium. | FlashyReese | Client | Implements a more expanded version of OptiFine's particle disabling and animation settings. Also adds the ability to disable toasts |

# Edge case
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [BadOptimizations](https://modrinth.com/mod/badoptimizations) | Unknown | Optimization mod that focuses on things other than rendering | thosea | Client | N/A |
| [Krypton](https://modrinth.com/mod/krypton) | Unknown | A mod to optimize the Minecraft networking stack | astei | Both | N/A |
| [Language Reload](https://modrinth.com/mod/language-reload) | Unknown | Reduces load times and adds fallbacks for languages | Jerozgen | Client | N/A
| [Noxesium](https://modrinth.com/mod/noxesium) | Unknown | Improves play experience on large multiplayer servers. | Noxcrew | Client | Mainly meant for use on MCC Island. Will be an unnecessary add for 90% of users. Also included on Lunar Client. |
| [sepals](https://modrinth.com/mod/sepals) | None | An extremely radical and experimental optimization for Minecraft server performances. | cao-awa | Server | N/A |
| [Substrate](https://modrinth.com/mod/substrate) | Unknown | Sodium add-on for optimization of the bottom (or top) layer of the world | VesMaybeVesper | Client | Fork of Bedrodium that culls more than just bedrock. |

# Possible Snake Oil
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [RenderScale](https://modrinth.com/mod/renderscale) | Iris + Distant Horizions [^2] | Allows you to change Minecraft's render resolution separately from the HUD elements | zolo101 | Client | May cause lower performance, I haven't tested. Will definitely make your game look bad. Fork of ResolutionControl++. |
| [ThreatenGL](https://modrinth.com/mod/threatengl) | Unknown | Threatens Minecraft to use modern versions of OpenGL | Richy-Z | Client | Just changes the OpenGL version from 3.2 to 4.6 (or 4.1 on Mac). Require a card from 2012 or later. |

# Snake Oil / Gimmick
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [FPS to the Trash](https://modrinth.com/mod/fps-to-the-trash) | VulkanMod | Throw away display updates your monitor can't process for more FPS | notahero04 | Client | Doesn't actually optimize the game, just tosses frames the monitor can't see. Enable VSync if you experience stutters and/or high GPU usage. |




[^1]: Original repo only goes up to 1.21.1 but you can get 1.21.2+ if you use [drouarb's fork](https://github.com/drouarb/nvidium).

[^2]: Using Iris and Distant Horizions at once seems to cause issues with RenderScale. See [this thread](https://github.com/Zolo101/RenderScale/issues/26) for potential fixes.
