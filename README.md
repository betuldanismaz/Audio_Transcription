
# Audio Transcription Project

This repository contains the results of an audio transcription performed using OpenAI's Whisper model in Google Colab.

## Project Overview

The goal of this project was to transcribe an audio file (e.g., `your_audio_file.m4a`) into text and generate corresponding subtitle files.

## Files Included

*   `your_audio_file_transcript.txt`: The full text transcription of the audio file.
*   `your_audio_file.srt`: Subtitle file with timestamps for the transcribed audio.
*   `transcription_notebook.ipynb`: The Google Colab notebook used for the transcription process.
*   `README.md`: This file.

## Transcription Details

*   **Original Audio File:** Replace with the actual name of your audio file (e.g., `your_audio_file.m4a`) (located in Google Drive)
*   **Whisper Model Used:** `large`
*   **Language Detected:** Turkish (based on the provided transcription preview)

## How to Replicate (Google Colab)

1.  **Open the Notebook:** Open `transcription_notebook.ipynb` in Google Colab.
2.  **Mount Google Drive:** The notebook will prompt you to mount your Google Drive to access the audio file.
3.  **Place Audio File:** Ensure your audio file (e.g., `your_audio_file.m4a`) is located in the root of your Google Drive (`/content/drive/MyDrive/`). If your file path is different, you'll need to update the `file_path` variable in the notebook.
4.  **Run Cells:** Execute all cells in the notebook sequentially.

## Libraries Used

*   [OpenAI Whisper](https://github.com/openai/whisper)
*   `ffmpeg` (for audio processing)


