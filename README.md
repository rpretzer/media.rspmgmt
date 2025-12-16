# RSP Publishing Website

Website for RSP Publishing - Publishing & Media Sub-brands, Audio Production, and Podcasts.

## Site Information

- **Domain**: media.rspmgmt.com
- **Hosting**: GitHub Pages
- **Status**: Ready for deployment

## Project Structure

```
rsp-publishing/
├── index.html      # Main page
├── styles.css      # Stylesheet
├── README.md       # This file
└── .gitignore      # Git ignore file
```

## Setup Instructions

1. Create a new repository on GitHub (name it as desired)
2. Add the remote repository:
   ```bash
   git remote add origin https://github.com/username/repo-name.git
   ```
3. Add all files:
   ```bash
   git add .
   ```
4. Commit the initial files:
   ```bash
   git commit -m "Initial commit: RSP Publishing website"
   ```
5. Push to GitHub:
   ```bash
   git branch -M main
   git push -u origin main
   ```
6. Enable GitHub Pages:
   - Go to repository Settings > Pages
   - Select source branch (usually `main`)
   - Select folder (usually `/ (root)`)
   - Save

## Custom Domain Setup

The DNS record is already configured at Squarespace pointing to media.rspmgmt.com. After enabling GitHub Pages:

1. Add a `CNAME` file in the repository root with the content: `media.rspmgmt.com`
2. Configure the custom domain in GitHub Pages settings
3. Wait for DNS propagation (can take up to 24 hours)

## Development

To work on this site locally:

1. Clone the repository
2. Open `index.html` in a web browser
3. Make changes and test locally
4. Commit and push changes

## License

© 2024 RSP Publishing. All rights reserved.

