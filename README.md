# VR Club Website Template

A modern, responsive website template designed for VR clubs in schools and educational institutions. This template provides everything you need to showcase your VR club's mission, projects, and impact.

## 📱 Live Preview

https://vrclubsofamerica.github.io/vrclubwebsite/

## 🎯 Features

- Modern, responsive design that works on all devices
- Clean and professional layout
- Pre-built pages for essential content:
  - Home page with impact statistics and mission statement
  - Projects showcase with video integration
  - About page with team profiles
  - "Start a VR Club" guide
- Customizable CSS styling
- Mobile-friendly navigation
- Footer with contact information

## 🚀 Getting Started

1. Clone or download this template
2. Replace the content with your club's information
3. Deploy to your preferred hosting service

## 📁 File Structure

```
VRClubWebsite/
├── css/
│   ├── about.css      # About page styles
│   ├── hero.css       # Hero section styles
│   ├── navbar.css     # Navigation styles
│   ├── projects.css   # Projects page styles
│   ├── start.css      # Start a Club page styles
│   └── style.css      # Global styles
├── images/
│   ├── vrlogo.png     # Club logo
├── about.html         # About page
├── index.html         # Home page
├── projects.html      # Projects showcase
└── start.html         # Start a Club guide
```

## 🎨 Customization Guide

### 1. Basic Information
- Update the club name and contact email throughout all HTML files
- Replace copyright year in footer sections
- Update meta descriptions for SEO

### 2. Logo
- Replace `images/vrlogo.png` with your club's logo
- Recommended size: maintain aspect ratio, max height 50px
- Update all `<img>` tags with your logo's alt text

### 3. Content Sections

#### Homepage (index.html)
- Update statistics in the hero section
- Modify impact numbers and statements
- Customize mission statement
- Add your own team members

#### Projects Page (projects.html)
- Replace YouTube video embeds with your project videos
- Update project descriptions
- Modify project tags
- Add new project cards as needed

#### About Page (about.html)
- Update team member information
- Modify core values
- Customize mission statement
- Add your own team photos/avatars

#### Start a Club Page (start.html)
- Customize setup instructions
- Update resource links
- Modify step-by-step guide

### 4. Styling

The CSS is organized into modular files for easy customization:

- `style.css`: Global styles and variables
- `navbar.css`: Navigation styling
- `hero.css`: Hero section styling
- `about.css`: About page specific styles
- `projects.css`: Projects page specific styles
- `start.css`: Start a Club page specific styles

To change colors, modify the CSS variables in `style.css`:

```css
:root {
  /* Update these colors to match your brand */
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
  /* etc */
}
```

## 📱 Responsive Design

The template is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones

No additional configuration needed for responsiveness.

## 🔧 Technical Requirements

- Basic HTML/CSS knowledge for customization
- Web hosting service
- Text editor (VS Code recommended)
- Basic understanding of responsive design

## 📝 License

This template is free to use for any VR club. Please maintain the following:
- Credit the original template in your website's footer
- Keep the open-source spirit by sharing your improvements
