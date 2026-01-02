# AI HUBX — Free AI Tools Directory

A modern, dark-themed website showcasing curated free AI tools for image generation, video creation, and voice synthesis.

## 🎯 Features

- **Image Generator AI** — Discover 6+ free tools (Stable Diffusion, Craiyon, Leonardo.AI, etc.)
- **Text-to-Video AI** — Browse free video generators (Synthesia, HeyGen, Invideo AI, etc.)
- **AI Voice Generator** — Explore text-to-speech tools (Google TTS, ElevenLabs, Natural Reader, etc.)
- **Dark Theme** — Modern, sleek design with violet + teal gradients
- **Responsive Design** — Mobile-friendly interface
- **No Dependencies** — Pure HTML, CSS, JavaScript (single file)

## 📁 Project Structure

```
ai-hubx/
├── index.html           # Main site
├── ai-hubx-logo.svg     # Dark theme logo
├── README.md            # This file
├── .gitignore           # Git ignore rules
└── netlify.toml         # Netlify config (optional)
```

## 🚀 Quick Start

### Local Testing
```bash
# Simply open in browser
open index.html
```

### Deploy to Netlify

#### Option 1: Via GitHub (Recommended)

1. **Create GitHub Repository:**
   - Go to https://github.com/new
   - Create new repo: `ai-hubx`
   - Clone to your machine

2. **Add Files:**
   ```bash
   cd ai-hubx
   cp /path/to/index.html .
   cp /path/to/ai-hubx-logo.svg .
   cp /path/to/README.md .
   ```

3. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Initial AI HUBX site"
   git push -u origin main
   ```

4. **Deploy via Netlify:**
   - Go to https://netlify.com
   - Click "New site from Git"
   - Select your GitHub repo
   - Build command: (leave empty)
   - Publish directory: `.`
   - Click "Deploy"

#### Option 2: Direct Drag & Drop

1. Go to https://app.netlify.com/drop
2. Drag `index.html` and `ai-hubx-logo.svg` into the deploy zone
3. Your site is live!

## 🎨 Customization

### Update Contact Info
Edit `index.html` (search for `mailto:` and `https://t.me/`):
```html
<a class="btn" href="mailto:your-email@example.com">Email</a>
<a class="btn" href="https://t.me/your_username">Telegram</a>
```

### Add More Tools
Edit the `aiTools` object in `index.html`:
```javascript
imageGen: [
  { name: 'Tool Name', desc: 'Description', url: 'https://...' },
  // Add more...
]
```

### Change Colors
Modify CSS variables in `<style>`:
```css
--accent: #7c3aed;      /* Violet */
--accent-2: #06b6d4;    /* Teal */
```

## 📊 Tool Categories

### 🖼️ Image Generators
- Free tier: Craiyon, Leonardo.AI, OpenArt
- Cloud-based: Stable Diffusion (Hugging Face), Bing Image Creator
- Design platforms: Canva

### 🎬 Video Generators
- Avatar-based: HeyGen, Synthesia
- Text-to-video: Invideo AI, Fliki
- AI editing: Runway ML, Descript

### 🎤 Voice Generators
- APIs: Google TTS, Azure TTS, ElevenLabs
- Web tools: Natural Reader, Uberduck
- Desktop: Balabolka

## 📝 License

Free to use and modify. No attribution required.

## 🤝 Contributing

Feel free to:
- Add more AI tools
- Improve UI/design
- Fix bugs
- Add new categories

Just submit a PR!

## 📧 Support

Questions? Issues?
- **Telegram:** https://t.me/REPRANGER
- **Email:** hello@aihubx.example

---

**Live Demo:** [Deploy to Netlify](#option-2-direct-drag--drop)  
**Built with:** HTML, CSS, JavaScript, ❤️
