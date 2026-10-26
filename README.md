# CropRatio

CropRatio is a free, browser-based image cropping tool that lets you crop images using preset or custom aspect ratios, set output dimensions in pixels, and export images in multiple formats.

## Features

- **Image Upload**: Upload images using file selection or drag and drop.
- **Aspect Ratio Presets**: Choose from popular ratios, including 1:1, 4:5, 3:2, 4:3, 16:9, 9:16, 3:4, and 2:3.
- **Custom Aspect Ratio**: Define your own crop ratio.
- **Free Crop Mode**: Resize the crop area freely.
- **Image Editing**: Zoom, rotate, and reset the crop area.
- **Output Dimensions**: Set custom width and height in pixels.
- **Export Formats**: Download images as JPEG, PNG, or WebP.
- **Image Quality**: Adjust export quality for supported formats.
- **Bilingual Interface**: Switch between Indonesian and English.
- **Responsive Design**: Works on desktop and mobile browsers.
- **Client-Side Processing**: Images are processed locally in your browser.

## Getting Started

### Requirements

- A modern web browser.
- An internet connection to load the Cropper.js library from the CDN.

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/cropratio.git
   ```

2. Open the project folder.

   ```bash
   cd cropratio
   ```

3. Open `cropratio.html` in your browser.

You can also download the HTML file and open it directly without installing dependencies.

## How to Use

1. Open CropRatio in your browser.
2. Upload an image or drag and drop it into the workspace.
3. Select an aspect ratio preset or define a custom ratio.
4. Adjust the crop area using the image editor.
5. Set the output width and height in pixels.
6. Choose an export format and adjust the quality if needed.
7. Click **Download Image** to save the cropped image.

## Technologies

- HTML5
- CSS3
- JavaScript
- [Cropper.js](https://github.com/fengyuanchen/cropperjs)

## Privacy

CropRatio processes images directly in the browser. Image files are not uploaded to an application server.

The Cropper.js library is loaded from a third-party CDN, so an internet connection is required for the editor to work when using the standalone HTML file.

## Project Structure

```text
cropratio/
└── cropratio.html
```

## License

Choose a license before distributing the project. If you want others to use, modify, and redistribute your code, consider the MIT License.

---

Built for simple and accessible image cropping.