# Fullscreen YouTube Video Viewer

This repository provides a distraction-free, fullscreen view of a YouTube video. Click the link below to watch the video without borders or distractions.

## View the Video

[View Fullscreen Video](https://yizazaza.github.io/jonkler/)

## About

This project uses a simple HTML file to embed the YouTube video in fullscreen mode, hiding all unnecessary YouTube elements.

## How It Works

The `index.html` file includes the following code:

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
        src="https://www.youtube.com/embed/8

