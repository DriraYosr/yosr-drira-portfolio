# Image Guide for Your Portfolio Website

## 📁 File Structure
Place all images in the same folder as `index.html`:
```
recherche_taf/
├── index.html
├── myphoto.jpg (your profile photo)
├── criteo-logo.png
├── inexbet-logo.png
├── project-feedback-analyzer.png
├── project-music-therapy.png
└── project-satellite.png
```

## 🏢 Company Logos

### Criteo Logo
- **Filename:** `criteo-logo.png`
- **Recommended size:** 200x200 pixels (or any square format)
- **Where to find:** 
  - Official Criteo website: https://www.criteo.com/
  - Google Images: search "Criteo logo PNG transparent"
  - Or take a screenshot from their website

### INEX BET Logo
- **Filename:** `inexbet-logo.png`
- **Recommended size:** 200x200 pixels (or any square format)
- **Where to find:** 
  - Company website or LinkedIn page
  - Google Images: search "INEX BET logo"
  - Or ask your contact at the company

## 📸 Project Screenshots

### Project 1: Customer Feedback Analyzer
- **Filename:** `project-feedback-analyzer.png` or `.jpg`
- **What to capture:**
  - Dashboard with sentiment analysis visualizations
  - Charts showing trends over time
  - Example of aspect-based analysis results
  - The most impressive/colorful part of your interface
- **Recommended size:** 1200x800 pixels (landscape)

### Project 2: Music Therapy Recommender
- **Filename:** `project-music-therapy.png` or `.jpg`
- **What to capture:**
  - Streamlit app interface
  - Recommendation results
  - Performance metrics dashboard
  - User assessment interface
- **Recommended size:** 1200x800 pixels (landscape)

### Project 3: Satellite Imagery Analysis
- **Filename:** `project-satellite.png` or `.jpg`
- **What to capture:**
  - Satellite images with analysis overlay
  - Time series visualization
  - Map showing dump site locations
  - Before/after comparison
- **Recommended size:** 1200x800 pixels (landscape)

## 🎨 Image Tips

### For Company Logos:
1. **Use transparent backgrounds** (PNG format) if possible
2. Keep them **professional** and **official**
3. Make sure they're **high resolution** (not pixelated)
4. Square format works best (the CSS will handle resizing)

### For Project Screenshots:
1. **Take full-screen screenshots** for best quality
2. **Clean up the interface** before capturing:
   - Close unnecessary browser tabs
   - Hide personal information
   - Make sure data is presentable
3. **Highlight key features** - show your best work
4. **Use good lighting** if it's a dark/light theme toggle
5. **Consider adding annotations** (arrows, highlights) using tools like:
   - Snagit
   - Greenshot
   - Paint / Paint.NET
   - Photoshop

## 🖼️ Profile Photo Tips

Update the profile photo reference in `index.html`:
- Change `src="your-image.jpg"` to `src="myphoto.jpg"` (or whatever you name it)
- **Professional headshot** recommendations:
  - Good lighting
  - Professional attire
  - Neutral background
  - Smiling and approachable
  - Square aspect ratio (500x500px minimum)

## 🔧 Quick Fixes

### If an image doesn't show up:
1. ✅ Check the filename matches exactly (case-sensitive)
2. ✅ Check the file is in the same folder as index.html
3. ✅ Check the file extension (.png vs .jpg)
4. ✅ Try refreshing the browser (Ctrl+F5)

### If logos look stretched:
- The CSS is set to `object-fit: contain` which prevents stretching
- Just make sure your logos are square-ish

### If project images are too large:
- They're set to max-width: 600px and will scale responsively
- You can resize them before adding to save loading time

## 🎯 Alternative: Using Placeholder Services

If you don't have images yet, you can test with placeholders:

```html
<!-- For logos -->
<img src="https://via.placeholder.com/200x200/667eea/ffffff?text=Criteo" alt="Criteo">

<!-- For project images -->
<img src="https://via.placeholder.com/1200x800/667eea/ffffff?text=Project+Screenshot" alt="Project">
```

## 📊 Recommended Tools

### For Screenshots:
- **Windows:** Snipping Tool (Win + Shift + S)
- **Professional:** Snagit, ShareX
- **Mac:** Command + Shift + 4

### For Image Editing:
- **Basic:** Paint.NET (free)
- **Advanced:** GIMP (free), Photoshop
- **Online:** Canva, Photopea

### For Compression:
- TinyPNG.com (reduces file size)
- Squoosh.app (Google's image optimizer)

## ✅ Final Checklist

Before deploying:
- [ ] Profile photo added and displays correctly
- [ ] Criteo logo added (60x60px display size)
- [ ] INEX BET logo added (60x60px display size)
- [ ] All 3 project screenshots added
- [ ] All images are clear and professional
- [ ] File sizes are optimized (< 500KB per image)
- [ ] Test on mobile view to ensure images look good
- [ ] All images have descriptive alt text (already done in HTML)

---

**Note:** The website uses `onerror="this.style.display='none'"` which means if an image is missing, it will simply hide that element rather than showing a broken image icon. This allows you to add images gradually!
