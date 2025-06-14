# Poetry Appreciation Website

A beautiful, interactive website for exploring and appreciating classic poetry from both English and Chinese literary traditions.

## 🌟 Features

- **Bilingual Collection**: 10 carefully selected poems (5 English, 5 Chinese)
- **Interactive Interface**: Click on poems to read and analyze them
- **Category Filtering**: Browse by "All Poems", "English Poems", or "Chinese Poems"
- **Search Functionality**: Find poems by title, author, or content
- **Favorites System**: Save your favorite poems with local storage
- **Dark Mode**: Toggle between light and dark themes
- **XML Analysis**: Structured literary analysis for each poem
- **Responsive Design**: Works perfectly on desktop and mobile devices

## 📖 Poetry Collection

### English Poems
1. **"Sonnet 18"** by William Shakespeare
2. **"Because I could not stop for Death"** by Emily Dickinson
3. **"The Road Not Taken"** by Robert Frost
4. **"Ozymandias"** by Percy Bysshe Shelley
5. **"Do not go gentle into that good night"** by Dylan Thomas

### Chinese Poems (中文诗词)
1. **"静夜思"** by 李白 (Li Bai)
2. **"春晓"** by 孟浩然 (Meng Haoran)
3. **"登鹳雀楼"** by 王之涣 (Wang Zhihuan)
4. **"相思"** by 王维 (Wang Wei)
5. **"咏鹅"** by 骆宾王 (Luo Binwang)

## 🚀 Live Demo

Visit the live website: [Your GitHub Pages URL will be here]

## 🛠️ Technical Details

- **Frontend**: Pure HTML, CSS, and JavaScript
- **Storage**: Local Storage for favorites
- **Responsive**: CSS Grid and Flexbox layout
- **Accessibility**: Semantic HTML and keyboard navigation
- **Performance**: Optimized for fast loading

## 📁 Project Structure

```
poetry-appreciation/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🚀 Deployment

### GitHub Pages Deployment

1. **Fork or clone this repository**
2. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"
3. **Access your site**: Your site will be available at `https://[username].github.io/[repository-name]`

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/[username]/[repository-name].git
   cd [repository-name]
   ```

2. Open `index.html` in your browser or serve it with a local server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve .
   ```

## 🎨 Customization

### Changing Colors
Edit the CSS variables in `styles.css` to customize the color scheme:

```css
.filter-btn {
    background: rgba(255, 255, 255, 0.2);  /* Button background */
    color: white;                          /* Button text */
    border: 2px solid rgba(255, 255, 255, 0.3); /* Button border */
}

.filter-btn:hover,
.filter-btn.active {
    background: rgba(255, 255, 255, 0.9);  /* Active button background */
    color: #667eea;                        /* Active button text */
}
```

### Adding New Poems
1. Open `script.js`
2. Add new poem objects to the `poems` array
3. Follow the existing structure with `title`, `text`, `author`, `category`, and `analysis` fields

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Classic poetry authors whose works are featured
- Open source community for inspiration
- GitHub Pages for free hosting

---

*Crafted with 💜 for lovers of classic poetry | Explore the timeless beauty of words*
