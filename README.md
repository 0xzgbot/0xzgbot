# 0xzgbot

Tools for making physical work: CNC/CAM, sand casting, and photography production. Also local AI agents and chat UIs.

Several of these repos are **private while I build** — source stays closed; the work is still happening. Original (not forked) earlier projects live on [`tmophoto`](https://github.com/tmophoto).

---

## CNC / CAM

### [ShopPilot](https://github.com/0xzgbot/ShopPilot)
Native **macOS** CNC suite (Swift). Design vectors, generate 2.5D and 3D toolpaths, simulate the cut, and stream to GRBL/FluidNC. Jobs save as `.shoppilot` packages.

### [VectorPilot](https://github.com/0xzgbot/VectorPilot)
**Windows** sibling of ShopPilot. C# / .NET 8 + WPF. Same document format and machine-safety rules: design → toolpaths → 3D preview → post → machine control.

---

## Casting & metal

### SculptCast
*Source private while in development.*

Instant-quote metal casting. Upload an STL, get a price per part in aluminum or bronze. Next.js site + FastAPI quote engine.

### Sand casting simulation
Public original: [`tmophoto/sand_casting_v2`](https://github.com/tmophoto/sand_casting_v2). A private copy on this account is where I keep developing it.

Process simulation for sand casting — gating, fill, and foundry workflow, not a generic CFD demo.

### MadeFromFire
*Source private while in development.*

Atelier shop for custom terrain jewelry and bronze topographic objects (Little Cottonwood Canyon, Utah). Includes a topographic record-weight designer / configurator (`topo-record-weight-designer`).

---

## Photography

### Photo labeler
*Source private while in development.*

Eyewear product photo labeling pipeline. **macOS** (Swift) and **Windows** production app — same job, two machines.

---

## Local AI & media

### [Relay](https://github.com/tmophoto/relay)
Local LM Studio chat UI (original on `tmophoto`). Follow-ons on this account, source private: **TurboQuant mobile** and **Relay superapp**.

### [Cinesmith](https://github.com/0xzgbot/forge-nps-v01)
Formerly Forge NPS. Hermes-led cinematic AI production runtime: brief like an executive producer; Hermes plans, renders, audits, and remembers. Private workspaces on this account: `The-Forge`, `forge`.

### [hermes-media-skill-pack](https://github.com/0xzgbot/hermes-media-skill-pack)
129 media-production skills for Hermes Agent — cinematography, lighting, style emulation, character consistency, prompt engineering, LTX / FLUX video workflows, audio and post.

### [hermes-comfyui-skills](https://github.com/0xzgbot/hermes-comfyui-skills)
Hermes Agent skill bundles for ComfyUI image and video generation.
