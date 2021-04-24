# FFMPEG batch remux

Simple script for batch muxing/merging of video and audio files.
This script replacing original audio tracks with external audio files.
___________________


# Requirements:
FFMPEG
___________________


# Usage:

-  (script arg1 arg2)  
-  arg1 = path to video files folder
-  arg2 = path to audio files folder
-  arg3 (unnecessary) = additional ffmpeg arguments
+   /bin/remux    /path-to-video_files    /path-to-audio_files


# Important:

Merged files will be stored in "remuxed" folder under original video files folder.

!!! Same Video and Audio file names are necesary !!!
