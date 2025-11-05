# 📸 Photo Upload App - PHOTO_BOOTH# PHOTO_BOOTH

A modern, professional web application for capturing and uploading photos directly to Supabase cloud storage.

## ✨ Features

- 📷 **Live Camera Capture** - Real-time photo capture from your webcam
- 📧 **Email Integration** - Link photos to email addresses
- ☁️ **Cloud Storage** - Photos stored securely in Supabase
- 📱 **Mobile Friendly** - Fully responsive design
- ⚡ **Instant Upload** - Fast base64 encoding and upload
- 🎨 **Modern UI** - Beautiful gradient design with smooth animations

## 🚀 Quick Start

### Option 1: Direct (Easiest)
1. Open `index.html` in your web browser
2. Click "▶️ START CAMERA"
3. Allow camera permissions
4. Click "📸 CAPTURE" to take a photo
5. Enter your email
6. Click "✅ UPLOAD PHOTO"

### Option 2: Local Server
```bash
# In the PHOTO_BOOTH directory
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

## 📁 Project Structure

```
PHOTO_BOOTH/
├── index.html          ← Main app (open this file)
├── README.md           ← This file
└── requirements.txt    ← Setup info (frontend only)
```

## 🔧 How It Works

1. **Capture** - Camera captures your photo and converts to base64
2. **Email** - You enter your email address
3. **Upload** - Photo + email sent to Supabase database
4. **Success** - Page refreshes automatically

## 📊 Database

- **Cloud Service**: Supabase
- **Database Table**: `photos`
- **Columns**: 
  - `email` (text)
  - `image` (text - base64 encoded)

## 🛠️ Troubleshooting

### Camera not working?
- ✅ Check browser permissions
- ✅ Try Chrome, Firefox, or Safari
- ✅ Ensure good lighting
- ✅ Use HTTPS or localhost

### Upload fails?
- ✅ Check email format is valid
- ✅ Check internet connection
- ✅ Open console (F12) to see error details
- ✅ Verify email field is filled

### Page doesn't load?
- ✅ Make sure you opened `index.html`
- ✅ Try refreshing the page (Ctrl+F5)
- ✅ Try a different browser

## 📋 Requirements

**None!** This is a frontend-only application.

- No Python packages needed
- No server setup required
- No installation needed
- Just open the HTML file in a browser!

To serve locally:
```bash
python -m http.server 8000
```

## 🎯 Use Cases

- 📸 Profile photo uploads
- 🎬 Live event photography
- 📷 Document scanning
- 👤 ID verification
- 🏢 Employee photo capture
- 📱 Mobile app screenshots

## 🔐 Security Notes

- ✅ API key embedded (development only)
- ✅ HTTPS recommended for production
- ✅ Consider backend for production deployment
- ✅ Add authentication for multi-user scenarios

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Edge | ✅ Full |
| Mobile Chrome | ✅ Full |
| Mobile Safari | ✅ Full |

## 🚀 Deployment

### Deploy to Netlify (Free)
1. Push to GitHub
2. Connect to Netlify
3. Deploy automatically

### Deploy to Vercel (Free)
1. Push to GitHub
2. Connect to Vercel
3. Deploy automatically

### Deploy to GitHub Pages
1. Push to GitHub
2. Enable Pages in settings
3. Access at `username.github.io/PHOTO_BOOTH`

## 📝 Notes

- Photos are stored as base64 strings in the database
- Each upload automatically refreshes the page
- Works offline for camera capture, needs internet for upload
- Maximum browser request size may limit photo size (typically 10-100MB)

## 🎨 Customization

Edit `index.html` to customize:
- Colors (search for `#667eea`)
- Text labels
- Supabase credentials
- Camera settings

## 📞 Support

For issues:
1. Check browser console (F12 → Console tab)
2. Verify Supabase database exists
3. Ensure internet connection
4. Try a different browser

## 📄 License

Open source - feel free to use and modify

## 🙏 Credits

Built with:
- HTML5 (Camera API)
- CSS3 (Modern styling)
- JavaScript (Logic & API calls)
- Supabase (Cloud database)

---

**Version**: 1.0.0  
**Last Updated**: November 5, 2025  
**Author**: Your Name

Enjoy using Photo Booth! 📸✨
