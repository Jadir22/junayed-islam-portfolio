# Junayed Islam - Professional E-Portfolio

Responsive professional E-Portfolio website built with HTML, CSS, and JavaScript.

## How to add the self-introduction video

### YouTube Unlisted (recommended)
1. Upload your 1-2 minute video to YouTube.
2. Set visibility to Unlisted.
3. Copy the video ID.
4. Open `index.html` and find the `Video Introduction` section.
5. Replace the placeholder `div` with:

```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" title="Self Introduction Video" allowfullscreen></iframe>
```

### Direct MP4
1. Rename your video file to `intro-video.mp4`.
2. Put it inside the `assets` folder.
3. Replace the placeholder `div` in the video section with:

```html
<video controls poster="assets/profile-full.jpg">
  <source src="assets/intro-video.mp4" type="video/mp4">
</video>
```

## GitHub Pages hosting
1. Create a public GitHub repository named `portfolio`.
2. Upload all files and folders from this project.
3. Go to repository Settings > Pages.
4. Source: Deploy from a branch.
5. Branch: main, folder: /root.
6. Save.
7. Your site will be live at `https://Jadir22.github.io/portfolio/`.
