# Image Data Generation using a Modular Pipeline

This project investigates image-to-image translation for road scene images using pretrained generative models.
The aim is to generate adverse weather variants of road scenes while peserving the orginal structure.


## Pipeline

1. Upload input image and reference image
2. Enter weather translation prompt
3. BLIP-2 caption generation
4. MiDaS depth estimation
5. ControlNet structure preservation
6. IP-Adapter reference image conditioning
7. Stable Diffusion image-to-image generation


## Models

- BLIP-2: Salesforce/blip2-opt-2.7b
- MiDaS: DPT_Hybrid
- Stable Diffusion: stable-diffusion-v1-5/stable-diffusion-v1-5
- ControlNet Depth: lllyasviel/sd-controlnet-depth
- IP-Adapter: h94/IP-Adapter
