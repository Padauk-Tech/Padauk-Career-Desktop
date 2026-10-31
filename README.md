<div align="center">

# Padauk Career — Desktop

**Your AI-Powered Career & Interview Preparation Companion**

[![Latest Release](https://img.shields.io/github/v/release/Padauk-Tech/Padauk-Career-Desktop?include_prereleases&label=Latest%20Release&style=for-the-badge)](https://github.com/Padauk-Tech/Padauk-Career-Desktop/releases)
[![Downloads](https://img.shields.io/github/downloads/Padauk-Tech/Padauk-Career-Desktop/total?style=for-the-badge&label=Downloads)](https://github.com/Padauk-Tech/Padauk-Career-Desktop/releases)
[![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-blue?style=for-the-badge)](https://github.com/Padauk-Tech/Padauk-Career-Desktop/releases)

[**Download Latest Release →**](https://github.com/Padauk-Tech/Padauk-Career-Desktop/releases/latest)

</div>

---

## Overview

**Padauk Career Desktop** is a native, privacy-first desktop application designed to help you manage your career profile, tailor resumes and cover letters to job descriptions, and practice realistic AI mock interviews—all running locally on your machine with zero external database setup required.

---

## 📥 Downloads

Download the installer for your operating system from the [**Releases**](https://github.com/Padauk-Tech/Padauk-Career-Desktop/releases) page:

| Operating System | Architecture | Installer Format | Recommended For |
| :--- | :--- | :--- | :--- |
| **macOS** (11.0+) | Apple Silicon (`aarch64`) | `.dmg` | Mac with M1 / M2 / M3 / M4 chip |
| **macOS** (11.0+) | Intel (`x86_64`) | `.dmg` | Intel-based Mac |
| **Windows** (10 / 11) | 64-bit (`x64`) | `.msi` / `.exe` | Windows 10 & Windows 11 (64-bit) |

---

## ✨ Key Features

- **100% Local & Self-Contained**: Runs an embedded local server and SQLite database on your computer—your career data, resumes, and interview sessions stay on your device.
- **Career Biography & Resume Hub**: Import your existing resume (PDF) or build structured career profiles (experience, education, skills, certifications).
- **Job Tracking & Tailoring**: Track job applications, generate tailored resumes and cover letters, and draft custom answers to application questions.
- **Interactive AI Mock Interviews**: Practice behavioral, technical, and role-specific interviews with real-time AI feedback and question-by-question coaching.
- **Bring Your Own AI Model (BYOK & Local LLMs)**:
  - **Cloud Providers**: Google Gemini, OpenAI, and compatible APIs.
  - **Local AI**: Run completely offline/free using [Ollama](https://ollama.com/) on your own machine.

---

## 🛠 Installation Guide

### macOS
1. Download the `.dmg` file matching your Mac's processor (`aarch64` for Apple Silicon or `x64` for Intel) from [Releases](https://github.com/Padauk-Tech/Padauk-Career-Desktop/releases).
2. Open the downloaded `.dmg` file and drag **AI Interview Practice** (Padauk Career) into your **Applications** folder.
3. **First Launch Note (macOS Gatekeeper)**:
   If macOS shows an *"unidentified developer"* or *"app is damaged"* prompt on first launch:
   - Right-click (or Control-click) the app in **Applications** and select **Open**, or
   - Run the following command in Terminal to clear the quarantine flag:
     ```bash
     xattr -cr "/Applications/AI Interview Practice.app"
     ```

### Windows
1. Download the `.msi` or `.exe` installer from [Releases](https://github.com/Padauk-Tech/Padauk-Career-Desktop/releases).
2. Run the installer and follow the setup wizard.
3. **First Launch Note (Windows SmartScreen)**:
   If Windows Defender SmartScreen displays *"Windows protected your PC"*, click **More info** → **Run anyway**.

---

## ⚙️ Quick Start after Installation

1. **Launch the App**: The embedded local server and database initialize automatically in the background.
2. **Configure Your AI Provider**:
   - Navigate to **Settings → AI Keys / AI Models**.
   - Add your **Gemini** or **OpenAI** API key, or connect to your local **Ollama** instance (`http://localhost:11434`).
3. **Set Up Your Biography**: Upload your resume or fill in your career profile under **Biography**.
4. **Add a Job & Start Practicing**: Add a target job listing and launch your first **Mock Interview** session!

---

## 🐛 Feedback & Issues

Found a bug or have a feature request? Please open an issue in the [**Issues**](https://github.com/Padauk-Tech/Padauk-Career-Desktop/issues) tab of this repository with:
- Your OS version (macOS / Windows)
- App version (e.g., `v0.1.0`)
- Steps to reproduce or screenshots

---

<div align="center">
  Built by <strong>Padauk Tech</strong>
</div>
