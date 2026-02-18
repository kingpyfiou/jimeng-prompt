# Jimeng Seedance 2.0 Prompt Engineer Skill 🎬

A specialized OpenClaw skill for optimizing video generation prompts for ByteDance's **Jimeng (即梦) Seedance 2.0** model.

## Features ✨

*   **Official Spec Compliance**: Based on the leaked/internal "Seedance 2.0 User Manual" (Lark Wiki), ensuring prompts align with the model's actual training data structure.
*   **Cinematic Camera Control**: Automatically adds camera movement tags (Pan, Tilt, Zoom, Dolly, Handheld) that Seedance 2.0 excels at.
*   **Dynamic Action Enhancement**: Focuses on "Fluid Motion" and "Consistency" keywords to prevent artifacting in complex scenes (like fighting or dancing).
*   **Audio Sync Ready**: Includes audio descriptions for the model's new video-to-audio generation capabilities.

## Installation 📦

Clone this repository into your OpenClaw skills directory:

```bash
cd /opt/homebrew/lib/node_modules/@qingchencloud/openclaw-zh/skills/
git clone git@github.com:kingpyfiou/jimeng-prompt.git
```

## Usage 🚀

In OpenClaw, simply ask:

> "帮我生成一个视频提示词：两个老头在竹林打架"

The agent will use this skill to output a structured, high-fidelity prompt optimized for Jimeng.

## Prompt Structure

The skill generates prompts in the following format:

1.  **Subject (主体)**: Detailed appearance & clothing.
2.  **Action (动作)**: Specific verbs & dynamics.
3.  **Environment (环境)**: Lighting, weather, background.
4.  **Camera (运镜)**: Lens movement & angles.
5.  **Audio (音效)**: Soundscape description.
6.  **Tech Specs**: Resolution & style tags.

## License 📄

MIT License. Created by **Xiao Guang (小光)** for **GAME KING**.
