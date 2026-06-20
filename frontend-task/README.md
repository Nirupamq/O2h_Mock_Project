# TaskFlow - Responsive SaaS Landing Page

A modern, responsive SaaS landing page built as part of a Front-End Developer assessment. The project demonstrates responsive web design, accessibility, JavaScript functionality, API integration, and performance optimization using HTML5, CSS3, and Vanilla JavaScript.

## Features

### Hero Section

* Responsive navigation bar
* Logo and navigation links
* Call-to-action button
* Hero content and image
* Dark mode toggle

### Features Section

* 6 feature cards
* Responsive grid layout
* Hover effects and modern UI

### Pricing Section

* Starter Plan
* Professional Plan (featured)
* Enterprise Plan
* Highlighted recommended plan

### Contact Section

* Name, Email, and Message fields
* Client-side form validation
* Email format validation
* Error message handling

### Bonus: Blog Posts API Integration

* Fetches latest posts from JSONPlaceholder API
* Displays 6 blog posts
* Loading state handling
* Error state handling

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Flexbox
* CSS Grid
* Media Queries
* Local Storage API
* Fetch API

## Responsive Design

The website is fully responsive and optimized for:

### Desktop

* Multi-column layouts
* Full navigation menu

### Tablet

* Two-column layouts where appropriate

### Mobile

* Single-column layouts
* Animated hamburger menu
* Mobile-friendly navigation

## Accessibility Features

* Semantic HTML structure
* ARIA labels
* Keyboard navigation support
* Proper heading hierarchy
* Alt text for images
* Color contrast considerations

## Performance Optimizations

* Lazy-loaded images
* Optimized CSS and JavaScript
* Efficient DOM manipulation
* Reusable components and styles

## Project Structure

```text
frontend-task/
├── index.html
├── css/
│   ├── style.css
│   └── responsive.css
├── js/
│   └── app.js
├── images/
├── README.md
└── .gitignore
```

## JavaScript Functionalities

### Mobile Navigation

* Hamburger menu toggle
* Responsive menu behavior
* Auto-close on navigation selection

### Form Validation

* Required field validation
* Email format validation
* Error handling

### Dark Mode

* Theme switching
* Preference persistence using localStorage

### API Integration

* Fetches blog data from:
  https://jsonplaceholder.typicode.com/posts

## Setup Instructions

1. Clone the repository

```bash
git clone <repository-url>
```

2. Open the project folder

```bash
cd frontend-task
```

3. Open `index.html` in a browser

No additional dependencies or build tools are required.

## Git Commit Workflow

* Initial layout setup
* Responsive navbar completed
* Feature section added
* Form validation implemented
* Final optimization and cleanup

## Author

Developed as part of a Front-End Developer Assessment for TaskFlow SaaS Landing Page.
