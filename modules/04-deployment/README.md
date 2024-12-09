# Module 4: Website Deployment (1 Hour)

## Learning Objectives
By the end of this module, you'll be able to:
- Deploy websites using GitHub Pages
- Configure custom domains
- Understand deployment best practices
- Troubleshoot common issues

## Part 1: GitHub Pages Basics (20 mins)

### 1. Repository Setup
- Name repository: `username.github.io` (for user site)
- Or use any repo name (for project site)
- Ensure main branch has website files
- Include `index.html` in root

### 2. Enable GitHub Pages
1. Go to repository Settings
2. Scroll to "GitHub Pages" section
3. Select branch (usually `main`)
4. Choose root folder
5. Save changes

### 🔨 Exercise 1: Basic Deployment
1. Create/use repository
2. Add website files
3. Enable GitHub Pages
4. View live site

## Part 2: Configuration (20 mins)

### 1. Project Structure
```
your-repo/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── images/
│   └── logo.png
└── README.md
```

### 2. Custom Domain Setup
```bash
# 1. Add CNAME file to repo
echo "www.yourdomain.com" > CNAME

# 2. DNS Settings (at domain provider)
# Type    Name    Value
A         @       185.199.108.153
A         @       185.199.109.153
A         @       185.199.110.153
A         @       185.199.111.153
CNAME     www     username.github.io
```

### 🔨 Exercise 2: Advanced Setup
1. Organize project files
2. Add custom domain (optional)
3. Test site functionality
4. Check mobile responsiveness

## Part 3: Best Practices (15 mins)

### 1. Performance Tips
- Optimize images
- Minify CSS/JS
- Use CDN for libraries
- Enable caching

### 2. SEO Basics
```html
<!-- Add to head -->
<meta name="description" content="Your site description">
<meta name="keywords" content="your, keywords">
<meta name="author" content="Your Name">
```

### 3. Testing Checklist
- Cross-browser compatibility
- Mobile responsiveness
- Load time optimization
- Link functionality
- Form submissions

### 🔨 Exercise 3: Optimization
1. Compress images
2. Add meta tags
3. Test performance
4. Fix any issues

## Part 4: Troubleshooting (5 mins)

### Common Issues
1. 404 Page Not Found
   - Check repository settings
   - Verify index.html location
   - Wait for deployment (can take 5-10 mins)

2. Custom Domain Issues
   - Verify DNS settings
   - Check CNAME file
   - Wait for DNS propagation (24-48 hrs)

3. Style/Script Not Loading
   - Check file paths
   - Use relative paths
   - Verify file names

## Resources
- [GitHub Pages Documentation](https://docs.github.com/pages)
- [Custom Domain Guide](https://docs.github.com/pages/configuring-a-custom-domain)
- [Jekyll Themes](https://pages.github.com/themes/)

## 🎯 Final Project Prep
1. Deploy your website
2. Add custom domain (optional)
3. Optimize performance
4. Test thoroughly
5. Share with others

## Next Steps
- Explore static site generators
- Learn continuous deployment
- Add dynamic features
- Move on to Final Project! 