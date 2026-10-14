# Bostami Portfolio React App

A modern, responsive portfolio template built with React and Tailwind CSS for creatives, developers, and professionals who want a polished personal brand presence.

## Overview

This project is a portfolio website template with multiple home layouts, resume sections, work showcases, blog pages, and contact forms. It is designed for personal branding and can be customized to fit a developer, designer, freelancer, or agency portfolio.

## Features

- Responsive portfolio layout
- Multi-page navigation for home, about, resume, portfolio, blog, and contact
- Modern dark-themed aesthetic with clean typography
- Animated sections using AOS
- Reusable context-based app state
- React Router-based page structure
- Tailwind CSS setup for styling flexibility
- Contact form support with toast notifications
- Multiple preview/home variations included in the template

## Tech Stack

- React 18
- React Router DOM
- Tailwind CSS
- AOS animations
- React Slick + Slick Carousel
- React Icons
- React Toastify
- Create React App

## Project Structure

```bash
src/
├── App.js
├── Context/
├── Hooks/
├── Pages/
│   ├── About/
│   ├── Blog/
│   ├── Contact/
│   ├── Home/
│   ├── Portfilo/
│   └── Resume/
├── Share/
├── assets/
├── index.css
├── index.js
└── ...
```

## Getting Started

### Prerequisites

- Node.js 16 or newer
- npm or yarn

### Installation

```bash
npm install
```

### Run the app locally

```bash
npm start
```

The application will run in development mode at:

```text
http://localhost:3000
```

### Production build

```bash
npm run build
```

This creates an optimized production build for deployment.

## Available Scripts

```bash
npm start
npm run build
npm test
npm run eject
```

## Customization

You can tailor the portfolio by editing the content in the page components under `src/Pages` and updating the shared styles in `src/index.css` and `src/assets`.

Common areas to update:

- Personal information and bio
- Resume and experience details
- Project portfolio content
- Blog data and entries
- Contact details and social links
- Theme colors and typography

## Deployment

This app can be deployed to any static hosting platform or frontend hosting service such as:

- Vercel
- Netlify
- GitHub Pages
- Firebase Hosting

After building the project, publish the generated `build` folder to your hosting provider.

## License

This project is provided as a template for portfolio use. Please review the package and project documentation for any licensing details associated with the original theme or assets before production deployment.

## Support

For questions or modifications, update the relevant page components and style files in the `src` directory to match your branding and content requirements.

