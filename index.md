---
layout: default
title: Motion2MIDI - Hand Motion Control for DAWs
description: Control your DAW with hand movements using your webcam
---

![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/froehlicht/motion2midi/total) ![GitHub Tag](https://img.shields.io/github/v/tag/froehlicht/motion2midi) ![GitHub Repo stars](https://img.shields.io/github/stars/froehlicht/motion2midi) [![Email](https://img.shields.io/badge/Email-white?logo=gmail)](mailto:contact@motion2midi.com)

# Motion2MIDI

Control your DAW with hand movements using your webcam.

> **Note:** This repository is for distribution and feedback only. The source code is closed-source.

---

## 🎬 See It In Action

[![Motion2MIDI Demo](media/demo.mp4)](https://github.com/user-attachments/assets/4b8e2665-b8d5-49b8-9712-5e6043f14a10)

_Watch how Motion2MIDI transforms movements into MIDI control_

---

## 📦 Download

**Latest Release:** [Download Motion2MIDI v0.9.2-beta](https://github.com/froehlicht/motion2midi/releases/latest)

### macOS Universal (x86_64, arm64)

- **[Download Motion2MIDI v0.9.2-beta](https://github.com/froehlicht/motion2midi/releases/tag/v0.9.2)** - Includes both AU and VST3

**Planned Support:**

- Windows (coming soon)

---

## 🎯 Features

- **Real-time hand tracking** using YOLO computer vision model
- **4 MIDI CC outputs** - Map left/right hand X/Y positions to any parameter
- **MIDI Map** - Assign any CC number per parameter
- **Mute/Solo controls** - Focus on specific parameters
- **Customizable visualization** - Toggle video feed, keypoints, skeleton, and control zones
- **Per-session settings** - Preferences saved with your DAW project
- **Automatic updates** - Get notified when new versions are available

---

<div style="text-align: center; margin: 50px 0;">
  <a href="https://github.com/froehlicht/motion2midi/releases/latest" 
     style="display: inline-block; padding: 20px 50px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); 
            color: white; text-decoration: none; border-radius: 10px; font-weight: bold; font-size: 20px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3); transition: transform 0.2s;">
    ⬇️ Download Latest Release
  </a>
</div>

---

## 🚀 Quick Start Guide

### 1. Installation

1. **Download** Motion2MIDI from [Releases](https://github.com/froehlicht/motion2midi/releases/latest)
2. **Unzip** the downloaded file
3. **Copy plugins to your plugin folder**:
    - **AU:** `~/Library/Audio/Plug-Ins/Components/Motion2MIDI.component`
    - **VST3:** `~/Library/Audio/Plug-Ins/VST3/Motion2MIDI.vst3`
4. **Restart your DAW**

### 2. Setup IAC Driver (macOS)

The IAC Driver creates a virtual MIDI bus for routing MIDI between applications.

#### How to activate the IAC Driver:

1. Open **Audio MIDI Setup** (Applications → Utilities → Audio MIDI Setup)
2. Go to **Window → Show MIDI Studio** (or press ⌘2)
3. Double-click the **IAC Driver** icon
4. Check **"Device is online"**

For full documentation, visit: [GitHub Repository](https://github.com/froehlicht/motion2midi#readme)

---

<div style="text-align: center; margin: 40px 0;">
  <img src="https://img.shields.io/github/downloads/froehlicht/motion2midi/total?style=for-the-badge&label=Downloads&color=667eea" alt="Downloads">
  <img src="https://img.shields.io/github/v/tag/froehlicht/motion2midi?style=for-the-badge&label=Version&color=764ba2" alt="Version">
  <img src="https://img.shields.io/github/stars/froehlicht/motion2midi?style=for-the-badge&color=667eea" alt="Stars">
</div>

---

## 📋 System Requirements

- **macOS** 12.0 (Monterey) or later
- **Webcam** - Built-in or external USB camera
- **DAW** - Any DAW with MIDI mapping functionality

### Tested DAWs

✅ Ableton Live 11
✅ FL Studio 21  
📝 Logic Pro (mapping guide coming soon)

---

## 🛠 Report Bugs & Request Features

Found a bug or have a feature idea?

- **[Report a Bug](https://github.com/froehlicht/motion2midi/issues/new?template=bug_report.yml)** - Help us improve Motion2MIDI
- **[Request a Feature](https://github.com/froehlicht/motion2midi/issues/new?template=feature_request.yml)** - Share your ideas
- **[View All Issues](https://github.com/froehlicht/motion2midi/issues)** - See what others are reporting

You can also use the built-in feedback buttons:

- **Settings button** → Bug Report / Quick Feedback

---

<div style="background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%); 
            padding: 50px; border-radius: 15px; margin: 50px 0; text-align: center;">
  <h2>📧 Get in Touch</h2>
  <p style="font-size: 18px; margin: 30px 0;">
    <strong>Email:</strong> <a href="mailto:contact@motion2midi.com" style="color: #667eea;">contact@motion2midi.com</a><br><br>
    <strong>GitHub:</strong> <a href="https://github.com/froehlicht/motion2midi" style="color: #764ba2;">Repository</a><br><br>
    <strong>Issues:</strong> <a href="https://github.com/froehlicht/motion2midi/issues" style="color: #667eea;">Bug Reports & Features</a>
  </p>
</div>

---

<p style="text-align: center; color: #666; font-size: 14px; margin-top: 50px;">
  Made with ❤️ for music producers | © 2025 Motion2MIDI
</p>
