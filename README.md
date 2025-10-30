# Lumen GI - Marketing & Privacy Pages

This repository hosts the marketing landing page and privacy policy for **Lumen GI**, a privacy-first IBS and IBD symptom tracking app for iOS.

## 📁 Files

- **`index.html`** - Marketing landing page with app features and download link
- **`privacy.html`** - Privacy policy page for App Store Connect compliance

## 🚀 GitHub Pages Setup

### Initial Setup

1. **Enable GitHub Pages:**
   - Go to your repository: https://github.com/usmanplusone/lumen-gi
   - Navigate to **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Choose branch: `main` (or `master`)
   - Choose folder: `/ (root)`
   - Click **Save**

2. **Wait for Deployment:**
   - GitHub will build and deploy your site automatically
   - This usually takes 1-2 minutes
   - You'll see a message: "Your site is live at https://usmanplusone.github.io/lumen-gi/"

3. **Verify the URLs:**
   - Marketing page: https://usmanplusone.github.io/lumen-gi/
   - Privacy policy: https://usmanplusone.github.io/lumen-gi/privacy.html

### App Store Connect Setup

Once GitHub Pages is live, add these URLs to App Store Connect:

1. **Privacy Policy URL:**
   ```
   https://usmanplusone.github.io/lumen-gi/privacy.html
   ```

2. **Marketing URL (optional):**
   ```
   https://usmanplusone.github.io/lumen-gi/
   ```

### Testing Before Submission

Before submitting to App Store Connect, verify:

- [ ] Both URLs load properly on iPhone Safari
- [ ] Both URLs load properly on desktop browsers
- [ ] Dark mode works correctly
- [ ] All links work (no 404 errors)
- [ ] Privacy policy email is correct: lumengiapp@gmail.com
- [ ] Privacy policy "Last Updated" date is current
- [ ] App Store download link is updated (currently placeholder)

## 📝 Updating Content

### Update Privacy Policy

Edit `privacy.html` and update:
- The "Last Updated" date in the header
- Any changed policy sections
- Commit and push - GitHub Pages auto-deploys

### Update Marketing Page

Edit `index.html` to:
- Update the App Store download link (replace placeholder)
- Add screenshots or app preview images
- Modify features or messaging
- Commit and push - GitHub Pages auto-deploys

### Update App Store Link

In `index.html`, find this line:
```html
<a href="https://apps.apple.com/app/lumen-gi" class="cta-button">Download on App Store</a>
```

Replace with your actual App Store URL:
```html
<a href="https://apps.apple.com/us/app/lumen-gi/idYOUR_APP_ID" class="cta-button">Download on App Store</a>
```

## 🎨 Customization

Both HTML files use inline CSS for:
- Fast loading (no external dependencies)
- Apple-style design system
- Automatic dark mode support
- Mobile-first responsive design
- WCAG 2.1 AA accessibility

Feel free to customize colors, fonts, or layout by editing the `<style>` section in each file.

## 📧 Support

For questions about the app or privacy policy:
- Email: lumengiapp@gmail.com
- Website: https://usmanplusone.github.io/lumen-gi/

## 📄 License

© 2025 Lumen GI. All rights reserved.
