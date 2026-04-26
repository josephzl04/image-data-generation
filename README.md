# Image Data Generation using Diffusion Models

This project investigates conditional image translation using pretrained generative models.

## Current Pipeline

1. Input image upload
2. BLIP-2 caption generation
3. MiDaS depth estimation
4. Stable Diffusion + ControlNet generation
5. IP-Adapter conditioning

## Models

- BLIP-2: Salesforce/blip2-opt-2.7b
- MiDaS: DPT_Hybrid
- Stable Diffusion: runwayml/stable-diffusion-v1-5
- ControlNet Depth: lllyasviel/sd-controlnet-depth
- IP-Adapter: h94/IP-Adapter
