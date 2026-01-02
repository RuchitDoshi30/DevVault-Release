# DevVault Landing Page

A simple static landing page for DevVault.

## Deploy to Netlify

1. Go to [netlify.com](https://netlify.com)
2. Sign up/login with GitHub
3. Click "Add new site" → "Deploy manually"
4. Drag and drop this `website` folder
5. Done! Your site is live.

## Deploy to Vercel

1. Go to [vercel.com](https://vercel.com)
2. Sign up/login with GitHub
3. Click "Add New..." → "Project"
4. Choose "Import Third-Party Git Repository" or deploy via CLI:
   ```bash
   npm i -g vercel
   cd website
   vercel
   ```

## Files

- `index.html` - The landing page
- `logo.png` - DevVault logo

## Update Download Links

Before deploying, update these placeholders in `index.html`:
- `YOUR_USERNAME` - Your GitHub username
- `YOUR_LINKEDIN` - Your LinkedIn profile
- `YOUR_TWITTER` - Your Twitter handle (optional)

## Host Download Files

Upload the installers to GitHub Releases:
1. Create a new repo: `github.com/YOUR_USERNAME/DevVault`
2. Go to Releases → "Create a new release"
3. Tag: `v1.0.0`
4. Upload:
   - `DevVault-v1.0.0-Setup.exe`
   - `DevVault-v1.0.0-android.apk`
5. Publish release
