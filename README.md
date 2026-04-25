# PNG Metadata Reader

PNG Metadata Reader is a standalone metadata reader made completely from scratch.

I created this tool to solve a personal problem while using ComfyUI, because I wanted a cleaner and more useful way to read generation metadata from images and videos.

The tool detects and organizes the most important information, including source, checkpoint, prompts, LoRAs, generation parameters and extra metadata. It also includes a Raw tab for checking the original metadata directly.

It supports PNG, JPG, WebM and MP4 files, and includes local tools to edit or remove metadata.

## Main features

- Reads metadata from PNG, JPG, WebM and MP4 files.
- Organizes prompts, LoRAs, generation parameters and extra information.
- Supports metadata from different AI generation tools, with special focus on ComfyUI and Stable Diffusion workflows.
- Includes a Raw tab to inspect the original metadata.
- Includes local tools to edit or remove metadata.
- Includes a Danbooru tag system to search and detect tags from prompts.
- Works directly in the browser as a standalone HTML file.

## Usage

Use online:

[link here]

Or use locally:

Download the HTML file and drag it into your web browser.

Local use is recommended. If PNG Metadata Reader and LoRA Metadata Reader are in the same directory, the tool can open LoRA Metadata Reader locally, making the workflow faster and easier when using both tools together.
LoRa Metadata Reader> https://github.com/shirosaki33/Lora-Metadata-Reader
