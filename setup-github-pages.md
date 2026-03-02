# GitHub Pages Setup Instructions

## Option 1: Manual Setup (Recommended)

1. **Go to your repository settings:**
   - Visit: https://github.com/Whitehurst87/bog-house-email-newsletter
   - Click on the "Settings" tab

2. **Configure GitHub Pages:**
   - In the left sidebar, click "Pages"
   - Under "Source", select "Deploy from a branch"
   - Choose "main" as the branch
   - Click "Save"

3. **Wait for deployment:**
   - GitHub will process your site
   - You'll see a success message once it's live
   - Your site will be available at: `https://whitehurst87.github.io/bog-house-email-newsletter/`

## Option 2: Using GitHub CLI (if you have it installed)

If you install GitHub CLI in the future, you can run:

```bash
gh api repos/Whitehurst87/bog-house-email-newsletter/pages -f source=main
```

## Verification

After setup, you can verify your site is working by:
1. Visiting the URL: `https://whitehurst87.github.io/bog-house-email-newsletter/`
2. Your `index.html` file should load and display your Bog House Pub newsletter

## Notes

- GitHub Pages deployment usually takes 5-10 minutes
- Your site will be publicly accessible
- The URL format is: `https://[username].github.io/[repository-name]/`
- Your existing `index.html` file is already properly formatted for web display

## Troubleshooting

If you encounter issues:
1. Make sure your `index.html` file is in the root of the repository
2. Check that the file is properly committed and pushed to the main branch
3. Wait a few minutes for GitHub to process the deployment