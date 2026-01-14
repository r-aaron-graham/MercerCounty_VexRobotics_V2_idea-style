# 🚀 Quick Start Guide

## Get Up and Running in 5 Minutes!

### Step 1: Extract the Files
```bash
# Extract the downloaded package
tar -xzf mercer-vex-website-complete.tar.gz
cd mercer-vex-website
```

### Step 2: Open in Browser
**Option A - Simple (Double-click)**
- Find `index.html`
- Double-click to open in your default browser

**Option B - Local Server (Recommended)**
```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js
npx serve

# Then visit: http://localhost:8000
```

### Step 3: Start Customizing!

#### Change Content (5 minutes)
1. Open `index.html` in a text editor
2. Find text you want to change
3. Edit and save
4. Refresh browser

#### Update Videos (2 minutes)
1. Get YouTube video ID from URL: `youtube.com/watch?v=VIDEO_ID_HERE`
2. Find `data-video-id="OLD_ID"` in `index.html`
3. Replace with your video ID
4. Save and refresh

#### Change Colors (3 minutes)
Colors are in the `<style>` section of `index.html`:
```css
:root {
  --primary-gold: #FFD700;    /* Your primary color */
  --vex-red: #E63946;          /* Your accent color */
}
```

#### Replace Logo (1 minute)
1. Place your logo in `images/` folder as `logo.png`
2. Recommended size: 500x500px PNG
3. Refresh browser

### Step 4: Deploy to Web

#### GitHub Pages (Free, 10 minutes)
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main
```
Then enable GitHub Pages in repository settings.

#### Netlify (Free, 5 minutes drag & drop)
1. Go to app.netlify.com/drop
2. Drag the entire folder
3. Done! You get a live URL instantly.

### Common First Tasks

#### Update Team Statistics
Find in `index.html`:
```html
<span class="stat-number">150+</span>
<span class="stat-label">Active Students</span>
```
Change numbers as needed.

#### Add New Achievement
Copy this template and paste in achievements section:
```html
<div class="achievement-card">
  <div class="achievement-icon">🏆</div>
  <h4>Your School Name</h4>
  <div class="achievement-title">Award Title</div>
  <p>Description of achievement here.</p>
</div>
```

#### Update Contact Info
Find near bottom of `index.html`:
```html
<a href="mailto:your-email@school.com">your-email@school.com</a>
<a href="tel:123-456-7890">(123) 456-7890</a>
```

### Need More Help?
- 📖 Full documentation: See `README.md`
- 🐛 Issues: Check browser console (F12)
- 📧 Contact: robotics@merc.k12.wv.us

### File Structure
```
mercer-vex-website/
├── index.html          ← Main file (edit this!)
├── README.md           ← Full documentation
├── QUICK_START.md      ← This file
└── images/
    └── logo.png        ← Your logo here
```

### Pro Tips
1. **Test on Mobile** - Use Chrome DevTools (F12 → Device Toolbar)
2. **Backup Before Editing** - Copy `index.html` to `index-backup.html`
3. **Use Find & Replace** - Ctrl+F in text editor to update repeated content
4. **Compress Images** - Use tinypng.com before adding to site
5. **Check Validation** - validator.w3.org for error checking

### Troubleshooting

**Logo not showing?**
- Check filename is exactly `logo.png` (lowercase)
- Ensure it's in the `images/` folder
- Try clearing browser cache (Ctrl+Shift+R)

**Mobile menu not working?**
- Make sure you didn't accidentally delete the `<script>` section
- Check browser console for errors (F12)

**Videos not playing?**
- Verify video is set to "Public" on YouTube
- Double-check video ID is correct
- Try in a different browser

### Ready to Go!
Your website is ready to use right now. All the content about Mercer County Schools is already in place - just update with your latest information and deploy!

**Questions?** Read the full `README.md` for complete documentation.
