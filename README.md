[README.md](https://github.com/user-attachments/files/27236219/README.md)
# 📖 Book Quotes — 书语

> *以文字为舟，渡万千书海 / Where words become worlds*

A premium, single-page web app for exploring and sharing literary quotes from 48 classic books across three languages — Chinese, English, and French.

---

## ✨ Features

### 🌍 Trilingual Support
Switch seamlessly between 中文, English, and Français. Book titles, quotes, introductions, and all UI text adapt to the selected language.

### 📚 48 Classic Books · 1,440+ Quotes
From Orwell's *1984* to Cao Xueqin's *红楼梦*, from Hemingway's *The Old Man and the Sea* to Dostoyevsky's *The Brothers Karamazov*. Each book includes:
- **10 curated quotes** per language
- **Book introduction** in 3 languages
- **Translated titles** across all languages

### 🎴 Postcard Generator
Click any quote card to generate a beautiful postcard with:
- Random gradient backgrounds (10 color themes)
- Decorative corner frames and stamp
- High-resolution 1200×800 PNG download via Canvas API
- No external libraries required

### 🌊 Auto-Rotating Quotes
Quote text refreshes automatically every 15 seconds with a gentle fade-out/fade-in transition. Cards shimmer with a light sweep animation on first appearance.

### 📱 Fully Responsive
Optimized for all screen sizes:
- **Desktop** — Full layout with 2-column quote grid
- **Tablet** (≤768px) — Adapted spacing, single-column cards
- **Mobile** (≤400px) — Compact layout with touch-friendly targets

### 🎨 Premium Design
- Low-saturation deep blue gradient palette
- Glassmorphism cards with subtle backdrop-filter
- Playfair Display + Merriweather typography
- Smooth CSS animations (fadeInUp, shimmer, sparkle)
- Custom scrollbar and selection color
- Font anti-aliasing for crisp text rendering

---

## 🚀 Getting Started

No build tools required. Just open the file:

```bash
# Clone the repository
git clone https://github.com/your-username/book-quotes.git

# Open in browser
cd book-quotes
open index.html
```

Or simply drag `index.html` into any modern browser.

---

## 📁 Project Structure

```
Book-Quotes-main/
└── index.html          # Single-file app (HTML + CSS + JS)
```

All HTML, CSS (~1,300 lines), and JavaScript (~3,500 lines) live in one file. No dependencies, no build step.

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (Custom Properties, Glassmorphism, Animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Typography | Google Fonts (Playfair Display, Merriweather) |
| Image Export | Canvas API |
| External Libraries | **None** |

---

## 📖 Data Coverage

| Database | Entries | Description |
|----------|---------|-------------|
| `quotesDB` | 48 books × 10 quotes × 3 languages | Core quote content |
| `bookTitlesDB` | 55 entries | Translated book titles |
| `bookIntrosDB` | 59 entries | Book introductions/synopses |

### Books Include

**English Literature:** 1984, The Great Gatsby, To Kill a Mockingbird, The Catcher in the Rye, Pride and Prejudice, Jane Eyre, Wuthering Heights, Frankenstein, The Little Prince, Moby-Dick, Hamlet, Romeo and Juliet, Brave New World, The Handmaid's Tale, Norwegian Wood, and more...

**Chinese Literature:** 百年孤独 (One Hundred Years of Solitude), 围城 (The Fortress Besieged), 红楼梦 (Dream of the Red Chamber)

**World Literature:** Les Misérables, Don Quixote, The Brothers Karamazov, Anna Karenina, War and Peace, Crime and Punishment, The Odyssey, The Iliad, Demian, Siddhartha, The Trial, The Metamorphosis, and more...

---

## 🎯 Browser Support

- Chrome 80+
- Firefox 80+
- Safari 14+
- Edge 80+

Requires `backdrop-filter` and `Canvas API` support.

---

## 📄 License

This project is open source. Feel free to use, modify, and share.

---

*Built with ❤️ for book lovers everywhere.*
