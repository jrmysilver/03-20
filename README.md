# JPEG to Base64 Converter

A simple, web-based tool to convert JPEG images to Base64 format for embedding in websites.

## Features

- 📸 **Upload JPEG Images** - Drag & drop or click to upload
- 👁️ **Image Preview** - See your image before conversion
- 🔄 **Convert to Base64** - One-click conversion
- 📋 **Copy to Clipboard** - Easy copy functionality
- 🌐 **Web Ready** - Output is a complete data URI for HTML

## How to Use

1. **Upload a JPEG** - Click the file input or drag & drop your image
2. **Preview** - Your image will display for verification
3. **Convert** - Click "Convert to Base64"
4. **Copy** - Click the output to copy to clipboard
5. **Use** - Paste directly into your HTML or website code

## Output Format

The converter produces a complete data URI:

```
data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAA...
```

## HTML Usage

```html
<img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/..." alt="My Image" />
```

## Installation

1. Clone or open this repository
2. Open `index.html` in your web browser
3. Or enable GitHub Pages for online access

## Files

- `index.html` - Main converter interface
- `style.css` - Styling and responsive design
- `README.md` - This file

## Browser Support

- Chrome/Edge
- Firefox
- Safari
- Any modern browser with FileReader API support

## License

Public domain