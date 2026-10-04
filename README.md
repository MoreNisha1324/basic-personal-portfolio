
# Nisha More - Basic Personal Portfolio

A clean, modern and responsive single-page portfolio website built using HTML and CSS. This website showcases my educational background, technical skills, academic projects and professional interests.

Hosted using GitHub Pages.

## ✨ Features

- **Modern & Responsive Design**: Compatible with mobile, tablet and desktop devices.
- **Single-Page Layout**: Easy navigation between different sections.
- **Clean Sections**:
  - Hero section with name and introduction.
  - About section with personal information.
  - Education section with academic details.
  - Technical skills showcase.
  - Portfolio section with academic projects.
  - Contact section with email and social links.
  - Footer with copyright information.
- **Accessible**: Semantic HTML and keyboard-friendly navigation.
- **SEO Friendly**: Page title and meta information.
- **No Complex Dependencies**: Built using HTML and CSS.
- **GitHub Pages Ready**: Hosted directly from a GitHub repository.

## 👩‍💻 About Me

Hello! I'm **Nisha More**, an Electronics and Telecommunication Engineering student at the International Institute of Information Technology (I2IT), Pune.

I have a strong interest in Software Development, Data Engineering and emerging technologies. I enjoy solving problems, learning new technologies and building practical applications.

## 🎓 Education

- **Degree:** Bachelor of Engineering (B.E.)
- **Branch:** Electronics and Telecommunication Engineering
- **College:** International Institute of Information Technology (I2IT), Pune
- **Academic Duration:** 2023 - 2027

## 🛠️ Technical Skills

- **Programming Languages:** Java, Python
- **Web Technologies:** HTML, CSS, JavaScript
- **Database:** MySQL, PostgreSQL, SQL
- **Data Analytics:** Pandas, Power BI
- **Tools:** Git, GitHub, VS Code
- **Other Technologies:** Blockchain, Web3, Cloud Computing

## 🚀 Projects

### 1. PoisonProof - Federated Learning Security with Blockchain

- Developed a project concept combining Artificial Intelligence, Federated Learning and Blockchain.
- Focuses on identifying suspicious model updates in collaborative machine learning.
- Uses blockchain to maintain tamper-evident records of submitted model updates.
- **Technologies:** Python, PyTorch, Flower, Solidity, Hardhat, Web3.

### 2. E-Commerce Data Engineering Pipeline

- Developed an ETL pipeline to process and transform e-commerce data.
- Used Python and Pandas for data processing.
- Designed a PostgreSQL database for analytical data storage.
- Created a Power BI dashboard to visualize business insights.
- **Technologies:** Python, Pandas, PostgreSQL, SQL, Power BI.

### 3. Pharmacy Management System

- Developed a pharmacy management application to manage medicine and related records.
- Implemented database operations to store and retrieve information.
- **Technologies:** PHP, MySQL, XAMPP.

## 📁 Folder Structure

```text
basic-personal-portfolio/
├── index.html          # Main HTML file with website sections
├── style.css           # Stylesheet for website design
├── assets/             # Images and icons folder
│   ├── profile.jpg     # Profile photo
│   ├── project-1.jpg   # PoisonProof project image
│   ├── project-2.jpg   # E-Commerce project image
│   ├── project-3.jpg   # Pharmacy project image
│   ├── og-image.jpg    # Social sharing image
│   ├── favicon.png     # Website favicon
│   ├── html-icon.svg   # HTML skill icon
│   ├── css-icon.svg    # CSS skill icon
│   ├── js-icon.svg     # JavaScript skill icon
│   ├── git-icon.svg    # Git skill icon
│   └── other icons
├── README.md           # Project documentation
└── LICENSE             # Project license
```

## 🎨 Customization Guide

### Update Personal Information

1. **Open `index.html`** and update the following:
   - Update `<meta name="author">` with your name.
   - Update the website title.
   - Replace the navigation brand with "Nisha More".
   - Update the hero section with your name and introduction.
   - Update the About section with your personal information.
   - Add your educational details.
   - Update the technical skills section.
   - Replace the sample projects with your academic projects.
   - Update the contact email and social media links.
   - Update the footer copyright information.

2. **Update `style.css`** to modify colours and fonts:

   ```css
   /* Main theme colours */
   --color-primary: #6366f1;
   --color-primary-dark: #4f46e5;
   --color-text: #1f2937;
   --color-background: #ffffff;

   /* Font family */
   --font-family: 'Poppins', sans-serif;
   ```

