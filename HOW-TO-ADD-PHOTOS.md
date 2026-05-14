# How to Add Your Photos & Video

## Folder Structure
```
woodug-website/
├── index.html
└── images/
    ├── woodug-portrait.jpg      ← Your portrait photo (About section)
    ├── hapkido-poster.jpg       ← Video thumbnail for Hapkido section
    ├── hapkido-demo.mp4         ← Your Hapkido video file
    ├── paypal-qr.jpg            ← PayPal QR code screenshot
    └── gallery/
        ├── clifton-bridge.jpg
        ├── bristol-harbour.jpg
        ├── ss-great-britain.jpg
        ├── cabot-tower.jpg
        ├── bristol-museum.jpg
        ├── big-ben-night.jpg
        ├── parliament.jpg
        ├── avon-gorge.jpg
        ├── bristol-colorful.jpg
        ├── sunset-silhouette.jpg
        ├── countryside.jpg
        └── coffee.jpg
```

## Steps

1. **Portrait photo** → save as `images/woodug-portrait.jpg`
2. **PayPal QR** → screenshot the QR code image → save as `images/paypal-qr.jpg`
3. **Hapkido video** → save as `images/hapkido-demo.mp4`  
   (Or use a YouTube embed — edit the `<video>` tag in index.html and replace with an `<iframe>`)
4. **Gallery photos** → save each travel photo with the matching filename in `images/gallery/`

## Using a YouTube Video Instead of a Local File

In `index.html`, find the `<video>` tag and replace it with:
```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" allowfullscreen></iframe>
```
