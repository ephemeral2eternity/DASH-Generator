DASH-Generator
==============

This is a collection of tools to generate a DASH video sequences. 

# Libraries
Libraries include:

- [FFMPEG](https://www.ffmpeg.org/)

- [Bento4](http://www.bok.net/trac/bento4/wiki/MpegDash)

# Quick Start

Clone this repository, download an open source video with HD format and follow following steps to generate a set of videos as DASH with its MPD file.

## Transcode the video to mp4 format in multiple bitrates and resolutions.
You need to find a video under open license to publish it on your website. 
1.  Download a HD video with open licence.
Take *Tear of Steel* for example, please download [HD 1920 Pixels Wide Version](http://ftp.nluug.nl/pub/graphics/blender/demo/movies/ToS/ToS-4k-1920.mov).

```
wget http://ftp.nluug.nl/pub/graphics/blender/demo/movies/ToS/ToS-4k-1920.mov
```

2. Transcode the video to mp4 format with supported video encoder in multiple bitrates and resolution.
    1. Choose the resolution and bitrates to encode.

| Profile Level  | Target Bitrate  | Width  | Height  |
|---|---|---|---|
| 1  | 450kbps  | 640  | 360  |
| 2  | 1500kbps  | 1080  | 720  |
| 3  | 3400kbps  | 1920  | 1080  | 





