# Figma Design Review & Annotation Tool

A simple HTML tool for reviewing Figma designs with annotation and note-taking capabilities.

## Features

- **Figma Embed**: Easily embed any Figma design using the embed URL
- **Drawing Tools**: Circle, highlight, or mark items you're interested in
- **Notes Panel**: Add detailed notes and feedback
- **Customizable Drawing**: Change color, size, and opacity of annotations
- **Export Options**: 
  - Export all annotations and notes as JSON
  - Save canvas drawings as PNG image
- **Mobile-Friendly**: Touch support for tablets and mobile devices

## How to Use

1. **Get Your Figma Embed URL**:
   - Open your Figma file
   - Click "Share" → "Get embed code"
   - Copy the URL from the iframe src attribute
   - Example: `https://www.figma.com/embed?embed_host=share&url=https://www.figma.com/file/...`

2. **Open the Tool**:
   - Open `index.html` in your web browser
   - Or deploy it to any web hosting service

3. **Load Your Design**:
   - Paste the Figma embed URL in the input field
   - Click "Load Figma"

4. **Annotate**:
   - Click "Start Drawing" to enable drawing mode
   - Choose your color and line size
   - Draw circles or highlights over items you want
   - Toggle opacity for see-through annotations

5. **Add Notes**:
   - Type your notes in the text area on the right
   - Click "Add Note" to save
   - Delete notes if needed

6. **Export**:
   - Click "Export Annotations & Notes" to download a JSON file with all your feedback
   - Click "Save Canvas as Image" to download just the drawings

## Technical Details

- Pure HTML, CSS, and JavaScript (no dependencies)
- Works offline once loaded
- Canvas-based drawing system
- Responsive design

## Getting Started

Simply open `index.html` in any modern web browser. No build process or installation required!
