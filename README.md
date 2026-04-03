ninholoader
A lightweight, portable media downloader built on top of yt-dlp and ffmpeg. Designed for simplicity, speed, and ease of use on Windows.

Features
Portable: No installation required. Just run it from any folder.

Format Flexibility: Easily switch between high-quality video or audio-only (MP3) downloads.

Duplicate Detection: Automatically skips files that have already been downloaded.

Clean UI: Minimalist command-line interface with custom ASCII branding.


Installation:
1. Download the archive
2. Unzip the folder
3. Run setup_tools.bat
   It will create a system tools folder with the required yt-dlp and ffmpeg.
4. Launch ninholoader.bat
5. You are ready to go!

Prerequisites
To use this downloader, ensure the following are in your System tools folder:

yt-dlp

ffmpeg (binaries in System tools\ffmpeg\bin)

Folder Structure
To ensure the script works correctly, keep your directory organized like this:

Plaintext
ninholoader/
├── ninholoader.bat
└── System tools/
    ├── yt-dlp.exe
    └── ffmpeg/
        └── bin/
            ├── ffmpeg.exe
            └── ffprobe.exe
Usage
Double-click ninholoader.bat.

Paste the video link when prompted.

Select your desired format (1 for Video, 2 for Audio).

Your file will be saved automatically to your Downloads folder.

License
This project is for educational and personal use. Please respect the Terms of Service of the platforms you download from.
