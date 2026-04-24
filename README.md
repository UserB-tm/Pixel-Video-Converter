# Pixel Video Converter

A simple tool that converts Google Pixel HEVC videos to MP4, ensuring broader compatibility with Windows apps and devices. This app is designed to be portable, i.e., you can copy the contents of this repo to a USB drive, a folder on your computer, or where ever, and run `Pixel Video Converter.exe`. 

## How to use

1. **Get the App**:
   - Click the green **Code** button at the top right of this page.
   - Select **Download ZIP**.
   - Once downloaded, open the ZIP file and drag the contents to a folder on your computer (like your Desktop or Documents).

2. **Run the app**: Double-click `Pixel Video Converter.exe`.

3. **Select your video**: The app will prompt you to browse for a video file to convert.

4. **Wait for conversion**: The app re-encodes your video in the background.

5. **Choose save location**: After conversion completes, the app will ask where to save the file and what to name it.

The app automatically remembers the location of `ffmpeg.exe` after the first run, so no additional setup is needed.

## What it does

- Converts Google Pixel HEVC video to H.264 video codec
- Converts audio to AAC format for maximum Windows compatibility
- Works from a USB drive or local installation
- No installation required—just run the `.exe`

## Windows SmartScreen warning

You may see a Windows SmartScreen warning when running the app for the first time. This is normal for unsigned portable applications. Click "More info" and then "Run anyway" to proceed.

## Technical details

**Video codec**: H.264  
**Audio codec**: AAC (192 kbps)  
**Output format**: MP4 with optimizations for quick playback start

## License notes

This folder includes `ffmpeg.exe` and related files. Make sure to include the corresponding ffmpeg license files with any distribution.
