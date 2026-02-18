# Jimeng Seedance 2.0 Prompt Engineer Skill (即梦 Seedance 2.0 提示词优化专家) 🎬

这是一个为字节跳动 **即梦 (Jimeng) Seedance 2.0** 视频生成模型量身定制的 OpenClaw Skill。它能将您的简单创意转化为符合官方标准的“导演级”提示词。

## 功能亮点 ✨

*   **官方标准对齐**: 基于内部泄露/公开的“Seedance 2.0 使用手册”开发，确保生成的 Prompt 完美契合模型训练结构。
*   **电影级运镜控制**: 自动添加 Seedance 2.0 擅长的运镜标签（如推拉摇移、手持感、一镜到底）。
*   **动态动作增强**: 针对打斗、舞蹈等复杂场景，自动加入“流畅动作 (Fluid Motion)”和“一致性 (Consistency)”关键词，减少画面崩坏。
*   **音画同步准备**: 包含对音效环境的描述，适配新版模型的“视频生音频”功能。

## 安装方法 📦

在您的 OpenClaw 环境中，将此仓库克隆到 skills 目录：

```bash
cd /opt/homebrew/lib/node_modules/@qingchencloud/openclaw-zh/skills/
git clone https://github.com/kingpyfiou/jimeng-prompt.git
```

## 使用指南 🚀

在 OpenClaw 对话中，直接下达指令：

> "帮我生成一个视频提示词：两个老头在竹林打架"

Agent 会自动调用此 Skill，输出一份结构清晰、细节丰富的提示词（通常包含中英文对照），您可以直接复制到即梦使用。

## 提示词结构

本 Skill 生成的提示词遵循以下黄金法则：

1.  **主体 (Subject)**: 详细的外貌、服装、材质描述。
2.  **动作 (Action)**: 具体的动词和动态幅度（Seedance 2.0 的核心）。
3.  **环境 (Environment)**: 光影、天气、背景氛围。
4.  **运镜 (Camera)**: 镜头语言和角度。
5.  **音效 (Audio)**: 声音场景描述。
6.  **技术参数 (Tech Specs)**: 分辨率、风格标签。

## 许可证 📄

MIT License. 由 **小光 (Xiao Guang)** 为 **GAME KING (老板)** 专属定制。
