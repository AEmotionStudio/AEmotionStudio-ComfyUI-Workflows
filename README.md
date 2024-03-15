(https://github.com/AEmotionStudio/AEmotionStudio_ComfyUI_Workflows/assets/163354043/eb8dc795-28d6-4318-af1a-c41e891b6ed2)

This suite is a collection of modules which aims to cover the entire creation process from prompts to full on animations, in a neat, organized, and compact fashion.

The ultimate goal is to streamline productivity while outputting high quality content, without the need to switch back and forth between a bunch of other workflows.

All modules here are uniform and have a left-to-right, top-to-bottom flow (sequential flow). Meaning they read just like a book.

No nodes are hidden, there are no extravagant re-routes, and all similar or branching nodes are grouped together accordingly.

I have also included a good bit of notation within the workflows themselves, in order to answer any questions one may have when using these.

Below is a brief break down of the suite and all its contents.

Prompt Generator - Module #1:

You can use this module as a type of brain-storming workshop for prompting. It contains a variety of ways to generate prompts.

- LLaVA captioner to prompt
- GPT to prompt for use with offline LLM's (large language models)
- VLM nodes for visualizing images to prompts such as Moondream and Joytag
- Other visualization nodes such as BLIP and WD 1.4 Tagger
- A bunch of auto-prompters both controlled and random

Image Generator - Module #2:

Used to create images from text as well as loaded images.

- Text to Image Generation
- Image to Image Generation

Compositing & Editing - Module #3:

This module handles a variety of tasks related to compositing and editing.

- In-painting
- ClipsSeg
- Pix2Pix
- Watermark Creation
- Simple Mask
- Gligen
- IPAdapter Attention Masking
- IPAdapter Styler
- IPAdapter FaceID/Face Swapper
- Image and Text Overlay
- Image Cropping
- Image Border Creation
- Filters, Colors, and Post-Processing

Animation Generator - Module #4:

This modules aim is to provide a multitude of ways to create animations, from text, video, and images.

- Text to Video (AnimateDiff)
- Video to Video (AnimateDiff)
- Attention Masking & Image Composite to Video (AnimateDiff)
- In-paint Image to Video (AnimateDiff)
- Video Upscale (AnimateDiff)
- Image to Video (SVD)
- Simple Frame Interpolation
- MotionDiff & SMPL
- Video Remove Background

All Modules - Combined:

The All Modules .json contains all of the modules put together in one large workflow. It is recommended to use the split versions, if you don't want to download a bunch of nodes at once or if you are running on a complete potato pc.

Tested on a fresh install of ComfyUI with a 4070 @12GBs.

Thanks to all the wonderful node and model creators used within this suite!
