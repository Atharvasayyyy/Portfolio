# 🚀 Portfolio Website

A modern, responsive portfolio website built with React, TypeScript, and Vite. Showcasing skills, projects, experience, and contact information with a sleek dark theme design.

**Live Demo:** [https://atharvasayyyy.github.io/Portfolio/](https://atharvasayyyy.github.io/Portfolio/)

---

## ✨ Features

- 🎨 **Modern UI Design** - Beautiful dark theme with gradient accents
- 📱 **Fully Responsive** - Works seamlessly on all devices (mobile, tablet, desktop)
- ⚡ **Fast Performance** - Built with Vite for optimal build speed
- 🎯 **Multiple Sections**:
  - Hero/Introduction
  - About Me
  - Technical Skills
  - Professional Experience
  - Project Showcase
  - Education
  - Contact Form
  - Testimonials
- 🛠️ **Component Library** - Radix UI components for consistent design
- 📊 **Data Visualization** - Charts and visualizations with Recharts
- 🎪 **Barcode Scanner** - Interactive product scanning feature
- 💾 **Shopping List** - Built-in shopping list functionality

---

## 🛠️ Tech Stack

- **Frontend Framework**: React 18.3.1
- **Language**: TypeScript
- **Build Tool**: Vite 6.3.5
- **Styling**: Tailwind CSS
- **UI Components**: Radix UI
- **Form Handling**: React Hook Form
- **Charts**: Recharts
- **Carousel**: Embla Carousel
- **Icons**: Lucide React
- **Themes**: Next Themes

---

## 📦 Installation

### Prerequisites

- Node.js 18+
- npm or yarn

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/Atharvasayyyy/Portfolio.git
   cd Portfolio
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**

   ```bash
   npm run dev
   ```

   The site will open at `http://localhost:3000`

4. **Build for production**
   ```bash
   npm run build
   ```
   Creates optimized build in `dist/` folder

---

## 🚀 Deployment

This project is automatically deployed to GitHub Pages using GitHub Actions.

### Deploy to GitHub Pages

1. Push changes to `main` branch

   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```

2. GitHub Actions will automatically:

   - Build the project
   - Upload artifacts
   - Deploy to GitHub Pages

3. View your site at: `https://yourusername.github.io/Portfolio/`

### Manual Build & Deploy

```bash
# Build for production
npm run build

# The dist folder is ready to be deployed
```

---

## 📁 Project Structure

```
Portfolio/
├── src/
│   ├── components/          # React components
│   │   ├── About.tsx
│   │   ├── Projects.tsx
│   │   ├── Experience.tsx
│   │   ├── Skills.tsx
│   │   ├── Education.tsx
│   │   ├── Contact.tsx
│   │   ├── Navigation.tsx
│   │   └── ui/             # Radix UI components
│   ├── styles/             # Global styles
│   ├── App.tsx             # Main app component
│   └── main.tsx            # Entry point
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions workflow
├── vite.config.ts          # Vite configuration
├── package.json            # Dependencies
└── README.md               # This file
```

---

## 🎨 Customization

### Update Content

Edit components in `src/components/` to customize:

- Personal information
- Skills and expertise
- Project details
- Experience timeline
- Contact information

### Update Colors & Theme

Modify Tailwind CSS colors in `src/styles/globals.css` and component files.

The main color scheme uses:

- Primary: Cyan/Blue gradients
- Dark theme: Slate 950 background
- Accents: Cyan 500, Blue 600

### Add New Sections

1. Create a new component in `src/components/`
2. Import and add to `src/App.tsx`
3. Add navigation link in `src/components/Navigation.tsx`

---

## 📄 Available Scripts

| Command         | Description              |
| --------------- | ------------------------ |
| `npm run dev`   | Start development server |
| `npm run build` | Build for production     |
| `npm install`   | Install dependencies     |

---

## 🔗 Links

- **Repository**: [GitHub](https://github.com/Atharvasayyyy/Portfolio)
- **Live Demo**: [Portfolio Website](https://atharvasayyyy.github.io/Portfolio/)
- **Design Reference**: [Figma Design](https://www.figma.com/design/L1LCZUQQUfl7wGKibkEpEG/Grocery-Shopping-App)

---

## 📝 License

This project is open source. Feel free to use it as a template for your own portfolio.

---

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

---

## 📞 Contact

- **Website**: [https://atharvasayyyy.github.io/Portfolio/](https://atharvasayyyy.github.io/Portfolio/)
- **GitHub**: [@Atharvasayyyy](https://github.com/Atharvasayyyy)

---

## 🙏 Acknowledgments

- [Radix UI](https://www.radix-ui.com/) - Component library
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Vite](https://vitejs.dev/) - Next generation frontend tooling
- [React](https://react.dev/) - JavaScript library for building UIs

---

**Made with ❤️ by Atharva**
