Reddit Shorts Generator
A Python-based tool to automatically create short videos (e.g., YouTube Shorts, TikTok) from Reddit stories, using text-to-speech narration and video editing.
Features

    Scrapes compelling stories from Reddit subreddits.
    Converts text into narrated audio.
    Generates short videos with background visuals and optional subtitles.
    Fully automated pipeline from story selection to video output.

Tech Stack

    Python: Core language for scripting and automation.
    PRAW: Fetches Reddit posts and comments via the Reddit API.
    gTTS: Generates narration audio from text using Google Text-to-Speech.
    FFmpeg (via ffmpeg-python): Handles video editing and rendering.
    MoviePy: Simplifies video manipulation and assembly.
    OpenCV (cv2): Adds text overlays or basic visual effects.
    Whisper (OpenAI): Provides audio timestamps for syncing or trimming.
    os/shutil: Manages file operations.
    requests: Downloads background visuals from external sources.
    transformers (Hugging Face): Optional text summarization for concise scripts.
