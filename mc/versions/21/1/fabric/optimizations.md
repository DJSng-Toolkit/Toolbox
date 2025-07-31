# Essential
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Better Fps - Render Distance](https://www.curseforge.com/minecraft/mc-mods/better-fps-render-distance-fabric) | Async, Very Many Players | Better FPS Render Distance is a mod which adds a few performance improvements to increase fps. | Client | Incompatible with Async, as Async is incompatible with this mod's dependancy (Cupboard). |
| [Cull Particles MultiLoader](https://modrinth.com/mod/cull-particles-multiloader) | Unknown | MultiLoader particle culling mod to improve performance | Client | Fork of [a mod of a similar name](https://www.curseforge.com/minecraft/mc-mods/cull-particles-fabric)  |
| [Entity Culling](https://modrinth.com/mod/entityculling) | Unknown | Using async path-tracing to hide Block-/Entities that are not visible | Client | N/A |
| [FerriteCore](https://modrinth.com/mod/ferrite-core) | Unknown | Memory usage optimizations | Both | N/A |
| [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast) | Unknown | Speed up immediate mode rendering in Minecraft | Client | Effect is most noticable on CPU bottleneck and old CPU setups, according to the author | 
| [Lithium](https://modrinth.com/mod/lithium) | Unknown | No-compromises game logic optimization mod. | Both | N/A |
| [Modernfix](https://modrinth.com/mod/modernfix) | None | All-in-one mod that improves performance, reduces memory usage, and fixes many bugs. | Both | 1.21.5+ builds can be obtained from Simply Optimized. |
| [Moonrise](https://modrinth.com/mod/moonrise-opt) | C2ME, ScalableLux, Async | Optimisation mod for the dedicated/integrated server. | Server | Ports some of PaperMC's server patches. Also works on Singleplayer / LAN servers if the host has the mod. My testing with this mod has been pretty spotty before, YMMV. |
| [Nvidium](https://github.com/drouarb/nvidium) [^1] | VulkanMod, Non-Sodium rendering engines | Fast nvidia only rendering engine for sodium | Client | For GTX 16XX and RTX cards only. If the game crashes more often mid-game, remove this mod. |
| [Particle Core](https://modrinth.com/mod/particle-core) | Unknown | Particle culling, rendering optimizations, configurable particle-type-specific spawn reduction, and potion particle disabling. | Client | N/A |
| [Sodium](https://modrinth.com/mod/sodium) | VulkanMod | The fastest rendering optimization mod for Minecraft. | Client | N/A |

# Situational
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Async](https://modrinth.com/mod/async) | Moonrise, Cupboard | Async is a Fabric mod designed to improve the performance of entities by processing them in parallel threads. | Server | Based on MCMTFabric / JMT-MCMT. | 
| [AsyncParticles](https://modrinth.com/mod/asyncparticles) | OptiFine | Async particle tick/rendering | Client | Disables some of Particle Core's optimizations when installed. |
| [BetterBeds](https://modrinth.com/mod/better-beds) | None | Changes the renderer of the bed to use json models instead of a block entity renderer! | Client | Incompatible with Bedspreads. |
| [Concurrent Chunk Management Engine](https://modrinth.com/mod/c2me-fabric) | ViaFabricPlus, Moonrise | Improve the chunk performance of Minecraft | Both | Essential if not using VFP. VFP developer often advises users to remove C2ME to fix bugs. |
| [Cull Leaves](https://modrinth.com/mod/cull-leaves) | None | Adds culling to leaf blocks, providing a huge performance boost over vanilla. | Client | N/A |
| [Cull Less Leaves](https://modrinth.com/mod/qthuEuVy) | Unknown | Cull leaves while looking hot! | Client | Alternative for Cull Leaves that lets you keep more of the inside leaves |
| [Debugify](https://modrinth.com/mod/debugify) | Unknown | Fixes Minecraft bugs found on the bug tracker | Both | This is mainly a bugfix mod, but some mods such as ForgetMeChunk and Entity Collision FPS Fix are included in this mod, so it counts. |
| [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) | Unknown | Reduce resource usage while Minecraft is in the background | Client | Also applies to battery mode and idle mode. Overrides Vanilla's "AFK Mode" setting. |
| [GPU Tape](https://modrinth.com/mod/gputape) | Video Tape | Fix VRAM leaks. Based on VideoTape. | Client | Vulkan compatible fork of Video Tape available on more setups (older versions, Forge setups) |
| [MoreCulling](https://modrinth.com/mod/moreculling) | Unknown | A mod that changes how multiple types of culling are handled in order to improve performance | Client | N/A |
| [Noisium](https://modrinth.com/mod/noisium) | Performant | Optimises worldgen performance for a better gameplay experience. | Server | Also works on Singleplayer / LAN servers if the host has the mod | 
| [Palladium](https://modrinth.com/mod/mpalladium) | Unknown | Another optimizing mod, provides deduplication, improved memory control, shader/chunk/nbt optimizations and enchanced mob AI. | Client | Modrinth exclusive. |
| [ScalableLux](https://modrinth.com/mod/scalablelux) | Moonrise | A Fabric mod based on Starlight that improves the performance of light updates in Minecraft. | Both | Might not be as efficient as Starlight, as 1.20+ has most of Starlight's enhancements already added. |
| [ServerCore](https://modrinth.com/mod/servercore) | Unknown | A mod that aims to optimize the minecraft server | Server | Also works on Singleplayer / LAN servers if the host has the mod |

# Edge case
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [BadOptimizations](https://modrinth.com/mod/badoptimizations) | Unknown | Optimization mod that focuses on things other than rendering | Client | N/A |
| [Krypton](https://modrinth.com/mod/krypton) | Unknown | A mod to optimize the Minecraft networking stack | Both | N/A |
| [Language Reload](https://modrinth.com/mod/language-reload) | Unknown | Reduces load times and adds fallbacks for languages | Client | N/A
| [Sodium Extras](https://modrinth.com/mod/sodium-extras) | stfu | An add-on mod for Sodium that adds new features and customization. | Client | Has very, *very* small optimizations. Causes issues with stfu. |
| [Substrate](https://modrinth.com/mod/substrate) | Unknown | Sodium add-on for optimization of the bottom (or top) layer of the world | Client | Fork of Bedrodium that culls more than just bedrock. |
| [Super Fast Math](https://modrinth.com/mod/super-fast-math) | OptiFine | A lightweight fabric mod that changes the sin and cos for better math. | Client | Similar to OptiFine's "Fast Math" option. |
| [ThreadTweak](https://modrinth.com/mod/threadtweak) | Unknown | Improve and tweak Minecraft thread scheduling | Client | Fork of Smooth Boot |
| [ThreatenGL](https://modrinth.com/mod/threatengl) | Unknown | Threatens Minecraft to use modern versions of OpenGL | Client | Just changes the OpenGL version from 3.2 to 4.6 (or 4.1 on Mac). YMMV. Require a card from 2012 or later. |
| [TT20](https://modrinth.com/mod/tt20) | Unknown | TT20 helps reduce lag by optimizing how ticks work when the server's TPS is low. | Server | Doesn't work properly on Singleplayer. Seemingly meant for servers whose TPS might go low every once and a while. |

# Possible Snake Oil
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Reflex AntiLag](https://modrinth.com/mod/reflex-antilag) | Unknown | Implementing Nvidia reflex in Minecraft to reduce latency | Both | Requires a GTX 9XX or later. Very lightly tested, with no benchmarks. Use with caution. |
| [RenderScale](https://modrinth.com/mod/renderscale) | Iris + Distant Horizions [^2] | Allows you to change Minecraft's render resolution separately from the HUD elements | Client | May cause lower performance, I haven't tested. Will definitely make your game look bad. Fork of ResolutionControl++. |




[^1]: Original repo only goes up to 1.21.1 but you can get 1.21.2+ if you use [drouarb's fork](https://github.com/drouarb/nvidium).

[^2]: Using Iris and Distant Horizions at once seems to cause issues with RenderScale. See [this thread](https://github.com/Zolo101/RenderScale/issues/26) for potential fixes.
