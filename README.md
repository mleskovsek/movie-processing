# movie-processing
FFmpeg script to reduce size, improve loudness, and convert to H.264 AAC for broad compatibility.

What the script does

This script searches the current folder and its subfolders for movie files (".mp4", ".mkv", ".mov", and ".avi").

- Video files are processed with FFmpeg and saved as new files inside a "processed" folder, preserving the original folder structure.
- The processed videos are resized, compressed, converted to H.264/AAC, and have their audio adjusted for better loudness and broad compatibility.
- Other files, such as subtitles, notes, and torrent files, are copied unchanged to the corresponding locations inside the "processed" folder.
- Original files are not modified.