3. **Replace Images** in the `assets/` folder:
   - `profile.jpg`: Personal photograph.
   - `project-1.jpg`: PoisonProof project screenshot.
   - `project-2.jpg`: E-Commerce project screenshot.
   - `project-3.jpg`: Pharmacy Management project screenshot.
   - `og-image.jpg`: Social sharing image.
   - `favicon.png`: Website favicon.

### Customize Skills

In `index.html`, modify the skills section:

- Add programming languages and technologies.
- Update skill names and icons.
- Adjust progress bar widths.
- Add or remove skill items as required.

### Update Portfolio Projects

In `index.html`, modify the project section:

- Replace project titles and descriptions.
- Update project images.
- Add GitHub repository links.
- Add project demonstrations where available.
- Add more projects by duplicating the existing project card structure.

### Change Color Scheme

Edit the CSS variables in `style.css`:

```css
/* Blue/Purple theme */
--color-primary: #6366f1;

/* Alternative themes */
/* Green theme: #10b981 */
/* Orange theme: #f97316 */
/* Pink theme: #ec4899 */
/* Teal theme: #14b8a6 */
```

### Change Fonts

1. Replace the Google Fonts link in `index.html`.
2. Update `--font-family` in `style.css`.

Popular alternatives:

- `Roboto` - Modern and clean.
- `Inter` - Excellent for user interfaces.
- `Montserrat` - Bold and professional.
- `Open Sans` - Highly readable.

## 🚀 Deployment to GitHub Pages

This project is hosted using GitHub Pages.

### Option 1: GitHub Web Interface

1. Create a GitHub account.
2. Select a portfolio project from GitHub.
3. Fork the repository into your GitHub account.
4. Customize the HTML and CSS files.
5. Open repository Settings.
6. Select Pages from the sidebar.
7. Under Source, select `Deploy from a branch`.
8. Select the `main` branch.
9. Select the `/(root)` folder.
10. Click Save.
11. Wait for GitHub Pages deployment to complete.
12. Open the generated website URL.

### Option 2: Git Command Line

```bash
# Initialize Git repository
git init

# Add all project files
git add .

# Commit changes
git commit -m "Update personal portfolio website"

# Add remote repository
git remote add origin https://github.com/MoreNisha1324/basic-personal-portfolio.git

# Push code to GitHub
git push -u origin main
```

### Live Website

**Hosted Website:**

https://morenisha1324.github.io/basic-personal-portfolio/

**GitHub Repository:**

https://github.com/MoreNisha1324/basic-personal-portfolio

### Custom Domain (Optional)

1. Open repository Settings → Pages.
2. Find the Custom domain section.
3. Enter your domain name.
4. Configure DNS records with your domain provider.

## 🛠️ Testing & Validation

### HTML Validation

Visit [W3C HTML Validator](https://validator.w3.org/) and enter the website URL.

### CSS Validation

Visit [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) and enter the website URL.

### Accessibility Check

- Use the WAVE Web Accessibility Tool.
- Test keyboard navigation.
- Verify image alternative text.
- Check readability and contrast.

### Responsive Testing

Test the website on different screen sizes:

- Mobile: 375px, 414px.
- Tablet: 768px, 1024px.
- Desktop: 1280px, 1920px.

### Browser Compatibility

Test on:

- Google Chrome.
- Microsoft Edge.
- Mozilla Firefox.
- Safari.
- Mobile browsers.

## 🎯 Future Improvements

- Add more academic and personal projects.
- Include GitHub links for individual projects.
- Add a downloadable resume.
- Improve mobile responsiveness.
- Add animations and interactive elements.
- Integrate a working contact form.

## 📄 License

This project uses the license included in the original GitHub repository. Refer to the `LICENSE` file for the applicable terms.

## 🙏 Credits

The initial portfolio template was obtained from the GitHub repository by [Hidden-Sect](https://github.com/Hidden-Sect) and customized for my personal portfolio and academic project demonstration.

## 📧 Contact

**Nisha More**

Electronics and Telecommunication Engineering Student

International Institute of Information Technology (I2IT), Pune.

GitHub: https://github.com/MoreNisha1324

Portfolio: https://morenisha1324.github.io/basic-personal-portfolio/

---

**Made with ❤️ by Nisha More**
