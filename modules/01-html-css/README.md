# Module 1: HTML & CSS Fundamentals (1 Hour)

## Learning Objectives
By the end of this module, you'll be able to:
- Create HTML documents with proper structure
- Use common HTML elements
- Style elements using CSS
- Understand the CSS box model

## Part 1: HTML Basics (25 mins)

### 1. Basic HTML Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My First Webpage</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```

### 2. Essential HTML Elements
- Headings: `<h1>` to `<h6>`
- Paragraphs: `<p>`
- Links: `<a href="url">text</a>`
- Images: `<img src="image.jpg" alt="description">`
- Lists: `<ul>`, `<ol>`, `<li>`
- Tables: `<table>`, `<tr>`, `<td>`

### 🔨 Exercise 1: Create Your "About Me" Page
Create a file named `about.html` with:
- Your name as a heading
- A short bio paragraph
- A list of your hobbies
- A favorite quote
- An image

## Part 2: CSS Styling (25 mins)

### 1. CSS Syntax
```css
selector {
    property: value;
}
```

### 2. Three Ways to Add CSS
```html
<!-- 1. Inline CSS -->
<p style="color: blue;">Blue text</p>

<!-- 2. Internal CSS -->
<style>
    p { color: blue; }
</style>

<!-- 3. External CSS (preferred) -->
<link rel="stylesheet" href="styles.css">
```

### 3. Common CSS Properties
- `color`: Text color
- `background-color`: Background color
- `font-size`: Text size
- `margin`: Outside spacing
- `padding`: Inside spacing
- `border`: Element borders
- `width/height`: Element dimensions

### 4. The Box Model
Every element has:
- Content
- Padding
- Border
- Margin

### 🔨 Exercise 2: Style Your About Page
Create `styles.css` and add:
- Custom colors
- Different font sizes
- Margins and padding
- Borders around elements

## Part 3: Hands-on Project (10 mins)
Enhance your "About Me" page with:
- A navigation menu
- Multiple sections
- Custom fonts
- Hover effects
- Responsive design basics

## Resources
- [MDN Web Docs](https://developer.mozilla.org)
- [W3Schools HTML](https://www.w3schools.com/html)
- [W3Schools CSS](https://www.w3schools.com/css)

## 🎯 Mini-Challenge
Create a simple portfolio layout with:
- Header with navigation
- About section
- Skills section (using lists)
- Contact form
- Footer

## Next Steps
- Experiment with different CSS properties
- Try CSS Grid and Flexbox
- Practice with more HTML elements
- Move on to Module 2: Bootstrap! 