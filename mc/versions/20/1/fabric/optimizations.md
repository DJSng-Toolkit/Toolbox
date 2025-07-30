# Essential
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Entity Culling](https://modrinth.com/mod/entityculling) | Unknown | Using async path-tracing to hide Block-/Entities that are not visible | Client | N/A |
| [Embeddium](https://modrinth.com/mod/embeddium) | Unknown | A powerful, mod-friendly, FOSS client performance mod | Client | Intended for mod compatibility. It's forked from an older version of Sodium, so you shouldn't use this unless you need that extra mod compatibility. |
| [FerriteCore](https://modrinth.com/mod/uXXizFIs) | Unknown | Memory usage optimizations | Both | N/A |
| [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast) | Unknown | Speed up immediate mode rendering in Minecraft | Client | Effect is most noticable on CPU bottleneck and old CPU setups, according to the author | 
| [LazyDFU](https://modrinth.com/mod/lazydfu) | None | Makes the game boot faster by deferring non-essential initialization | Both | Patched on servers on 1.19.4+. Patched on clients starting with 1.21.x. |
| [Lithium](https://modrinth.com/mod/lithium) | Unknown | No-compromises game logic optimization mod. | Both | N/A |
| [Modernfix](https://modrinth.com/mod/nmDcB62a) | None | All-in-one mod that improves performance, reduces memory usage, and fixes many bugs. | Both | 1.21.5+ builds can be obtained from Simply Optimized. |
| [Nvidium](https://github.com/drouarb/nvidium) | VulkanMod, Non-Sodium rendering engines | Fast nvidia only rendering engine for sodium | Client | For GTX 16XX and RTX cards only. If the game crashes more often mid-game, remove this mod. |
| [Sodium](https://modrinth.com/mod/sodium) | Unknown | The fastest rendering optimization mod for Minecraft. | Client | You should also install [Indium](https://modrinth.com/mod/indium) for better compatibiity. |

# Situational
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [Cull Leaves](https://modrinth.com/mod/cull-leaves) | None | Adds culling to leaf blocks, providing a huge performance boost over vanilla. | Client | N/A |
| [Cull Less Leaves](https://modrinth.com/mod/qthuEuVy) | Unknown | Cull leaves while looking hot! | Client | Alternative for Cull Leaves that lets you keep more of the inside leaves |
| [Debugify](https://modrinth.com/mod/debugify) | Unknown | Fixes Minecraft bugs found on the bug tracker | Both | This is mainly a bugfix mod, but some mods such as ForgetMeChunk and Entity Collision FPS Fix are included in this mod, so it counts. |
| [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) | Unknown | Reduce resource usage while Minecraft is in the background | Client | Also applies to battery mode and idle mode. Overrides Vanilla's "AFK Mode" setting. |
| [GPU Tape](https://modrinth.com/mod/gputape) | Video Tape | Fix VRAM leaks. Based on VideoTape. | Client | Vulkan compatible fork of Video Tape available on more setups (older versions, Forge setups). Might conflict with Memory Leak Fix. |
| [Memory Leak Fix](https://modrinth.com/mod/memoryleakfix) | Unknown | A mod that fixes random memory leaks for both the client and server | Both | Might cause mod conflicts. |
| [Noisium](https://modrinth.com/mod/KuNKN7d2) | Performant | Optimises worldgen performance for a better gameplay experience. | Server | Also works on Singleplayer / LAN servers if the host has the mod | 

# Edge case
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |
| [BadOptimizations](https://modrinth.com/mod/badoptimizations) | Unknown | Optimization mod that focuses on things other than rendering | Client | N/A |
| [Krypton](https://modrinth.com/mod/krypton) | Unknown | A mod to optimize the Minecraft networking stack | Both | N/A |
| [NoShade](https://modrinth.com/mod/no-shade) | Unknown | Removes all shadows on text. | Client | Might be redundant. The biggest effect will be on text heavy scenarios. Does very little for performance. |
| [Starlight](https://modrinth.com/mod/starlight) | Unknown | Rewrites the light engine to fix lighting performance and lighting errors | Both | Not necessary on 1.20.x anymore. Only use it if you feel you must. |

# Possible Snake Oil
| Name | Incompatibilities | Description | Client / Server | Notes |
| --- | :---: | :---: | :---: | :---: |

<!-- TODO: 1.20.1 --  add from this list
| [DashLoader](https://modrinth.com/mod/dashloader) | Unknown | 
| [FastAnim](https://modrinth.com/mod/fastanim) | Unknown | 
| [Faster Random](https://modrinth.com/mod/RfFxanNh)  | Unknown | 
| [Memory Leak Fix](https://github.com/fxmorin/memoryleakfix)
 -->