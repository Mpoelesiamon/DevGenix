# 🚀 DevGenix - Modern Web Design & SEO Agency Template

A professional, modern, and fully responsive Next.js 14 website template designed for web design agencies, SEO services, and digital marketing companies. Built with cutting-edge technologies and featuring a sleek dark theme with custom Qurova typography.

![DevGenix Preview](https://img.shields.io/badge/Next.js-14.2.15-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## ✨ Features

### 🎨 **Design & UI**
- **Modern Dark Theme** with glassmorphism effects
- **Custom Qurova Typography** for unique brand identity
- **Responsive Design** optimized for all devices
- **Smooth Animations** with AOS (Animate On Scroll)
- **Interactive Components** with hover effects and transitions
- **Professional Color Scheme** with gradients and shadows

### 📱 **Multi-Page Layouts**
- **5 Different Homepage Variants** (Index 1-5)
- **OnePage Versions** for single-page websites
- **Comprehensive Page Templates**:
  - About Us
  - Services (with detailed service pages)
  - Portfolio/Projects (Grid & List views)
  - Blog (Grid, Standard, Details)
  - Team (with individual member pages)
  - Contact & FAQ
  - Pricing Plans
  - Shop/E-commerce pages

### 🛠 **Technical Features**
- **Next.js 14** with App Router
- **React 18** with latest features
- **Custom Font Integration** (Qurova font family)
- **Component-Based Architecture**
- **SEO Optimized** structure
- **Performance Optimized** with lazy loading
- **Cross-Browser Compatible**

### 🎯 **Interactive Components**
- **Hero Sections** with dynamic content
- **Service Showcases** with hover effects
- **Portfolio Galleries** with filtering
- **Testimonial Sliders** with smooth transitions
- **Counter Animations** with React CountUp
- **Progress Bars** with circular progress
- **FAQ Accordions** with smooth animations
- **Contact Forms** with validation
- **Blog System** with sidebar and pagination

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Mpoelesiamon/DevGenix.git
   cd DevGenix
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
DevGenix/
├── app/                          # Next.js 14 App Router
│   ├── about/                    # About page
│   ├── blog/                     # Blog pages
│   ├── contact/                  # Contact page
│   ├── services/                 # Services pages
│   ├── project-grid/             # Portfolio grid
│   ├── project-list/             # Portfolio list
│   ├── team/                     # Team pages
│   ├── pricing/                  # Pricing page
│   ├── shop/                     # E-commerce pages
│   ├── index1-onepage/           # OnePage variant 1
│   ├── index2/                   # MultiPage variant 2
│   ├── index3/                   # MultiPage variant 3
│   ├── index4/                   # MultiPage variant 4
│   ├── index5/                   # MultiPage variant 5
│   ├── globals.css               # Global styles with custom fonts
│   ├── layout.js                 # Root layout
│   └── page.js                   # Homepage
├── components/                   # Reusable React components
│   ├── About.js                  # About section component
│   ├── Services.js               # Services showcase
│   ├── Team.js                   # Team member display
│   ├── Blog.js                   # Blog post component
│   ├── Counter.js                # Animated counters
│   ├── CTA.js                    # Call-to-action sections
│   ├── Faq.js                    # FAQ accordion
│   ├── LatestWorks.js            # Portfolio showcase
│   ├── PageBanner.js             # Page header banners
│   ├── Priceing.js               # Pricing tables
│   ├── ProgressBar.js            # Progress indicators
│   ├── WhyChooseUs.js            # Features showcase
│   ├── WorkingProcess.js         # Process steps
│   ├── popup/                    # Modal and popup components
│   └── sliders/                  # Carousel and slider components
├── layout/                       # Layout components
│   ├── DevGenixLayout.js         # Main layout wrapper
│   ├── Header.js                 # Navigation header
│   └── Footer.js                 # Site footer
├── public/                       # Static assets
│   ├── assets/
│   │   ├── css/                  # Stylesheets
│   │   ├── fonts/                # Custom Qurova fonts
│   │   ├── images/               # Images and graphics
│   │   └── sass/                 # SASS source files
│   └── favicon.ico
├── utility/                      # Utility functions
│   ├── index.js                  # Helper functions
│   ├── sliderProps.js            # Slider configurations
│   └── useClickOutside.js        # Custom React hooks
├── package.json                  # Dependencies and scripts
├── next.config.mjs              # Next.js configuration
└── README.md                     # This file
```

## 🎨 Customization

### **Custom Font Integration**
The project includes the custom Qurova font family with multiple weights:
- **Qurova Light** (300)
- **Qurova Regular** (400)
- **Qurova Medium** (500)
- **Qurova Semibold** (600)
- **Qurova Bold** (700)

Font files are located in `public/assets/fonts/` and are automatically loaded via CSS `@font-face` declarations.

### **Styling Customization**
- **Global styles**: `app/globals.css`
- **Component styles**: Individual component files
- **SASS files**: `public/assets/sass/` for advanced styling
- **Theme colors**: Easily customizable color variables

### **Content Management**
- **Page content**: Edit individual page files in `app/`
- **Component content**: Modify component props and content
- **Images**: Replace images in `public/assets/images/`
- **Configuration**: Update settings in component files

## 🛠 Available Scripts

```bash
# Development
npm run dev          # Start development server
npm run build        # Build for production
npm run start        # Start production server
npm run lint         # Run ESLint

# Additional commands
npm run export       # Export static site
npm run analyze      # Analyze bundle size
```

## 📱 Responsive Design

The template is fully responsive and optimized for:
- **Desktop** (1200px+)
- **Tablet** (768px - 1199px)
- **Mobile** (320px - 767px)
- **Large Screens** (1400px+)

## 🎯 Performance Features

- **Image Optimization** with Next.js Image component
- **Code Splitting** for faster initial loads
- **Lazy Loading** for components and images
- **Minified Assets** in production builds
- **SEO Optimization** with proper meta tags
- **Accessibility** compliant design

## 🔧 Dependencies

### **Core Dependencies**
- `next: 14.2.15` - React framework
- `react: ^18` - UI library
- `react-dom: ^18` - DOM rendering

### **UI & Animation**
- `aos: ^2.3.4` - Animate On Scroll
- `react-bootstrap: ^1.6.1` - Bootstrap components
- `react-slick: ^0.30.2` - Carousel/slider
- `react-circular-progressbar: ^2.1.0` - Progress indicators
- `react-countup: ^6.5.3` - Animated counters
- `react-player: ^2.16.0` - Video player
- `react-visibility-sensor: ^5.1.1` - Visibility detection

## 🌐 Browser Support

- **Chrome** 90+
- **Firefox** 88+
- **Safari** 14+
- **Edge** 90+
- **Mobile browsers** (iOS Safari, Chrome Mobile)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For support, email support@devgenix.com or join our Slack channel.

## 🙏 Acknowledgments

- **Qurova Font Family** - Custom typography
- **Next.js Team** - Amazing React framework
- **React Community** - Excellent ecosystem
- **Design Inspiration** - Modern web design trends

---

**Made with ❤️ by the DevGenix Team**

*Transform your digital presence with DevGenix - Where innovation meets design.* 