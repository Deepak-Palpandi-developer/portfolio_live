# Portfolio Website

A modern, responsive portfolio website built with Angular, showcasing professional projects, skills, and experience.

## 🚀 Overview

This is a personal portfolio website designed to present professional work, technical skills, and career achievements in an engaging and interactive manner. The site features a clean, modern design with smooth animations and responsive layouts.

## 📋 Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional interface using Tailwind CSS
- **Performance Optimized**: Pre-rendered routes for faster load times
- **Font Optimization**: Uses Inter font family with multiple weights for elegant typography
- **Image Assets**: Includes project screenshots and technology icons

## 🛠️ Technologies Used

### Frontend Framework
- **Angular**: Modern web application framework

### Styling
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development
- **Custom CSS Properties**: CSS variables for consistent theming

### Typography
- **Inter Font**: Modern, professional font family with multiple weights (300-800)

### Technologies Showcased
- Angular
- Docker
- .NET
- TypeScript
- PostgreSQL
- Redis
- GitHub
- LinkedIn

## 📁 Project Structure

```
portfolio_live/
├── index.html                    # Main HTML entry point
├── main-MHMAYUFS.js             # Main application bundle
├── styles-HSPVESGT.css          # Compiled styles
├── favicon.ico                   # Site favicon
├── 3rdpartylicenses.txt         # Third-party license information
├── prerendered-routes.json      # Pre-rendered routes configuration
├── DeepakPalpandi.pdf           # Resume/CV
├── img/                          # Image assets
│   ├── emr.jpg                  # Project screenshot
│   └── lims.png                 # Project screenshot
└── svg/                          # Technology icons
    ├── angular.svg
    ├── docker.svg
    ├── dotnet.svg
    ├── Github.svg
    ├── LinkedIN.svg
    ├── postgresql.svg
    ├── redis.svg
    └── typescript.svg
```

## 🌐 Deployment

This is a production-ready build of the portfolio website. The site is configured to be served from the `/portfolio_live/` base path.

### Hosting Options

The site can be deployed to:
- **GitHub Pages**: Ideal for static hosting
- **Netlify/Vercel**: Modern hosting platforms with CI/CD
- **Traditional Web Servers**: Apache, Nginx, or any static file server
- **Cloud Storage**: AWS S3, Google Cloud Storage, Azure Blob Storage

### Deployment Steps

1. **Static Hosting**:
   ```bash
   # Simply upload all files to your web server
   # Ensure the base href matches your hosting path
   ```

2. **GitHub Pages**:
   ```bash
   # Push to gh-pages branch
   git add .
   git commit -m "Deploy portfolio"
   git push origin gh-pages
   ```

3. **Web Server Configuration** (Nginx example):
   ```nginx
   server {
       listen 80;
       server_name yourdomain.com;
       
       location /portfolio_live/ {
           root /path/to/parent/directory;
           index index.html;
           try_files $uri $uri/ /portfolio_live/index.html;
       }
   }
   ```

## 🔧 Configuration

- **Base HREF**: The application is configured with base href `/portfolio_live/`
- **Fonts**: Google Fonts (Inter) loaded with font-display swap for optimal performance
- **SEO**: Includes proper meta tags and viewport configuration

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

Third-party licenses are documented in `3rdpartylicenses.txt`.

## 👤 Author

**Deepak Palpandi**

- GitHub: [Profile Link]
- LinkedIn: [Profile Link]
- Resume: Available in `DeepakPalpandi.pdf`

## 🤝 Contributing

This is a personal portfolio project. For suggestions or issues, please reach out directly.

## 📞 Contact

For professional inquiries, collaboration opportunities, or questions, please refer to the contact information provided on the website or in the resume.

---

**Note**: This is a production build. For development or source code, please refer to the source repository.
