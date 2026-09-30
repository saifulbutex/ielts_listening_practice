# ielts_listening_practice
Multi-Speaker IELTS Listening Dialogue Generator

An interactive tool built for generating natural British-accent dialogues with customizable multi-speaker configurations using Microsoft Edge's Neural Text-to-Speech service.

🚀 Quick Start in Google Colab

The easiest way to run this project is directly in Google Colab:

Click the Open In Colab badge above.

In Colab, run the setup cell to install all required system and Python dependencies.

Paste your script into the text area and click Generate Audio.

🛠️ Repository Structure

ielts_dialogue_generator.ipynb: The primary Jupyter Notebook containing setup commands and the interactive UI.

requirements.txt: List of required Python packages for local environments.

README.md: Project overview and usage instructions.

📋 Local Setup Instructions

If you prefer to run this notebook on your local machine:

1. System Dependencies

This project uses pydub to concatenate audio segments, which requires FFmpeg installed on your system PATH.

Linux: sudo apt update && sudo apt install -y ffmpeg

macOS: brew install ffmpeg

Windows: Install via winget install ffmpeg or download from FFmpeg Official Site and add bin to Environment Variables.

2. Python Dependencies

Install the required packages using pip:

pip install -r requirements.txt


3. Launch Notebook

jupyter notebook ielts_dialogue_generator.ipynb


✍️ Script Formatting Guide

Format your script as follows:

Speaker 1: Hello, could you tell me where the library is?
Speaker 2: Sure, it's just past the main square on your left.
Speaker 1: Thank you so much!


First detected speaker is automatically assigned en-GB-RyanNeural (Male).

Second detected speaker is automatically assigned en-GB-SoniaNeural (Female).
