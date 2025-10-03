# [costacyber.org](https://costacyber.org/)
- Official Website for the Mira Costa Cyber Security Club
- Made with ❤️ by the MCHS Cyber Security Club using: [Bootstrap](https://getbootstrap.com/)

## How to Add Content

### Adding Gallery Images

To add new images to the gallery:

1. Upload your images to the `assets/` folder
2. Edit `gallery.html` and find the `galleryImages` array in the `<script>` section at the bottom
3. Add your images to the array:
   ```javascript
   const galleryImages = [
       { src: 'assets/2023.png', caption: 'Club Photo 2023' },
       { src: 'assets/IMG_001.jpg', caption: 'Your caption here' },
       { src: 'assets/IMG_002.jpg', caption: 'Another caption' }
   ];
   ```

### Adding Presentations

To add presentations:

1. Upload your .pptx files to the `presentations/` folder
2. Edit `presentations.html` and find the `presentations` array in the `<script>` section
3. Add your presentation details:
   ```javascript
   const presentations = [
       {
           filename: 'your-presentation.pptx',
           title: 'Introduction to Cybersecurity',
           date: '2024-01-15'
       }
   ];
   ```

The presentation will automatically appear on the presentations page with a download button.
