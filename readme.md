# Simple HTML CSS Javascript video player

[Demo link](https://angel-del-dev.github.io/vanilla-videoViewer/)

# Download and add your videos:

1. Clone the repository 
```git
git clone https://github.com/Angel-del-dev/vanilla-videoViewer.git
```
2. Add your video
    * Change the video in `/video` and (when using the .bat file)rename it to `example.mp4` or change it in the code(`video` tag).
3. Creating the video thumbnails
    * The file `ffmpeg.bat` contains a command to generate a picture every 10 seconds of a given video(it is set to look for `example.mp4`)
        * Make sure you have ffmpeg installed
        * Empty the folder `/assets/previewImgs` before executing the command.
4. Adding your own Captions
    * Modify the file `/assets/subtitles.vtt` with your own timestamps

# Using the video player

* Play/Pause:
    * Click in the player
    * Pressing `spacebar`
    * Pressing `k`
* Skip 5 seconds:
    * Backwards:
        * Pressing `j`
        * Pressing `left arrow`
    * Forwards:
        * Pressing `l`
        * Pressing `right arrow`
* Theater mode:
    * Clicking the icon
    * Pressing `t`
* Mini player mode:
    * Clicking the icon
    * Pressing `i`
* Restarting the video:
    * Pressing `0`
* Toggling mute:
    * Clicking the icon
    * Pressing `m`
* Toggling captions:
    * Clicking the icon
    * Pressing `c`
* Toggling fullscreen:
    * Clicking the icon
    * Pressing `f`
