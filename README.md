# AI_VOICE

AI_VOICE is a web-based AI presentation tool that automatically converts PowerPoint slides into narrated, lip-synced videos using AI voice cloning and deep learning-based face animation. Just upload a .pptx file and an image — and the system will handle everything from text extraction to generating a talking avatar.

# Features
🧠 Extracts text from .pptx slides

🗣️ Clones voice using AI text-to-speech

🖼️ Syncs voice with a given image to generate animated video using SAD-Talker

🎞️ Generates final video output for each slide

🔊 Supports multilingual input (optional)

# Tech Stack
Flask — Web framework

Python-pptx — Text extraction from slides

TTS (XTTS) — Text-to-speech synthesis

SAD-Talker — Lip-sync video generation

FFmpeg — Audio/video merging

# How It Works
Upload a PowerPoint file and an image of a face.

The system extracts text from the slides.

Converts each slide’s text into speech.

Uses SAD-Talker to animate the image with the generated speech.

Outputs a complete narrated video presentation.

# License
MIT License © 2025 [Kalyani jupally]
