<div align="center">
  
# Aurora Poetica 🌌
[Live Demo](https://drbaph.is-a.dev/AuroraPoetica/)

</div>

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/D3.js-F68E1E?style=for-the-badge&logo=d3.js&logoColor=white" alt="D3.js" />
  <img src="https://img.shields.io/badge/PoetryDB_API-FF6B6B?style=for-the-badge&logo=api&logoColor=white" alt="PoetryDB API" />
</div>

<div align="center">
  <h3>Experience Poetry in a New Dimension</h3>
  <p>An immersive, interactive poetry discovery platform with cutting-edge visual effects</p>
</div>

## ✨ Features

### 🎨 Ultra-Modern Design
- **Aurora Background Effects**: Dynamic animated gradients creating a mesmerizing backdrop
- **Glassmorphism UI**: Multi-layered glass effects with backdrop filters
- **Neon Aesthetics**: Glowing text with gradient effects and custom animations
- **Floating Particles**: Ambient particle system for depth and atmosphere
- **3D Card Interactions**: Mouse-responsive tilt effects on desktop

### 📱 Fully Responsive
- Optimized for mobile, tablet, and desktop devices
- Touch-friendly interactions with no blue tap highlights
- Adaptive typography and spacing
- Performance-optimized animations

### 🎭 Poetry Features
- **Multiple Themes**: Random, Love, Nature, Melancholy, and Mythology
- **Dynamic Word Clouds**: Visual representation of poem keywords using D3.js
- **Smooth Animations**: Staggered line reveals and transition effects
- **Smart Error Handling**: Automatic retries and fallback mechanisms

### 🔧 Technical Highlights
- **Zero Dependencies**: Pure vanilla JavaScript (except for visualization libraries)
- **API Integration**: Real-time poem fetching from PoetryDB
- **Modern CSS**: CSS Grid, Flexbox, Custom Properties, and advanced animations
- **Accessibility**: Semantic HTML and keyboard navigation support

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for API access and CDN resources

### Installation
1. Clone the repository:
```bash
git clone https://github.com/Saganaki22/Poems.git
cd Poems
```

2. Open `index.html` in your web browser:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Or simply double-click index.html
```

## 📁 Project Structure
```
Poems/
├── index.html          # Main application file
├── favicon.svg         # Favicon
├── 404.html           # Custom 404 error page
├── og-img.jpg         # OG Image
├── LICENSE            # MIT
└── README.md          # Project documentation
```

## 🎯 Usage

### Discovering Poetry
1. **Select a Theme**: Choose from the available theme pills or stick with random
2. **Generate Poems**: Click "Conjure New Verse" to fetch a new poem
3. **Interact**: Hover over the poem card for 3D effects (desktop only)
4. **Watch the Word Cloud**: See key words from the poem float in the background

### Themes Available
- **Random**: Discover poems from various authors and styles
- **Love**: Romantic verses from Shakespeare, Burns, and more
- **Nature**: Natural beauty through Wordsworth, Frost, and others
- **Melancholy**: Darker themes from Poe, Blake, and Dickinson
- **Mythology**: Epic tales from Keats, Byron, and Shelley

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced animations, gradients, and effects
- **JavaScript ES6+**: Modern syntax and features
- **Tailwind CSS**: Utility-first CSS framework

### Libraries & APIs
- **D3.js**: Data visualization for word clouds
- **D3-Cloud**: Word cloud layout plugin
- **PoetryDB API**: RESTful API for poetry content
- **Google Fonts**: Premium typography (Space Grotesk & Playfair Display)

### Design Patterns
- **Glassmorphism**: Translucent UI elements with blur
- **Neumorphism**: Soft, extruded effects
- **Responsive Design**: Mobile-first approach
- **Progressive Enhancement**: Core functionality works everywhere

## 🎨 Color Palette
```css
--neon-teal: #00ffcc
--neon-purple: #9945ff
--neon-pink: #ff0080
--glass-bg: rgba(12, 12, 20, 0.4)
--glass-border: rgba(255, 255, 255, 0.08)
```

## 🌟 Key Features Implementation

### Aurora Background Animation
Creates a dynamic, ever-changing background using CSS animations and gradients:
```css
@keyframes aurora {
    0%, 100% { transform: translateY(0) rotate(0deg) scale(1); }
    33% { transform: translateY(-20px) rotate(120deg) scale(1.1); }
    66% { transform: translateY(20px) rotate(240deg) scale(0.9); }
}
```

### Smart Retry Logic
Automatically handles API failures with intelligent fallbacks:
```javascript
// Retry with different authors on failure
// Fall back to random poems if themed search fails
// Implement timeout handling for slow connections
```

### Dynamic Word Cloud Generation
Uses D3.js to create floating word visualizations from poem content, filtering out common words and sizing based on frequency.

## 📜 License
This project is open source and available under the MIT License.

---

<div align="center">
  <p>Crafted with 💜 for poetry lovers everywhere</p>
</div>
