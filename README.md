# 🍪 OREO Website Clone

A modern, responsive clone of the official OREO website featuring a beautiful UI with carousel animations, product showcases, and interactive elements.

**[🔗 View Live Site](https://oreo-clone12.netlify.app/)**


## 📋 Table of Contents

- [🍪 OREO Website Clone](#-oreo-website-clone)
  - [📋 Table of Contents](#-table-of-contents)
  - [🎯 About](#-about)
  - [✨ Features](#-features)
  - [🛠️ Technologies Used](#️-technologies-used)
  - [📁 Project Structure](#-project-structure)
  - [🚀 Getting Started](#-getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [💻 Usage](#-usage)
  - [🌐 Deployment](#-deployment)
  - [🎨 Project Highlights](#-project-highlights)
    - [Carousel Implementation](#carousel-implementation)
    - [Design Elements](#design-elements)
    - [Key Sections](#key-sections)
  - [📝 Notes](#-notes)
  - [🤝 Contributing](#-contributing)
  - [📄 License](#-license)

## 🎯 About

This project is a frontend recreation of the OREO website, showcasing various OREO cookie products, collections, and customization options. The website includes an interactive carousel, product categories, and promotional sections with smooth animations and hover effects.

## ✨ Features

- **Interactive Carousel**: Auto-rotating image carousel that cycles through promotional banners every 3 seconds
- **Responsive Navigation**: Multi-level navigation bar with main menu, sub-navigation, and icon-based actions
- **Product Categories**: Showcase of different OREO collections including:
  - Mickey & Friends
  - Bundles
  - OREO® Coca-Cola™
  - OREO Celebrations
  - OREOiD (Custom cookies)
- **Gradient Designs**: Beautiful gradient effects on buttons and text elements
- **Hover Animations**: Interactive hover effects on navigation items and product cards
- **Product Showcase**: Dedicated sections featuring:
  - OREO by You (Customization)
  - Celebrations collection
  - Classics & More
  - Featured products
- **Character Showcase**: Special section highlighting Mickey & Friends themed OREO cookies

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for structure
- **CSS3**: 
  - Flexbox & Grid layouts
  - CSS Gradients
  - Transitions and animations
  - Responsive design
- **JavaScript (Vanilla)**: Carousel functionality
- **Netlify**: Deployment and hosting configuration

## 📁 Project Structure

```
Oreo/
│
├── index.html          # Main HTML structure
├── styles.css          # All styling and layouts
├── script.js           # Carousel functionality
├── netlify.toml        # Netlify deployment configuration
├── README.md           # Project documentation
│
└── Assets/             # Image assets
    ├── logo-top-HFSIUXXF.png
    ├── carousel images
    ├── product images
    └── ... (other assets)
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (optional, for development)
- Git (optional, for version control)

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd Oreo
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser, or
   - Use a local development server for better experience:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using VS Code Live Server extension
     # Right-click index.html > Open with Live Server
     ```

3. **View the website**
   - Navigate to `http://localhost:8000` (or your chosen port)
   - The website should load with all assets and functionality

## 💻 Usage

- **Navigation**: Click on navigation items to explore different sections (note: links are currently placeholders)
- **Carousel**: The carousel automatically rotates through promotional images every 3 seconds
- **Product Categories**: Hover over product cards to see zoom effects
- **Interactive Elements**: Hover over navigation items to see color transitions and background changes

## 🌐 Deployment

This project is configured for deployment on Netlify:

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Connect your repository to Netlify
3. Netlify will automatically detect the `netlify.toml` configuration
4. The site will be deployed with proper SPA routing support

The `netlify.toml` file includes redirect rules to ensure proper routing for single-page application behavior.

## 🎨 Project Highlights

### Carousel Implementation
- Smooth transitions between images
- Auto-rotation every 3 seconds
- Pure JavaScript implementation (no dependencies)

### Design Elements
- **Color Scheme**: Uses OREO brand colors including:
  - Blue (#0058C9, #2B93E6)
  - Purple (#9b71c2)
  - Red (#eb3726, #EB3B36)
  - Neutral grays and whites
- **Typography**: Clean, bold fonts with proper hierarchy
- **Layout**: Centered, responsive design with proper spacing

### Key Sections
1. **Header Navigation**: Logo, main menu, sub-navigation, and action icons
2. **Hero Carousel**: Rotating promotional banners
3. **Category Grid**: Product collection tiles
4. **Feature Sections**: OREO by You, Celebrations, and Classics
5. **Character Showcase**: Mickey & Friends themed section with gradient background
6. **Product Grid**: Featured products showcase

## 📝 Notes

- All navigation links are currently placeholder links (`#`)
- Images are stored locally in the `Assets/` directory
- The design is optimized for desktop viewing
- The carousel uses CSS transforms for smooth animations

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements!

## 📄 License

This project is for educational purposes and is a clone/recreation of the official OREO website. All OREO branding and images are property of their respective owners.

---

**Built with ❤️ during Diwali Vacation**







