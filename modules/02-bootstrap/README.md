# Module 2: Bootstrap Magic (1 Hour)

## Learning Objectives
By the end of this module, you'll be able to:
- Use Bootstrap's grid system
- Implement responsive design
- Add Bootstrap components
- Customize Bootstrap elements

## Part 1: Getting Started with Bootstrap (15 mins)

### 1. Adding Bootstrap
```html
<!-- In your HTML head -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Before closing body tag -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
```

### 2. Basic Template
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Site</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container">
        <!-- Content here -->
    </div>
    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## Part 2: Grid System (20 mins)

### 1. Basic Grid
```html
<div class="container">
    <div class="row">
        <div class="col-sm-6">Half width on small screens</div>
        <div class="col-sm-6">Half width on small screens</div>
    </div>
</div>
```

### 2. Responsive Breakpoints
- `col-sm-`: ≥576px
- `col-md-`: ≥768px
- `col-lg-`: ≥992px
- `col-xl-`: ≥1200px

### 🔨 Exercise 1: Grid Layout
Create a responsive layout with:
- Header (full width)
- 3-column content area
- Sidebar (1/3 width)
- Main content (2/3 width)
- Footer (full width)

## Part 3: Components (20 mins)

### 1. Navigation
```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
        <a class="navbar-brand" href="#">Logo</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <!-- More nav items -->
            </ul>
        </div>
    </div>
</nav>
```

### 2. Common Components
- Buttons: `btn btn-primary`
- Cards: `card`
- Alerts: `alert alert-success`
- Forms: `form-control`
- Modals: `modal`

### 🔨 Exercise 2: Component Integration
Add to your layout:
- Navigation bar
- Hero section with jumbotron
- Card grid
- Contact form
- Footer with links

## Part 4: Utilities (5 mins)
- Spacing: `m-` (margin), `p-` (padding)
- Colors: `text-primary`, `bg-success`
- Display: `d-flex`, `d-none`
- Text: `text-center`, `fw-bold`
- Border: `border`, `rounded`

## Resources
- [Bootstrap Docs](https://getbootstrap.com/docs/)
- [Bootstrap Examples](https://getbootstrap.com/docs/5.3/examples/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)

## 🎯 Mini-Project
Create a responsive landing page with:
- Sticky navigation
- Hero section with CTA
- Feature cards
- Testimonial carousel
- Contact form
- Footer with social links

## Next Steps
- Explore more Bootstrap components
- Practice responsive design
- Customize Bootstrap with Sass
- Move on to Module 3: Git & GitHub! 