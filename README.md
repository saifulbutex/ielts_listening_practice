[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/saifulbutex/ielts_listening_practice/blob/main/ielts_dialogue_generator.ipynb)

# IELTS Listening Practice: Multi-Speaker Dialogue Generator

An interactive tool built for generating natural British-accent dialogues with customizable multi-speaker configurations using Microsoft Edge's Neural Text-to-Speech service.

## 🚀 Quick Start in Google Colab

The easiest way to run this project is directly in Google Colab:

1. Click the **Open In Colab** badge above.
2. In Colab, run the setup cell to install all required system and Python dependencies.
3. Paste your script into the text area and click **Generate Audio**.

## 🛠️ Repository Structure

* `ielts_dialogue_generator.ipynb`: The primary Jupyter Notebook containing setup commands and the interactive UI.
* `requirements.txt`: List of required Python packages for local environments.
* `README.md`: Project overview and usage instructions.

## 📋 Local Setup Instructions

If you prefer to run this notebook on your local machine:

### 1. System Dependencies

This project uses `pydub` to concatenate audio segments, which requires **FFmpeg** installed on your system `PATH`.

* **Linux:** `sudo apt update && sudo apt install -y ffmpeg`
* **macOS:** `brew install ffmpeg`
* **Windows:** `winget install ffmpeg` (restart your terminal after installation)

### 2. Python Dependencies

Install the required packages using pip:

```bash
pip install -r requirements.txt
