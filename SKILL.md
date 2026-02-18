# Jimeng Seedance 2.0 Prompt Engineer

## Description
This skill optimizes user prompts for the **Jimeng (即梦) Seedance 2.0** video generation model. It transforms short, rough ideas into professional, structured video generation prompts that leverage the model's specific capabilities (consistency, camera control, audio syncing, etc.).

## Usage
Use this skill when the user asks to generate a video prompt, optimize a prompt for Jimeng/Seedance, or wants to create a video using ByteDance's Jimeng AI.

## Prompt Structure (Seedance 2.0 Standard)
The optimized prompt should follow this logical flow:
1.  **Subject & Appearance:** Detailed character/object description (clothing, texture, style).
2.  **Action & Movement:** Specific dynamics (walking, running, fighting, dancing). *Key for Seedance 2.0.*
3.  **Environment & Lighting:** Background, weather, lighting (cinematic, natural, neon).
4.  **Camera Language:** Lens movement (Pan, Tilt, Zoom, Dolly, One-take/Long-shot). *Seedance 2.0 excels here.*
5.  **Audio/Atmosphere (Optional):** Sound effects or mood description (e.g., "upbeat rhythm", "sound of rain").
6.  **Technical Tags:** `4k`, `high quality`, `fluid motion`, `highly detailed`.

## Input vs Output Example
**Input:** "A cat dancing in the rain."
**Output:**
```markdown
**Subject:** A cute British Shorthair cat, wet fur texture, wearing a small yellow raincoat.
**Action:** Standing on hind legs, performing a rhythmic tap dance, splashing in puddles.
**Environment:** City street at night, neon lights reflecting on wet pavement, heavy rain falling.
**Camera:** Low angle shot, camera follows the cat's movement, slight slow motion.
**Audio:** Sound of rain pattering, rhythmic splashing sounds, upbeat jazz background music.
**Tech Specs:** 4k, cinematic lighting, high fidelity, Seedance 2.0 style.
```

## Instructions for the Agent
1.  **Analyze** the user's raw input for core intent.
2.  **Expand** missing details (if user says "man", define "cyberpunk warrior" or "business suit" based on context or ask; if context is vague, pick a high-quality default).
3.  **Enhance** with Seedance 2.0 specific keywords:
    *   For smoothness: "fluid motion", "consistency".
    *   For camera: "one-take", "dynamic camera".
    *   For audio: "audio reactive", "sound design".
4.  **Format** the output clearly so the user can copy-paste it into Jimeng.

## Version
v1.0 (Based on Official Lark Wiki: Seedance 2.0 Manual)
