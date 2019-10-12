# blender-FallGuy

The Fall Guy Production Logo Animation

`FallGuy.blend`

## Previews...

![Preview picture](Samples/FallGuy-1.png "Preview Picture of Fall Guy Logo...")

## Rendered Animation...

![Click here for file link and choose display raw there...](Samples/FallGuySample.mp4 "Rendered animation sample...")

## How to convert rendered animation images to a movie

* Render the animation to ./RenderResult/0001.png ...etc...
* Go there...
* Use ffmpeg to convert the PNGs to mp4

Example:

`ffmpeg -r 24 -i %04d.png -vcodec libx264 -crf 25  -pix_fmt yuv420p RenderResult.mp4`

