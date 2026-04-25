# Portfolio.me

A simple HTML-based portfolio with embedded video links showcasing your projects.

## Features

- 📹 Embedded YouTube video player
- 📱 Fully responsive design
- 🎨 Modern gradient design with smooth animations
- ⚡ Fast and lightweight
- 🔗 Easy to customize with your video links

## How to Use

1. **Replace Video IDs**: Open `index.html` and replace `VIDEO_ID_1`, `VIDEO_ID_2`, and `VIDEO_ID_3` with your actual YouTube video IDs.
   - You can find the video ID in the YouTube URL: `https://www.youtube.com/watch?v=VIDEO_ID_HERE`

2. **Update Project Descriptions**: Edit the project titles and descriptions in the video cards.

3. **Customize Styling**: Modify `style.css` to change colors, fonts, and layout.

## Adding More Videos

To add additional video projects, duplicate this code block in the `.video-container` div:

```html
<div class="video-card">
    <h3>Project Name</h3>
    <iframe width="100%" height="315"
        src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
        title="Project Demo"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
    </iframe>
    <p>Description of your project here</p>
</div>
```

## File Structure

```
Portfolio.me/
├── index.html          # Main portfolio page
├── style.css           # Styling
└── README.md           # Documentation
```

## Deployment

You can deploy this portfolio for free using:
- **GitHub Pages**: Enable in repository settings
- **Netlify**: Drag and drop the files
- **Vercel**: Connect your GitHub repo
- **Any web host**: Simple FTP upload

## Customization Tips

- Change the gradient colors in `style.css` (line 12)
- Adjust card sizes by modifying `grid-template-columns` (line 49)
- Update header text and description
- Add your contact information

## License

Feel free to use this template for your portfolio!

---

Made with ❤️ by Rhmanmirza
