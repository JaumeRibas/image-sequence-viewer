# image-sequence-viewer
Extremely rough and simple single-page app to 'play' a sequence of images as if it where a video.

The images must be all in the same folder and have a consistent name with a numeric index without leading zeros. The name cannot contain any digits after the image index as the last integer in the name is assumed to be the index.

## Download

[image-sequence-viewer.html](https://github.com/JaumeRibas/image-sequence-viewer/releases/download/v1.0.0/image-sequence-viewer.html)

## How to use

1. Download the `image-sequence-viewer.html` file and double click on it to open it up.
2. Click on the `Load` input to open up the file explorer.
3. Navigate to the folder containing the sequence of images.
4. Once on the desired folder, before selecting any image, copy the path of the folder to the clipboard. How to do this will depend on your system (e.g. clicking the file explorer's address bar, opening up the properties of one of the images, etc.)
5. Select the first image of the sequence to be 'played'.
6. Paste the previously copied folder path to the `Path` input.
7. Click the `Play/Pause` button.

The mouse can be used to pause or resume playback, by right clicking; or for panning, if the images are larger than the window, by holding down the left button.
The left an right arrow keys can be used, while the playback is paused, to move to the previous and next image.

The browser's built-in zooming function can be used to zoom in to a particular area of the image playback.
