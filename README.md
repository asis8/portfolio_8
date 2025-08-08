# Developer Portfolio Website

A modern, responsive portfolio website built with React and Tailwind CSS, featuring dark/light mode toggle, smooth animations, and a working contact form.

## ✨ Features

- **Responsive Design**: Mobile-first approach with beautiful layouts on all devices
- **Dark/Light Mode**: Toggle between themes with system preference detection
- **Smooth Animations**: Framer Motion animations with scroll-triggered effects
- **Contact Form**: Working contact form using EmailJS integration
- **Modern UI**: Clean, professional design with gradient accents
- **SEO Optimized**: Meta tags and Open Graph support
- **Fast Performance**: Optimized for speed and accessibility

## 🚀 Sections

- **Hero**: Introduction with profile image, CTA buttons, and social links
- **About**: Personal bio with stats and animated elements
- **Projects**: Showcase of 6 projects with GitHub and live demo links
- **Skills**: Technology stack with progress bars and icons
- **Contact**: Working contact form with EmailJS integration
- **Footer**: Social links, quick navigation, and copyright

## 🛠️ Technologies Used

- **Frontend**: React 18, Tailwind CSS, Framer Motion
- **Icons**: Lucide React
- **Form Handling**: EmailJS
- **Deployment**: Vercel/GitHub Pages ready
- **Development**: Create React App

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm start
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## ⚙️ Configuration

### EmailJS Setup

1. Create an account at [EmailJS](https://www.emailjs.com/)
2. Create a new service and template
3. Update the EmailJS credentials in `src/components/Contact.js`:
   ```javascript
   const result = await emailjs.sendForm(
     'YOUR_SERVICE_ID',    // Replace with your service ID
     'YOUR_TEMPLATE_ID',   // Replace with your template ID
     formRef.current,
     'YOUR_PUBLIC_KEY'     // Replace with your public key
   );
   ```

### Customization

1. **Personal Information**: Update all instances of placeholder text:
   - Name, title, bio in components
   - Contact information
   - Social media links
   - Resume download link

2. **Images**: Add your images to the `public` folder:
   - `profile.jpg` - Hero section profile image
   - `about-image.jpg` - About section image
   - `project1.jpg` to `project6.jpg` - Project images
   - `resume.pdf` - Your resume file

3. **Projects**: Update the projects array in `src/components/Projects.js` with your actual projects

4. **Skills**: Modify the skills and technologies in `src/components/Skills.js`

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Deploy automatically with each push

### GitHub Pages

1. Update the `homepage` field in `package.json`
2. Install gh-pages: `npm install --save-dev gh-pages`
3. Deploy: `npm run deploy`

### Netlify

1. Build the project: `npm run build`
2. Drag and drop the `build` folder to [Netlify](https://netlify.com)

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🎨 Color Scheme

The portfolio uses a modern blue-purple gradient theme:
- Primary: Blue (#3b82f6)
- Secondary: Purple (#8b5cf6)
- Accent: Various gradient combinations

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

If you have any questions or need help customizing the portfolio, feel free to reach out:

- Email: your.email@example.com
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourusername)

---

**Made with ❤️ using React and Tailwind CSS**
