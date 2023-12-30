# fooocus-viewer
A simple viewer for Fooocus logs.

![275327017-22d2166b-6b88-4ca7-9c7c-0e9839efb72a](https://github.com/sngazm/fooocus-viewer/assets/4480229/75a772dc-f7fd-4ce0-98b7-6161f61ba8e2)



## Features

- One HTML file. no additional backend, no npm install (it loads React and others from CDN)
- Quick date switching
- Auto reload new image (if today)
- Group images by "Batch" of image generation
- Show Diff with prompts from previous batch
- Sort images (newest first, oldest first)
- Mobile friendly
- Can choose how many images to load at once (important for mobile users like me)
- Easy grid resizing

If you place the attached `viewer.html` under the `output` directory, you can use the viewer by accessing
it on the local server like http://localhost:7865/file=outputs/viewer.html . Of course it doesn't send any data to outside.

For more advanced users, use [Fooocus-Log-Viewer](https://github.com/toutjavascript/Fooocus-Log-Viewer) .
