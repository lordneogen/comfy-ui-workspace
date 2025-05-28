# ComfyUI Image Collection

This repository contains a set of images generated or processed on May 29, 2025.

## ComfyUI PNG Images

<a href="./До.png"><img src="./До.png" width="400"/></a>
<a href="./Снимок экрана 2025-05-29 010249.png"><img src="./Снимок экрана 2025-05-29 010249.png" width="200"/></a>
<a href="./Снимок экрана 2025-05-29 010258.png"><img src="./Снимок экрана 2025-05-29 010258.png" width="200"/></a>

<p float="left">
  <a href="./ComfyUI_00887_.png"><img src="./ComfyUI_00887_.png" width="200"/></a>
  <a href="./ComfyUI_00888_.png"><img src="./ComfyUI_00888_.png" width="200"/></a>
  <a href="./ComfyUI_00899_.png"><img src="./ComfyUI_00899_.png" width="200"/></a>
  <a href="./ComfyUI_00900_.png"><img src="./ComfyUI_00900_.png" width="200"/></a>
  <a href="./ComfyUI_00903_.png"><img src="./ComfyUI_00903_.png" width="200"/></a>
  <a href="./ComfyUI_00904_.png"><img src="./ComfyUI_00904_.png" width="200"/></a>
  <a href="./ComfyUI_00905_.png"><img src="./ComfyUI_00905_.png" width="200"/></a>
  <a href="./ComfyUI_00906_.png"><img src="./ComfyUI_00906_.png" width="200"/></a>
  <a href="./ComfyUI_00907_.png"><img src="./ComfyUI_00907_.png" width="200"/></a>
  <a href="./ComfyUI_00908_.png"><img src="./ComfyUI_00908_.png" width="200"/></a>
  <a href="./ComfyUI_00911_.png"><img src="./ComfyUI_00911_.png" width="200"/></a>
  <a href="./ComfyUI_00912_.png"><img src="./ComfyUI_00912_.png" width="200"/></a>
</p>

## Originals and Other Images

<p float="left">
  <a href="./original 1.webp"><img src="./original 1.webp" width="200"/></a>
  <a href="./original 2.webp"><img src="./original 2.webp" width="200"/></a>
  <a href="./original 3.png"><img src="./original 3.png" width="200"/></a>
  <a href="./original 4.jpg"><img src="./original 4.jpg" width="200"/></a>
  <a href="./original 5.webp"><img src="./original 5.webp" width="200"/></a>
</p>

## Configuration Summary (from `Kusanov.json`)

### Models Used

- **UNet**: `fluxFillFP8_v10.safetensors` with precision `fp8_e4m3fn`
- **VAE**: `FLUX1/ae.safetensors`
- **CLIP**: `clip_l.safetensors`
- **T5**: `t5xxl_fp8_e4m3fn.safetensors`
- **CLIP Vision**: `sigclip_vision_patch14_384.safetensors`
- **Style Model**: `flux1-redux-dev.safetensors`

### Important Nodes & Parameters

#### `KSampler`
- Seed: `random`
- Steps: `20`
- CFG: `1`
- Sampler: `euler`
- Scheduler: `normal`

#### `ReduxAdvanced`
- Mode: `area`
- Aspect: `keep aspect ratio`
- Style weight: `0.1`

#### `FluxGuidance`
- Weight: `30`

#### `ImageCrop+`
- Size: `256x256`
- Position: `top-left`

#### `EmptyImage`
- Default resolution: `512x512`

#### `ImageScale`
- Method: `nearest-exact`

#### `Prompt`
- Input: `"short black suit"`

#### `LayerMask: PersonMaskUltra V2`
- Engine: `VITMatte`
- Confidence: `0.4`
- Device: `cuda`
- Batch size: `2`
  
## Files

- `Kusanov.json` — metadata or config file
- `desktop.ini` — system file, can be ignored

---

Click on any image to view it in full size.
