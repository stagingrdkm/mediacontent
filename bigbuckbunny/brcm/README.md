# mediacontent under bigbuckbunny

This is a series of fragments of about 30 seconds, based on unmodified original content converted to TS format. Also video and audio has been re-encoded to use different codec.
Input source used was: https://mirrors.dotsrc.org/blender/blender-demo/movies/BBB/bbb_sunflower_1080p_30fps_normal.mp4

## How converted?
ffmpeg -y -i part0130-0200.mp4 -c:v libx264 -preset medium -c:a aac sample1.ts
ffmpeg -y -i part0130-0200.mp4 -c:v libx264 -preset medium -c:a aac -muxrate 5M brcm/sample1.ts

## Copyright
(c) copyright 2008, Blender Foundation / www.bigbuckbunny.org

## License
Creative Commons Attribution 3.0
https://creativecommons.org/licenses/by/3.0/
https://creativecommons.org/licenses/by/3.0/legalcode
(copy in LICENSE file)
