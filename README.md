# Reddit Shorts Generator

A Python-powered tool that transforms captivating Reddit stories into short, narrated videos (e.g., YouTube Shorts, TikTok) with background visuals and optional subtitles—all automated from start to finish.

## Features

- Scrapes engaging stories from your favorite Reddit subreddits.
- Converts raw text into smooth, narrated audio.
- Produces polished short videos with dynamic background visuals.
- Offers a seamless pipeline: story scraping to final video output.

## Tech Stack

- **Python**: The backbone for scripting and automation.
- **PRAW**: Pulls Reddit posts and comments via the Reddit API.
- **gTTS**: Generates narration audio with Google Text-to-Speech.
- **FFmpeg (via ffmpeg-python)**: Handles video editing and rendering.
- **MoviePy**: Streamlines video assembly and manipulation.
- **OpenCV (cv2)**: Adds text overlays and simple visual effects.
- **Whisper (OpenAI)**: Provides audio timestamps for syncing or trimming.
- **os/shutil**: Manages file handling and organization.
- **requests**: Fetches background visuals from the web.
- **transformers (Hugging Face)**: Optional story summarization for tighter scripts.

## Setup

*(Coming soon: Instructions for installation, dependencies, and API keys.)*

## Usage

*(Coming soon: Quickstart guide and example commands.)*

## TODOs

- Add configuration for subreddit selection and video styles.
- Implement subtitle generation with Whisper timestamps.
- Optimize video rendering for faster output.
- Expand visual sources (e.g., stock footage APIs).

Contributions welcome! Check out the issues tab for ideas or submit your own.
