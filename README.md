# HTML Fundamentals Assignment

This repository contains the complete HTML fundamentals assignment with three main questions covering semantic HTML5, forms, and tables.

## Project Structure

```
html-fundamentals-assignment/
├── question1/
│   ├── index.html          # Personal Portfolio Website
│   └── favicon.ico         # Favicon file
├── question2/
│   └── registration.html   # Course Registration Form
├── question3/
│   └── students.html       # Student Management Dashboard
├── screenshots/            # Placeholder for screenshots
└── README.md              # This file
```

## Assignment Questions

### Question 1: Personal Portfolio Website
**File:** `question1/index.html`

A comprehensive personal portfolio website featuring:
- ✅ Complete HTML5 boilerplate with meta tags
- ✅ Semantic HTML5 structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- ✅ Navigation menu with 4 links (Home, About, Projects, Contact)
- ✅ Hero section with developer name and title
- ✅ About section with professional photo and skills list
- ✅ Projects section with 3 project entries
- ✅ Education section with ordered list
- ✅ Footer with copyright and social media links
- ✅ Proper heading hierarchy (one `<h1>`, proper `<h2>`, `<h3>` order)
- ✅ All images have descriptive alt text
- ✅ Favicon link included
- ✅ HTML entities used appropriately

### Question 2: Course Registration Form
**File:** `question2/registration.html`

A comprehensive course registration form featuring:
- ✅ Complete HTML5 boilerplate
- ✅ Form with POST method and proper action
- ✅ Personal Information section (name, email, phone, DOB, profile picture)
- ✅ Academic Background section (education level, field of study, experience)
- ✅ Course Preferences section (learning mode, categories, schedule)
- ✅ Additional Information section (experience level, comments, contact method)
- ✅ Terms and Conditions section
- ✅ All form inputs have proper labels with `for` attributes
- ✅ Appropriate HTML5 input types for validation
- ✅ Required fields marked with `required` attribute
- ✅ Grouped fields using `<fieldset>` and `<legend>`
- ✅ Submit and Reset buttons included

### Question 3: Student Management Dashboard
**File:** `question3/students.html`

A comprehensive student data table featuring:
- ✅ Complete HTML5 boilerplate with semantic structure
- ✅ Proper table elements (`<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`)
- ✅ Table caption: "Computer Science Students - Batch 2024"
- ✅ Complex table headers with colspan for grouped columns
- ✅ 6 student records with realistic data
- ✅ Rowspan used for students taking multiple courses
- ✅ Colspan used for summary rows in footer
- ✅ `scope` attribute used for header cells
- ✅ Summary section with statistics using semantic elements
- ✅ Proper accessibility features

## Technical Features

### HTML5 Semantic Elements Used
- `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
- `<fieldset>`, `<legend>` for form grouping
- `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<th>`, `<td>`

### Accessibility Features
- Proper heading hierarchy maintained
- All images have meaningful alt text
- Links have descriptive text (no "click here")
- Form labels properly associated with inputs
- Table headers use `scope` attribute
- Navigation properly labeled

### Validation Features
- Email field validates email format
- Phone field accepts phone numbers
- Date field with reasonable range restrictions
- File upload accepts only image formats
- Required fields marked appropriately
- Number inputs with min/max constraints

## Browser Compatibility
All HTML files are built with modern HTML5 standards and should work in all modern browsers including:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Validation
All HTML files have been validated for:
- ✅ Proper HTML5 structure
- ✅ Semantic markup
- ✅ Accessibility standards
- ✅ Form validation attributes
- ✅ Table structure and accessibility

## Usage
1. Clone or download this repository
2. Open any HTML file in a web browser
3. For the registration form, note that it's set to POST to `/submit-registration` (backend implementation required)
4. All files are self-contained and don't require external dependencies

## Notes
- The favicon.ico file is a placeholder - replace with an actual favicon file for production use
- Placeholder images are used from placeholder.com service
- All email addresses and phone numbers are fictional
- The registration form requires backend implementation for actual submission
