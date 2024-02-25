# Speaker Diarization and Audio Segmentation Project

## Overview:

This project aims to streamline the analysis of YouTube videos by taking a YouTube link as input, downloading the video, converting it into an audio file, and performing advanced audio processing tasks. The primary focus is on speaker diarization, visualization, and extraction of individual speaker audio segments.

## Key Features:

### YouTube Link Processing:

1. Accepting a YouTube link as input.
2. Downloading the video and extracting the audio component.

### Audio Format Standardization:

1. Converting the audio to a ".wav" file.
2. Adjusting the audio to mono-channel for consistency.
3. Setting the audio sample rate to 22050 Hz.

### Background Noise Removal:

1. Applying noise reduction techniques to enhance audio quality.

### Speaker Diarization:

1. Utilizing diarization algorithms to identify distinct speakers.
2. Generating a diarization result file (.rttm) with speaker labels and time segments.

### Visualization:

1. Plotting the diarized speakers on a graph for a visual representation of speaker turns and overlaps.

### Audio Segmentation and Organization:

1. Separating the audio into chunks of 10 seconds.
2. Organizing the resulting audio chunks into subdirectories for each speaker.

## Usage:

- Provide a YouTube link for analysis.
- Download and extract the audio from the video.
- Perform necessary audio format standardization and noise reduction.
- Apply speaker diarization for identifying speakers and obtaining time segments.
- Visualize speaker turns and overlaps with a graphical representation.
- Separate audio segments of each speaker and organize them into 10-second chunks in subdirectories.

## Dependencies:

- Python
- Librosa
- SciPy
- Pydub
- YouTube API (for downloading)

## Potential Applications:

- Podcast and video transcription
- Extracting insights from YouTube interviews or discussions
- Automated audio content analysis for research or content creators

## Note:
This project provides a comprehensive solution for extracting valuable information from YouTube audio content, offering users the ability to visualize speaker interactions and efficiently organize speaker-specific audio segments for further analysis.

