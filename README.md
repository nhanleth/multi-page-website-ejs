# Multi-Page Website with Express.js, EJS, and Partials

This project is a multi-page website built using **Express.js** and **EJS** templating, focusing on the use of EJS partials for consistent layouts. It is based on Section 4.3 of the course curriculum.

## Features

- Express.js server for routing and static file serving
- EJS templating engine for dynamic HTML rendering
- Consistent header and footer using EJS partials
- Modern, unified color scheme and improved layout
- Responsive and accessible design

## Project Structure

```
Backend/4.3+EJS+Partials/
├── index.js                # Express server setup
├── package.json            # Project dependencies
├── public/
│   └── styles/
│       ├── content.css     # Page-specific styles
│       └── layout.css      # Layout and navigation styles
├── views/
│   ├── index.ejs           # Home page
│   ├── about.ejs           # About page
│   ├── contact.ejs         # Contact page
│   └── partials/
│       ├── header.ejs      # Header partial
│       └── footer.ejs      # Footer partial
└── ...
```

## How to Run

1. **Install dependencies:**
   ```bash
   npm install
   ```
2. **Start the server:**
   ```bash
   node index.js
   ```
3. **Open your browser:**
   Visit `http://localhost:3000` to view the website.

## Customization

- Update styles in `public/styles/content.css` and `public/styles/layout.css` for color and layout changes.
- Edit EJS files in `views/` to modify page content or structure.
- Add new pages by creating new EJS files and updating routes in `index.js`.

## Screenshots

![Home Page](public/images/cat.jpeg)
