# SheetChat GitHub Pages Site

This repository contains the GitHub Pages site for SheetChat, required for Google OAuth verification.

## Deployment Instructions

1. **Create a new GitHub repository:**
   ```bash
   # Create a new repository on GitHub named 'sheetchat'
   # Then upload these files to the repository
   ```

2. **Enable GitHub Pages:**
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

3. **Your site will be available at:**
   ```
   https://[yourusername].github.io/sheetchat
   ```

## Files Included

- `index.html` - Homepage for SheetChat
- `privacy.html` - Privacy Policy (required for Google OAuth)
- `terms.html` - Terms of Service (required for Google OAuth)

## For Google OAuth Consent Screen

Use these URLs in your Google Cloud Console:

- **Application home page:** `https://[yourusername].github.io/sheetchat`
- **Application privacy policy link:** `https://[yourusername].github.io/sheetchat/privacy.html`
- **Application terms of service link:** `https://[yourusername].github.io/sheetchat/terms.html`
- **Authorized domains:** `[yourusername].github.io`

Replace `[yourusername]` with your actual GitHub username.

## Notes

- The site is designed to be minimal and professional
- All required legal pages are included
- The design matches Google's material design principles
- Contact email is set to evillain667@gmail.com as specified

After deployment, update your Google OAuth consent screen with the live URLs.