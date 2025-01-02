# Fullscreen Video

This repository provides a distraction-free fullscreen view of a YouTube video.

## How to Use

Click the link below to view the video in fullscreen mode:

[View Fullscreen Video](https://yizazaza.github.io/jonkler/)

## Embed Code

The video will open in fullscreen mode using the following minimal HTML code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fullscreen Video</title>
    <style>
        body {
            margin: 0;
            overflow: hidden;
        }
        iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: none;
        }
    </style>
</head>
<body>
    <iframe 
        src="https://www.youtube.com/embed/8rbhuml4bi4?autoplay=1&controls=0&modestbranding=1&rel=0&showinfo=0" 
        allow="autoplay; fullscreen">
    </iframe>
</body>
</html>
