# 📸 Simple Photo Upload App

A simple, clean web app to take photos with your camera and upload them to Supabase with your email.

## 🚀 Quick Start

1. **Open** `frontend/index.html` in your web browser
2. **Click** "▶️ Start Camera"
3. **Allow** camera permissions
4. **Click** "📸 Capture" to take a photo
5. **Enter** your email address
6. **Click** "✅ UPLOAD PHOTO"

## 📁 Files

```
face_app/
├── frontend/
│   └── index.html          ← Open this file in browser
└── README.md               ← This file
```

## ✅ Features

- 📷 Live camera capture
- 📧 Enter email
- 🖼️ Photo preview
- ☁️ Upload to Supabase
- ✨ Simple and clean UI

## 🔧 How It Works

1. **Capture** - Camera captures your photo
2. **Convert** - Photo converted to base64 string
3. **Email** - You enter your email
4. **Upload** - Sends email + photo to Supabase database

## 📊 Database

- Table: `photos`
- Columns: `email`, `image` (base64)
- Cloud: Supabase

## 💡 Notes

- No setup needed, just open the HTML file
- API key is embedded (development only)
- Works on desktop and mobile
- Requires camera permission

## 🛠️ Troubleshooting

**Camera not working?**
- Check browser permissions
- Try Chrome, Firefox, or Safari
- Ensure good lighting

**Upload fails?**
- Check email format
- Check internet connection
- Open browser console (F12) for errors

