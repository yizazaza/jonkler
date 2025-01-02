# Fullscreen Video Example (Cropped)

This repository demonstrates how to play a YouTube video in fullscreen mode with no title or controls, cropped to remove unwanted UI elements.

## Fullscreen Video Link
Click the link below to watch the cropped fullscreen video:

[▶ Watch Cropped Fullscreen Video](https://www.youtube.com/embed/db6QIx11vMA?autoplay=1&controls=0&showinfo=0&modestbranding=1&rel=0&iv_load_policy=3)

## Cropped Embed Example
To display the video cropped with 20% removed from the edges, use this code:

```html
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
    <iframe 
        src="https://www.youtube.com/embed/db6QIx11vMA?autoplay=1&controls=0&showinfo=0&modestbranding=1&rel=0&iv_load_policy=3" 
        allow="autoplay; fullscreen" 
        allowfullscreen 
        style="position: absolute; top: -10%; left: -10%; width: 120%; height: 120%; border: none;">
    </iframe>
</div>
```

## About
The video is embedded using YouTube's embed URL with parameters to:
- **Autoplay** the video.
- Hide as much UI as possible (e.g., controls, branding, annotations).
- Adjust the video frame to crop 20% from the edges for a cleaner view.
