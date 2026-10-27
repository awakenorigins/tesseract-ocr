# tesseract-ocr — Native OCR text extraction from images

> Pull text out of any image using Tesseract OCR CLI directly. No Python wrappers, no heavy deps — fast, native CLI extraction across multiple languages.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
tesseract-ocr extracts text from images by calling the Tesseract OCR CLI directly — no Python layer. Supports English, Simplified Chinese (chi-sim), and more, including mixed-language extraction in a single pass. Ideal for screenshots, scanned documents, and mixed-language images.

## Features
- Direct Tesseract CLI — no Python dependency
- Multi-language: English, Simplified Chinese, and more
- Mixed-language in one pass (`chi_sim+eng`)
- Fast, lightweight, cross-platform

## Usage / Quick Start
```bash
sudo apt-get install tesseract-ocr tesseract-ocr-chi-sim
# or: brew install tesseract tesseract-lang

tesseract image.png output -l chi_sim+eng
# → output.txt
```

## Trigger Keywords (OpenClaw)
OCR, extract text from image, read text in image, image to text, 识别图片文字

## Related Skills
- [tg-voice-whisper](https://github.com/NachaFromMars/tg-voice-whisper) — audio transcription
- [yt-transcript](https://github.com/NachaFromMars/yt-transcript) — video transcript extraction

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
