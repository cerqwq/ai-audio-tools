# 🎵 AI Audio Tools

AI音频工具，支持音频处理、语音合成、音乐生成。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🔊 TTS脚本生成
- 🎵 音乐提示生成
- 🔊 音效描述生成
- 🎙️ 播客脚本生成
- 🎧 音频品牌设计
- 📊 音频内容分析

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_audio_tools import create_tools

tools = create_tools()

# TTS脚本
tts = tools.generate_tts_script("你好世界", "zh-CN-XiaoxiaoNeural")

# 音乐提示
music = tools.generate_music_prompt("放松", "古典")

# 音效描述
sfx = tools.generate_sound_effect("爆炸", "游戏场景")

# 播客脚本
podcast = tools.generate_podcast_script("AI发展", "30分钟")

# 音频品牌
brand = tools.generate_audio_branding("TechCorp", ["创新", "专业"])

# 音频分析
analysis = tools.analyze_audio_content("对话录音")
```

## 📁 项目结构

```
ai-audio-tools/
├── tools.py       # 音频工具核心
└── README.md
```

## 📄 许可证

MIT License
