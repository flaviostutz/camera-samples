# camera-samples
Camera samples for algorithm development

## Tips

* Grabbing MJPG feed samples

  * Discover camera mjpg URL feed
  * Save video feed using ```wget -O test.mjpg http://87.57.111.162/mjpg/video.mjpg```
  * Convert to MP4 (saves 4x storage) using ```ffmpeg -i test.mjpg test.mp4```
  * Setup desired framerate: ```ffmpeg -r 2 -i test.mp4 -r 2 testb.mp4```
  * Move mp4 file to "videos" folder with a good name

