# 🔍 Vehicle Info Tracker

> **A Beautiful Matrix-Themed Vehicle Information Extraction System**
> 
> *Built by Ahir Ankush* 👨‍💻

---

## ✨ Features

- 🎨 **Matrix-Inspired Design** - Cyberpunk aesthetic with neon green glow effects
- 🚗 **Real-Time Data** - Fetch vehicle information instantly
- ⚡ **Fast & Responsive** - Optimized for all devices
- 🔐 **Secure** - Client-side processing
- 💚 **Creator Badge** - Features creator name prominently
- 📱 **Mobile Friendly** - Fully responsive design
- 🎯 **Easy to Use** - Simple one-click search interface
- 🌟 **Visual Effects** - Animated matrix background, glowing text, smooth transitions

---

## 🚀 Quick Start

### Option 1: Direct File Usage
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Enter a vehicle registration number (e.g., `DL01AB1234`)
4. Click **🔎 SCAN** to retrieve vehicle information

### Option 2: Deploy to Vercel
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Option 3: Deploy to Netlify
1. Visit [netlify.com](https://netlify.com)
2. Click "New site from Git"
3. Connect your GitHub repository
4. Deploy!

---

## 📋 How to Use

1. **Enter Vehicle Number**: Input the vehicle registration number
   - Format: State Code + 2 Digits + Letters + 4 Digits
   - Example: `DL01AB1234`

2. **Click SCAN**: Press the green "🔎 SCAN" button

3. **View Results**: The system fetches and displays:
   - Vehicle make and model
   - Registration details
   - Owner information
   - Other vehicle specs

4. **Clear Data**: Use the "🗑️ CLEAR" button to reset

---

## 🎨 Design Features

### Color Scheme
- **Primary Green**: `#00ff00` - Matrix classic
- **Cyan Accent**: `#00ffff` - Modern tech feel
- **Dark Background**: `#0a0e27` - Deep space black
- **Error Red**: `#ff0055` - Alert color

### Visual Effects
- Animated Matrix background with falling characters
- Grid overlay pattern
- Neon glow on text
- Smooth hover transitions
- Loading spinner animation
- Slide-in animations for results

### Typography
- Monospace font (`Courier New`) for authentic matrix feel
- Letter spacing for dramatic effect
- Text shadows for depth

---

## 🔧 Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Advanced styling with animations
- **Vanilla JavaScript** - No dependencies
- **API**: Vehicle Info API (Acko)

---

## 📡 API Integration

The tool integrates with the Vehicle Info API:

```
Base URL: https://vehicle-info-api-acko.vercel.app
Endpoint: /info?vehicle={VEHICLE_NUMBER}
```

### Request Example
```javascript
fetch('https://vehicle-info-api-acko.vercel.app/info?vehicle=DL01AB1234')
    .then(res => res.json())
    .then(data => console.log(data));
```

---

## 🎯 Creator Information

**Name**: Ahir Ankush 👨‍💻  
**GitHub**: [ahirankush771](https://github.com/ahirankush771)  
**Project**: Vehicle Info Tracker  

---

## 📂 File Structure

```
Vehicle_info/
├── index.html       (Main application file)
├── README.md        (This file)
├── package.json     (Project metadata)
└── vercel.json      (Vercel configuration)
```

---

## 🌐 Live Demo

Once deployed, access your tool at:
- Vercel: `https://your-vercel-app.vercel.app`
- Netlify: `https://your-netlify-app.netlify.app`
- Local: `file:///path/to/index.html`

---

## ✅ Supported Vehicle Number Formats

- Indian Registration Numbers
- State Code (2 letters)
- District Code (2 digits)
- Registration Letters & Numbers

**Example Formats**:
- `DL01AB1234` - Delhi
- `MH02CD5678` - Maharashtra
- `KA03EF9012` - Karnataka
- `TN04GH3456` - Tamil Nadu

---

## 🐛 Troubleshooting

### Issue: "Vehicle not found"
- ✓ Check if the registration number is correct
- ✓ Ensure proper formatting (State Code + 2 Digits + Letters + 4 Digits)
- ✓ Verify it's an Indian vehicle number

### Issue: "Error" message
- ✓ Check internet connection
- ✓ Verify the API is accessible
- ✓ Try again after a moment

### Issue: Matrix background not showing
- ✓ Update your browser
- ✓ Enable JavaScript
- ✓ Clear browser cache

---

## 🚀 Future Enhancements

- [ ] Dark/Light theme toggle
- [ ] Vehicle history tracking
- [ ] Export reports to PDF
- [ ] Advanced filters
- [ ] Multi-language support
- [ ] Progressive Web App (PWA)
- [ ] Offline support

---

## 📜 License

This project is open source. Feel free to use, modify, and distribute.

---

## 🙏 Credits

- **API Provider**: Acko
- **Design Inspiration**: Matrix (1999)
- **Developer**: Ahir Ankush

---

## 📞 Support

For issues or questions, please open an issue on GitHub or contact the creator.

---

**Made with 💚 by Ahir Ankush**

*"In the world of vehicles, data is everything."*

---

## 🎬 Quick Features Summary

| Feature | Status |
|---------|--------|
| Matrix Theme | ✅ Done |
| Creator Badge | ✅ Done |
| Real-time Search | ✅ Done |
| Responsive Design | ✅ Done |
| Error Handling | ✅ Done |
| Animations | ✅ Done |
| Mobile Optimized | ✅ Done |

---

**Last Updated**: June 17, 2026  
**Version**: 1.0.0  
**Status**: ✅ Production Ready