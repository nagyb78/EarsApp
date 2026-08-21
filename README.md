# Ears

A macOS menu bar recorder that turns meetings into Markdown.

Ears records your microphone and the system audio as two separate tracks,
transcribes them, works out who said what, and writes a Markdown transcript and
summary into a folder you choose — designed to sit inside an Obsidian vault.

Transcription and summarisation can run locally on your Mac (whisper.cpp,
Parakeet, Ollama, MLX) or through a cloud provider you configure (Deepgram,
OpenAI, Anthropic, OpenRouter).

## Download

**[Latest release](https://github.com/nagyb78/EarsApp/releases/latest)** — a
signed and notarized Developer ID app. Once installed, Ears updates itself:
it checks for new versions, tells you when one exists, and never installs while
a recording is in progress.

## Requirements

- macOS 14 or later
- Asks for Screen Recording, Microphone and Calendar permission on first use
- Not distributed through the Mac App Store

## A note on recording

Ears records meetings. Recording other people may require their consent
depending on where you and they are — that is your responsibility, not the
app's.

## This repository

This repo hosts the releases. The source is not published here.
