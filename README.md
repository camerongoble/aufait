# aufait
## "related to, as an aside"

A script to remind you of useful commands from your bash history and to encourage system exploration.

Depends on apropos, grep, cut, and sed.

# Usage:
aufait [OPTION...] KEYWORDS

OPTIONS are passed to apropos.  See 'apropos --help' for details.

# Example:
```
> aufait video

Available on your system:
amdgpu (4)           - AMD RADEON GPU video driver
ati (4)              - ATI video driver
cheese (1)           - tool to take pictures and videos from your webcam
dvdunauthor (1)      - Decodes DVD-Video file structure
fbdev (4)            - video driver for framebuffer device
ffmpeg-all (1)       - ffmpeg video converter
ffmpeg-scaler (1)    - FFmpeg video scaling and pixel format converter
...

In your recent command history:
ffmpeg (1)           - ffmpeg video converter
ghb (1)              - versatile DVD ripper and video transcoder
lutris (1)           - video game preservation platform
```
