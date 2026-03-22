# BarrierLess PWA 🌏

**Break Language Barriers** — AI-powered translation assistant for English, Bahasa Indonesia & Mandarin Chinese.

![BarrierLess](icon-512.png)

## Features

### 1. 💬 AI Translation Chat
- Type in **English**, **Bahasa Indonesia**, or **Mandarin Chinese**
- Supports **mixed language input** (e.g. English + Bahasa)
- Auto-translates to Mandarin with **Hanzi + Pinyin + English meaning**
- Vice versa: Chinese input → English & Bahasa translation with Pinyin
- Every response includes a **Vocab Summary Table**

### 2. 📚 Vocab Library
- Automatically saves new vocabulary from chat conversations
- Categorized by **HSK levels** (HSK 1-6+)
- Search by Hanzi, Pinyin, or English
- Export vocabulary as JSON
- Track daily learning progress

### 3. 🎓 Learning Center
- **Flashcard Review** — Flip-card style vocabulary practice
- **Grammar & Usage Guide** — Learn when/how to use each word with example sentences
- **HSK Level Practice** — Vocabulary grouped by HSK proficiency level
- Educationally approved grammar patterns and usage tips

### 4. 📝 Worksheet Generator
- Generate **printable writing practice worksheets**
- Chinese character grid format (like traditional practice sheets)
- Includes Pinyin, English meaning, and HSK level
- Download as HTML → Print to PDF

### 5. 📷 Diligent Scanner
- Type or paste Mandarin text for instant translation
- Upload/capture images of menus, signs, etc.
- Translation includes **Pinyin** for pronunciation practice
- Choose output: English or Bahasa Indonesia
- Character-by-character breakdown with HSK levels

## Tech Stack

- Pure **HTML/CSS/JavaScript** (no framework dependencies)
- **PWA** with Service Worker for offline support
- **LocalStorage** for vocabulary persistence
- **Noto Sans SC** for Chinese character rendering
- **Plus Jakarta Sans** for UI typography

## Deployment

### GitHub Pages + Vercel

1. Push to GitHub:
```bash
git init
git add .
git commit -m "Initial BarrierLess PWA"
git remote add origin https://github.com/YOUR_USERNAME/barrierless.git
git push -u origin main
```

2. Deploy on Vercel:
- Connect your GitHub repo to [Vercel](https://vercel.com)
- Framework: Other
- Build: None needed (static site)
- Deploy!

### Local Development

Simply open `index.html` in a browser, or use a local server:
```bash
npx serve .
```

## PWA Installation

Visit the deployed URL on your phone → Click "Add to Home Screen" to install as a native-like app.

## Color Scheme

| Color | Hex | Usage |
|-------|-----|-------|
| Blue 700 | `#1565C0` | Primary |
| Blue 500 | `#2196F3` | Accent |
| Blue 50 | `#E3F2FD` | Light background |
| White | `#FFFFFF` | Cards & surfaces |
| Gray 800 | `#1E293B` | Text |

## License

MIT — Built with ❤️ for language learners in China

---

*BarrierLess — 无障碍 (wú zhàng ài)*
