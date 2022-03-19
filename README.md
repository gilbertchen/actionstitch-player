# ActionStitch Player

This is an in-browser video player that can play 180&deg; cylindrical videos such as those created by [ActionStitch](https://actionstitch.com).

[Demo](https://actionstitch.com/play.html?src=https://download.actionstitch.com/full-demo.mp4)


## Usage

To use this player, upload the file `play.html` to a cloud storage service so that it can be public accessible in the browser.  Then append the url to the video file that you want to open in this form:

```
https://example.com/play.html?src=https://video_url
```

You can also store `play.html` locally to open on-disk video files:

```
file:///Users/username/Downloads/play.html?src=file:///path/to/video
```

You may need to give the browser the access to local files first.  For example, on macos you should run this command to start Chrome:

```
open /Applications/Google\ Chrome.app/ --args --allow-file-access-from-files
```

It is recommended to open this player in the latest version of Chrome on a desktop computer.  Other browsers may work too, but not all functionalities are compatible.

## Controls

- Mouse
  - Left click: play/pause
  - Right click: fast forward 5 seconds
  - Scroll: zoom in/out
  - Move with left button pressed: pan/tilt
- Keyboard
  - Left arrow: rewind 5 seconds
  - Right arrow: fast forward 5 seconds
  - Up arrow: step backward
  - Down arrow: step forward
  - Space: pause/resume
  - Enter: adjust zoom to match native resolution (flat view only)

## Perspective Mode

You can enable the perspective mode by clicking the ![perspective view](img/perspective-view-white.png) button on the bottom control bar.
This mode provides a more realistitc view as if you're watching the field through a pan/tilt/zoom camera.
You can also adjust a few viewpoint parameters using the sliding controls on the top right corner.
