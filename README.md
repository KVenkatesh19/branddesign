# Brand Design - Modern Creative Agency Website

A fully responsive, modern website for a creative design agency built with React, TypeScript, and Tailwind CSS. Features a clean design system with smooth navigation and interactive elements.

![Brand Design Website](https://img.shields.io/badge/Status-Live-success)
![React](https://img.shields.io/badge/React-18.3.1-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-Latest-blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.1-38bdf8)

## 🌐 Live Preview

**[View Live Website →](https://your-website-url.com)**

## ✨ Features

### 🎨 Modern Design
- Clean, professional design with brand colors (Green #34c759, Blue #08f, Purple #6366f1)
- Fully responsive layout that works on all devices
- Smooth transitions and hover effects
- Custom Roboto font family implementation

### 📄 Multi-Page Navigation
- **Home** - Hero section with call-to-action and service overview
- **Services** - Detailed breakdown of services (Strategy, UX Design, Development)
- **Portfolio** - Showcase of 6 projects with tech stacks, GitHub links, and live demos
- **Contact** - Contact form with company information

### 🚀 Technical Features
- Built with React 18 and TypeScript for type safety
- React Router for seamless client-side navigation
- Tailwind CSS 4.0 for modern styling
- Lucide React icons for beautiful UI elements
- Mobile-first responsive design
- SEO-friendly structure

### 📱 Responsive Design
- Desktop (1920px+)
- Laptop (1024px - 1920px)
- Tablet (768px - 1024px)
- Mobile (320px - 768px)

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **React 18.3.1** | Frontend framework |
| **TypeScript** | Type safety and better developer experience |
| **React Router 7.13** | Client-side routing |
| **Tailwind CSS 4.1** | Utility-first CSS framework |
| **Vite** | Build tool and development server |
| **Lucide React** | Icon library |

## 📦 Installation

### Prerequisites
- Node.js 18+ installed
- npm or pnpm package manager

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/brand-design-website.git
   cd brand-design-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   pnpm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   # or
   pnpm dev
   ```

4. **Open in browser**
   ```
   http://localhost:5173
   ```

5. **Build for production**
   ```bash
   npm run build
   # or
   pnpm build
   ```

## 📁 Project Structure

```
brand-design-website/
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── Navigation.tsx      # Main navigation component
│   │   │   ├── Footer.tsx          # Footer component
│   │   │   ├── Layout.tsx          # Layout wrapper with header/footer
│   │   │   └── figma/
│   │   │       └── ImageWithFallback.tsx
│   │   ├── pages/
│   │   │   ├── Home.tsx            # Homepage with hero section
│   │   │   ├── Services.tsx        # Services page
│   │   │   ├── Portfolio.tsx       # Portfolio showcase
│   │   │   └── Contact.tsx         # Contact form
│   │   ├── App.tsx                 # Main app component
│   │   └── routes.tsx              # React Router configuration
│   ├── styles/
│   │   ├── theme.css               # Custom theme styles
│   │   └── fonts.css               # Font imports
│   └── imports/                    # Imported Figma assets
├── package.json
├── vite.config.ts
└── README.md
```

## 🎨 Customization Guide

### Updating Colors

Edit the brand colors in your components:
- **Primary Green**: `#34c759`
- **Primary Blue**: `#08f`
- **Primary Purple**: `#6366f1`

### Adding Portfolio Projects

Edit `/src/app/pages/Portfolio.tsx` and add your project to the `projects` array:

```typescript
{
  title: 'Your Project Name',
  category: 'Project Type',
  description: 'Project description',
  color: '#34c759',
  techStack: ['React', 'Node.js', 'MongoDB'],
  githubUrl: 'https://github.com/yourusername/project',
  liveUrl: 'https://your-project.com'
}
```

### Updating Contact Information

Edit `/src/app/pages/Contact.tsx` to update:
- Email address
- Phone number
- Office location
- Social media links

### Modifying Services

Edit `/src/app/pages/Services.tsx` to add or modify services in the `services` array.

## 🔗 Important Links

- **Live Website**: [https://your-website-url.com](https://your-website-url.com)
- **Documentation**: This README file
- **Report Issues**: [GitHub Issues](https://github.com/yourusername/brand-design-website/issues)

## 📧 Contact Information

- **Website**: https://branddesign.com
- **Email**: hello@branddesign.com
- **Phone**: +1 (555) 123-4567
- **Location**: 123 Creative Street, Design City, DC 12345

## 🚀 Deployment

### Deploy to Vercel (Recommended)

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your repository
4. Vercel will auto-detect Vite and deploy

### Deploy to Netlify

1. Push your code to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Connect your repository
4. Build command: `npm run build`
5. Publish directory: `dist`

### Deploy to GitHub Pages

1. Install gh-pages:
   ```bash
   npm install --save-dev gh-pages
   ```

2. Add to package.json:
   ```json
   "homepage": "https://yourusername.github.io/brand-design-website",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```

3. Deploy:
   ```bash
   npm run deploy
   ```

## 📝 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |

## 🌟 Features Roadmap

- [ ] Add blog section
- [ ] Integrate CMS for easy content management
- [ ] Add animation effects with Motion
- [ ] Implement dark mode toggle
- [ ] Add multilingual support
- [ ] Integrate analytics

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Design inspiration from modern creative agencies
- Icons by [Lucide Icons](https://lucide.dev)
- Fonts from Google Fonts (Roboto)
- Built with [Vite](https://vitejs.dev)
- Styled with [Tailwind CSS](https://tailwindcss.com)

## 💡 Tips for End Users

### Navigation
- Use the top navigation bar to switch between pages
- Click the logo to return to the homepage
- Active page is highlighted in green

### Contact Form
- All fields marked with * are required
- Form validation is built-in
- You'll receive a confirmation message after submission

### Portfolio
- Click "Code" button to view GitHub repository
- Click "Live" button to see the live demo
- Hover over cards for interactive effects

### Mobile Experience
- Fully responsive on all devices
- Touch-friendly navigation
- Optimized for mobile performance

---

**Built with ❤️ by Brand Design Team**

*Last Updated: April 5, 2026*
