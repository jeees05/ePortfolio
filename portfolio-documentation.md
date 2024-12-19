# Personal ePortfolio Documentation

## Overview
This ePortfolio is a clean, responsive personal portfolio website built using HTML and modern CSS frameworks. It showcases the work and skills of Jelhoney A. Rollan, a 3rd-year Computer Science student. The portfolio features a personal introduction, project showcase, and a contact form, all styled with a professional pink-themed color scheme.

## Key Features
- Responsive header with profile picture and introduction
- About Me section highlighting current learning journey
- Project showcase with hover effects and GitHub links
- Interactive contact form with form validation
- Mobile-responsive design
- Smooth animations and transitions

## Technologies Used
- **HTML5** - Core structure and semantic markup
- **Tailwind CSS (v2.2.19)** - Utility-first CSS framework for styling
- **JavaScript** - Form handling and interactive elements
- **Google Fonts** - Typography
- **GitHub** - Version control and project hosting

## Project Structure
```
/
├── index.html          # Main HTML file
├── assets/            # Image assets directory
│   └── profile.jpg    # Profile picture
│   └── project1.jpg   # Project thumbnails
│   └── project2.jpg
│   └── project3.jpg
└── README.md          # Project documentation
```

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone [your-repository-url]
   cd [repository-name]
   ```

2. **Dependencies**
   - No local dependencies needed as Tailwind CSS is loaded via CDN

3. **Local Development**
   - Open `index.html` in a web browser
   - For live development, use a local server:
     ```bash
     python -m http.server 8000
     # or
     php -S localhost:8000
     ```

## Customization Guide

### Modifying the Theme
1. Update the color scheme by changing Tailwind CSS classes:
   - Primary color: `bg-pink-400`
   - Secondary colors: `bg-pink-100`, `text-pink-500`
   - Background colors: `bg-gray-50`, `bg-white`

### Adding New Projects
1. Duplicate the project card structure in the Projects section:
   ```html
   <div class="project-card bg-white rounded-lg shadow overflow-hidden">
       <img src="path/to/image" alt="Project Name" class="w-full h-40 object-cover">
       <div class="p-4">
           <h3 class="font-bold">Project Name</h3>
           <p class="text-gray-600 text-sm mt-1">Project Description</p>
           <a href="github-link" class="text-pink-500 text-sm mt-2 inline-block">See on GitHub →</a>
       </div>
   </div>
   ```

## Contributing Guidelines
1. Fork the repository
2. Create a new branch for your feature: `git checkout -b feature/YourFeature`
3. Make your changes
4. Test thoroughly
5. Submit a pull request with a detailed description of your changes

## Future Improvements
- Add dark mode support
- Implement a blog section
- Add project filtering capabilities
- Integrate a backend for the contact form
- Add more interactive elements and animations
- Implement SEO optimization

## License
© 2024 Jelhoney A. Rollan. All rights reserved.
