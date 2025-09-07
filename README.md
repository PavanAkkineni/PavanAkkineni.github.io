# Pavan Akkineni's Portfolio Website

A professional portfolio website showcasing my academic journey, work experience, projects, and achievements as a Computer Science graduate student at UNC Chapel Hill.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Clean Academic Style**: Professional design inspired by academic portfolio websites
- **Multiple Pages**: Home, Education, Experience, Projects, Resume, and Contact sections
- **Professional Certifications**: Showcases Databricks, AWS, and Oracle certifications
- **Project Showcase**: Detailed descriptions of key projects including MatchPlayer and Prism LLM
- **Contact Information**: Easy ways to connect via email, LinkedIn, and GitHub

## 🚀 Quick Start

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/PavanAkkineni/PavanAkkineni.github.io.git
   cd PavanAkkineni.github.io
   ```

2. **Add your assets:**
   - Place your profile photo as `assets/profile.jpg`
   - Add your resume as `assets/resume.pdf`
   - Add certification badges in the `assets/` folder
   - Add UNC logo as `assets/unc-logo.png`

3. **Run the local server:**
   ```bash
   python server.py
   ```
   The website will automatically open in your browser at `http://localhost:8000`

   **Alternative method (if Python is not available):**
   - Simply open `index.html` in your web browser
   - Or use VS Code with Live Server extension

## 📁 Project Structure

```
portfolio/
├── index.html          # Homepage
├── education.html      # Education and certifications
├── experience.html     # Work experience
├── projects.html       # Project showcase
├── contact.html        # Contact information
├── css/
│   └── style.css      # Main stylesheet
├── js/
│   └── script.js      # JavaScript for interactivity
├── assets/
│   ├── profile.jpg    # Your profile photo (to be added)
│   ├── resume.pdf     # Your resume (to be added)
│   ├── unc-logo.png   # UNC logo (to be added)
│   ├── databricks-cert.png  # Databricks certification badge
│   ├── aws-cert.png   # AWS certification badge
│   └── oracle-cert.png # Oracle certification badge
├── server.py          # Local development server
└── README.md          # This file
```

## 🚢 Deployment to GitHub Pages

1. **Create a new repository on GitHub:**
   - Name it `[your-username].github.io` (e.g., `PavanAkkineni.github.io`)
   - Make it public

2. **Push your code:**
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio website"
   git branch -M main
   git remote add origin https://github.com/[your-username]/[your-username].github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - Click Save

4. **Access your website:**
   - Your site will be available at `https://[your-username].github.io`
   - It may take a few minutes for the site to become available

## 🎨 Customization

### Updating Content
- Edit the HTML files directly to update your information
- Modify `css/style.css` to change colors, fonts, or layout
- Update `js/script.js` for additional interactivity

### Color Scheme
The website uses CSS variables for easy theming. Edit these in `css/style.css`:
```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #f39c12;
    --text-color: #333;
    --light-bg: #f8f9fa;
}
```

## 📝 Adding Your Assets

1. **Profile Photo:**
   - Add a professional photo as `assets/profile.jpg`
   - Recommended: 500x500px minimum, square format

2. **Resume:**
   - Save your resume as `assets/resume.pdf`
   - The Resume link in navigation will open this PDF

3. **Certification Badges:**
   - Add official certification badges to the `assets/` folder
   - Update image paths in HTML if filenames differ

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with flexbox and grid
- **JavaScript**: Vanilla JS for interactivity
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available for personal use.

## 👤 Contact

- **Email:** pavanchowdary.akkineni@gmail.com
- **LinkedIn:** [linkedin.com/in/pavan-akkineni](https://www.linkedin.com/in/pavan-akkineni/)
- **GitHub:** [github.com/PavanAkkineni](https://github.com/PavanAkkineni)

---

Built with ❤️ by Pavan Akkineni
