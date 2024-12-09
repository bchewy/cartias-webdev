# Module 5: Final Project (1 Hour)

## Project Overview
Create a multi-page educational website that showcases everything you've learned. This will be a resource you can actually use in your classroom!

## Requirements

### 1. Technical Requirements
- Minimum 4 HTML pages
- Responsive design using Bootstrap
- Version controlled with Git
- Deployed on GitHub Pages
- Custom styling with CSS
- Interactive elements

### 2. Required Pages

#### Home Page (`index.html`)
```html
<!-- Example structure -->
<nav class="navbar">
    <!-- Navigation -->
</nav>

<header class="hero">
    <!-- Hero section with CTA -->
</header>

<main>
    <!-- Featured content -->
</main>

<footer>
    <!-- Footer content -->
</footer>
```

#### Content Pages (minimum 3)
- Lesson plans page
- Resources page
- About/Contact page

### 3. Required Features
- Navigation menu
- Hero section
- Card components
- Contact form
- Social media links
- Responsive images
- Interactive elements

## Project Steps (45 mins)

### 1. Setup (5 mins)
```bash
# Create project structure
mkdir my-teaching-site
cd my-teaching-site
git init
```

### 2. Development (30 mins)

#### HTML Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Teaching Resource</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="css/styles.css" rel="stylesheet">
</head>
<body>
    <!-- Your content -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

#### CSS Organization
```css
/* styles.css */
/* Global styles */
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
}

/* Layout */
.container { /* ... */ }

/* Components */
.card { /* ... */ }

/* Responsive */
@media (max-width: 768px) { /* ... */ }
```

### 3. Deployment (10 mins)
1. Create GitHub repository
2. Push code
3. Enable GitHub Pages
4. Test deployment

## Evaluation Checklist

### Technical Implementation
- [ ] Valid HTML5
- [ ] Responsive design
- [ ] Bootstrap components
- [ ] Custom CSS
- [ ] Git version control
- [ ] Successful deployment

### Content & Design
- [ ] Clear navigation
- [ ] Engaging content
- [ ] Consistent styling
- [ ] Mobile-friendly
- [ ] Fast loading
- [ ] Working links

### Bonus Features
- Custom domain
- Animations
- Dark mode
- Search functionality
- PDF resources
- Student portal

## Example Project Structure
```
my-teaching-site/
├── index.html
├── lessons.html
├── resources.html
├── contact.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── images/
│   ├── hero.jpg
│   └── resources/
├── documents/
│   └── lesson-plans/
└── README.md
```

## Resources & Tips

### Design Resources
- [Google Fonts](https://fonts.google.com)
- [Font Awesome](https://fontawesome.com)
- [Unsplash](https://unsplash.com) (free images)
- [Coolors](https://coolors.co) (color schemes)

### Code Examples

#### Responsive Navigation
```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
        <a class="navbar-brand" href="#">TeachHub</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="index.html">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="lessons.html">Lessons</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="resources.html">Resources</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="contact.html">Contact</a>
                </li>
            </ul>
        </div>
    </div>
</nav>
```

#### Resource Card
```html
<div class="card">
    <img src="images/resource-thumb.jpg" class="card-img-top" alt="Resource">
    <div class="card-body">
        <h5 class="card-title">Lesson Plan Template</h5>
        <p class="card-text">A customizable template for creating engaging lesson plans.</p>
        <a href="#" class="btn btn-primary">Download</a>
    </div>
</div>
```

## Submission Guidelines
1. GitHub repository URL
2. Live site URL
3. Brief project description
4. List of features implemented
5. Any challenges faced
6. Future improvements planned

## Next Steps
- Share with colleagues
- Gather feedback
- Add more resources
- Keep updating
- Start using in class! 