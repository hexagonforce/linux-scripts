# linux-scripts

A set of convenience scripts for multimedia tasks. These scripts have been tested in Fedora 38 and Arch Linux 2023.09 with SwayWM.

## compress_webp

Compresses an animated webp file by first converting it to a video, then converting the video back to an animated webp file.

Requirements: libwebp, exiftool

## cpcompile

Convenience script for compiling C++ source files for competitive programming.

Requirements: g++ with AddressSanitizer, UBSan

## download_music

Downloads the audio from a list of YouTube URLs specified in a text file.

## giftowebp, mp4towebp

Converts animated GIF files and MPEG-4 files to animated WEBP files.

Requirements: ffmpeg

## youtube-watch

Convenience function for watching YouTube URLs copied in the Wayland clipboard in mpv.

Requirements: mpv, wl-clipboard
