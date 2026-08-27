# 0xzgbot

Native tools for making physical things. CNC, metal casting, product photography, and the local AI stack that builds them.

Public source where it helps. Private while a product is still in the shop.

---

## Projects

### CNC

| | Platform | |
| --- | --- | --- |
| **[ShopPilot](https://github.com/0xzgbot/ShopPilot)** | macOS · SwiftUI | Profile, pocket, drill, V-carve, 3D rough/finish, photo lithophane, nesting. GRBL/FluidNC with a built-in simulator. Hold/Reset always on screen. |
| **[VectorPilot](https://github.com/0xzgbot/VectorPilot)** | Windows · C# / WPF | The Windows sibling of ShopPilot. Same document, same safety rules. 3D preview, posts, machine control. |

### Casting

| | |
| --- | --- |
| **SculptCast** | Instant-quote metal casting. Upload an STL, get a price per part in aluminum or bronze. *Private.* |
| **Casting simulator** | Sand molds, ceramic shell, multiple metals. STL to gating, fill, solidification, and defect flags. Public original: [`tmophoto/sand_casting_v2`](https://github.com/tmophoto/sand_casting_v2). |
| **Made From Fire** | A foundry making bronze topographic objects and a terrain record-weight configurator. *Private.* |

### Photography

**Photo Labeler** — multi-AI LLM/VLM pipeline for eyewear product photos. RAW in, dual-model consensus, product/color/lens with confidence, XMP sidecars for Capture One. macOS + Windows production. *Private.*

### Local AI and media

| | |
| --- | --- |
| **[Cinesmith](https://github.com/0xzgbot/forge-nps-v01)** | Fully local cinematic pipeline. An isolated Hermes instance (it does not touch yours) orchestrates a DGX Spark and dual RTX 3090s running multiple ComfyUI instances. Plan, render, audit, remember. |
| **[hermes-media-skill-pack](https://github.com/0xzgbot/hermes-media-skill-pack)** | 138 Hermes skills (153 SKILL.md files) for cinematic production across LTX, FLUX 2, MiniMax H3, and Wan 3.0. |
| **[hermes-comfyui-skills](https://github.com/0xzgbot/hermes-comfyui-skills)** | ComfyUI playbooks and slash-command bundles for current Hermes: Flux.2, Z-Image, LTX, Wan 3.0, MiniMax H3, vision audit. |
| **Relay** | Local LM Studio chat, mobile UI. Original: [`tmophoto/relay`](https://github.com/tmophoto/relay). *Private.* |

---

Built with **Hermes** on Nous Research models. Earlier original work lives under [`tmophoto`](https://github.com/tmophoto).
