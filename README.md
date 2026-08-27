# 0xzgbot

Native tools for **making physical things** — CNC, metal casting, product photography — and the local AI stack that builds them.

Public source where it helps. Private while a product is still in the shop.

---

## CNC

Two native apps. One job file (`.shoppilot`). Design → toolpaths → preview → machine.

| | Platform | |
| --- | --- | --- |
| **[ShopPilot](https://github.com/0xzgbot/ShopPilot)** | macOS · SwiftUI | Profile, pocket, drill, V-carve, 3D rough/finish, photo lithophane, nesting. GRBL/FluidNC + built-in simulator. Hold/Reset always on screen. |
| **[VectorPilot](https://github.com/0xzgbot/VectorPilot)** | Windows · C# / WPF | Same document, same safety rules. 3D preview, posts, machine control. |

---

## Casting

| | |
| --- | --- |
| **SculptCast** | Instant-quote metal casting. Upload an STL, get a price per part in aluminum or bronze. *Source private.* |
| **Casting simulator** | Sand molds, ceramic shell, multiple metals. STL → gating, fill, solidification, defect flags. Public original: [`tmophoto/sand_casting_v2`](https://github.com/tmophoto/sand_casting_v2). |
| **Made From Fire** | Forged-goods studio — steel, bronze topographic objects, and a terrain record-weight configurator. *Source private.* |

---

## Photography

**Photo Labeler** — multi-AI LLM/VLM pipeline for eyewear product photos. RAW in → dual-model consensus → product, color, lens + confidence → XMP sidecars (Capture One). macOS + Windows production. *Source private.*

---

## Local AI & media

| | |
| --- | --- |
| **[Cinesmith](https://github.com/0xzgbot/forge-nps-v01)** | Fully local cinematic pipeline. Isolated Hermes (does not touch yours) orchestrates DGX Spark + dual RTX 3090s running multiple ComfyUI instances. Plan → render → audit → remember. |
| **[hermes-media-skill-pack](https://github.com/0xzgbot/hermes-media-skill-pack)** | 129 Hermes Agent skills — cinematography, lighting, character consistency, LTX 2.3 / FLUX 2, audio and post. |
| **[hermes-comfyui-skills](https://github.com/0xzgbot/hermes-comfyui-skills)** | Hermes skill bundles for ComfyUI image and video (Flux.2, LTX, Wan, SDXL). |
| **Relay** | Local LM Studio chat. Original: [`tmophoto/relay`](https://github.com/tmophoto/relay). Mobile UI on this account. *Source private.* |

---

Built with **Hermes** on Nous Research free models. Prompts in Grok 4.6 low. Verify and correction in Grok 4.6 max.

Earlier original work: [`tmophoto`](https://github.com/tmophoto).
