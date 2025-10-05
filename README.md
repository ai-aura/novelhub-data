# 📚 Urdu Novel Online Reader

A beautiful, modern, and feature-rich online PDF reader designed specifically for Urdu novels. Perfect for integration with Blogger websites.

## ✨ Features

### 🎨 Modern UI Design
- **Glassmorphism** design with blur effects
- Smooth animations and transitions
- Dark/Light mode support
- Mobile-responsive layout

### 📖 Reading Features
- PDF rendering with Mozilla PDF.js
- Page navigation (Previous/Next)
- Zoom controls (In/Out/Fit to Width)
- Keyboard shortcuts support
- RTL (Right-to-Left) layout for Urdu

### ⚙️ Customization
- Three background colors (White/Sepia/Dark)
- Theme persistence with localStorage
- Fullscreen mode
- PDF download option

### 💰 Monetization
- Automatic ad display after every 20 pages
- Exit confirmation with ad display
- Non-intrusive ad integration

## 🚀 Quick Start

### Step 1: Upload Your PDF
Upload your Urdu novel PDF to GitHub:
```
https://github.com/YOUR_USERNAME/YOUR_REPO/
└── novels/
    └── your-novel.pdf
```

### Step 2: Get Raw URL
Get the raw URL of your PDF:
```
https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/novels/your-novel.pdf
```

### Step 3: Create Reader Link
Use the reader with your PDF:
```html
<a href="reader.html?file=https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/novels/your-novel.pdf">
  Read Online
</a>
```

## 📱 Blogger Integration

Add this code to your Blogger post:

```html
<!-- Download Button -->
<div style="text-align: center; margin: 20px 0;">
  <a href="YOUR_PDF_URL" download class="download-btn">
    Download PDF
  </a>
</div>

<!-- Online Reader Button -->
<div style="text-align: center; margin: 20px 0;">
  <a href="reader.html?file=YOUR_PDF_URL" target="_blank" class="read-online-btn">
    آن لائن پڑھیں
  </a>
</div>

<style>
.download-btn, .read-online-btn {
  display: inline-block;
  padding: 12px 24px;
  margin: 10px;
  background: linear-gradient(135deg, #667eea, #764ba2);
  color: white;
  text-decoration: none;
  border-radius: 8px;
  font-family: 'Noto Nastaliq Urdu', sans-serif;
  transition: transform 0.3s;
}

.download-btn:hover, .read-online-btn:hover {
  transform: translateY(-2px);
}
</style>
```

## 💻 Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `←` | Next Page (RTL) |
| `→` | Previous Page (RTL) |
| `+` | Zoom In |
| `-` | Zoom Out |
| `F` | Fullscreen |
| `ESC` | Close Modals |

## 🎯 Ad Integration

✅ **Ads Successfully Integrated!**

Your tinysentgrowled.com ad network is now fully integrated:

1. **Regular Break Ad** (every 20 pages):
   - Native Ad Script: `659cb4b7b49223ba9c2448ddbec930bd`
   - Additional Ad: `7ba08fc0cc0443b580d9b5e673cd42c2`

2. **Exit Confirmation Ad**:
   - Same ad scripts with separate containers
   - Displays when user attempts to exit

**Ad Features:**
- Auto-close after 15 seconds (break ads)
- Mobile responsive design
- Centered layout with proper spacing
- Professional animation effects

## 📊 Technical Details

- **Single File**: Everything in one HTML file
- **CDN Dependencies**: 
  - PDF.js v3.11.174
  - Font Awesome v6.5.1
  - Noto Nastaliq Urdu (Google Fonts)
- **Browser Support**: Chrome, Firefox, Safari, Edge (Latest versions)
- **Mobile Support**: Android & iOS browsers

## 🔧 Customization

### Change Ad Frequency
Edit line ~599 in `reader.html`:
```javascript
let adInterval = 20; // Change number to show ad after X pages
```

### Modify Colors
Edit CSS variables in `:root` section (lines ~27-37)

### Add More Fonts
Add font links in `<head>` and update `font-family` in CSS

## 📝 Example URLs

Test the reader with these example formats:
```
reader.html?file=https://example.com/novel.pdf
reader.html?file=https://raw.githubusercontent.com/user/repo/main/book.pdf
reader.html?file=https://yourdomain.com/path/to/novel.pdf
```

## 🤝 Support

For issues or questions:
1. Check if PDF URL is accessible
2. Ensure PDF is not password-protected
3. Verify CORS settings if hosting on custom domain
4. Test in different browsers

## 📄 License

Free to use for personal and commercial projects.

---

**Made with ❤️ for Urdu Literature**
