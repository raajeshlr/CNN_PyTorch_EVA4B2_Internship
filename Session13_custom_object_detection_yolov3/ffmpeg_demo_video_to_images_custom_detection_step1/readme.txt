YouTube Video URL : https://www.youtube.com/watch?v=MPV7JXTWPWI
FFMPEG Download URL : https://www.ffmpeg.org/download.html#build-windows

Choose Windows.
Choose Windows builds by BtbN
Choose ffmpeg-N-102774-g2cf95f2dd9-win64-gpl-shared.zip

Archive, add ffmpeg.ext to env path.

=================================================================
Then open cmd terminal on your directory.

Video to Images - 3 frames per second
---------------------------------------
ffmpeg -i video.mp4 -vf fps=3 out%d.png
---------------------------------------

Images to Video - make sure your images are like img001.jpg, img002.jpg... since we mentioned %03d
---------------------------------------
ffmpeg -f image2 -i img%03d.jpg -vcodec libx264 -b 800k video.avi
---------------------------------------


other commands
ffmpeg -r 60 -f image2 -s 1920x1080 -i pic%04d.png -vcodec libx264 -crf 25  -pix_fmt yuv420p test.mp4
ffmpeg -f image2 -i image%d.jpg -vcodec mpeg4 -b 800k video.avi

