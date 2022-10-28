# ASCII Player

This player plays a video on the terminal using ascii characters.

## Usage

```
python3 player.py <video or video input device index>
```

The player uses 120 characters as default width. This can be changed using the `--width` flag. The height is calculated to preserve the aspect ratio.

The default framerate is 30 fps. This can also be changed using the `--fps` flag. If it's set too high it will just go as fast as it can.

You can choose to display the original video with `opencv` with `--show true`

You can also choose to invert the shades of the ascii video with `--inv true`
