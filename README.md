# Omnifood: AI-Powered Food Subscription Landing Page

## 💡 About the Project

This repository hosts the **professional, fully responsive landing page** for Omnifood, a conceptual AI-powered food subscription service. This is a **front-end only** project designed to showcase a modern and well-structured website to prospective customers.

The landing page effectively presents the Omnifood service, which uses an AI-centric approach to create and deliver healthy, personalized weekly meal plans to busy users.

## 🔗 Live Site and Deployment

This project has been successfully deployed and is live on Netlify.

- **View the live page:** https://omnifood-mhaske.netlify.app/

## ✨ Features of the Landing Page

The website is a multi-section landing page built to modern web standards and features:

- **Responsive Design**: Optimized for all devices, from large desktops down to the smallest mobile screens.
- **Sticky Navigation**: A mobile-responsive header that becomes sticky when scrolling past the hero section.
- **Smooth Scrolling**: JavaScript implementation for smooth animated jumps between sections (How it works, Meals, Pricing).
- **High-Fidelity Content**: Includes key sections such as:
  - **Hero**: Main value proposition and call-to-action.
  - **How it works**: Explained in 3 simple steps with custom app screenshots.
  - **Meals**: Sample meals (Japanese Gyozas and Avocado Salad) with nutritional facts and a list of 9 supported diets.
  - **Testimonials & Gallery**: Customer reviews and a visually appealing gallery of food images.
  - **Pricing**: Details for the Starter ($399/mo) and Complete ($649/mo) plans.
  - **Call to Action (CTA)**: A dedicated form section to capture user sign-ups for a free first meal.

## 🛠️ Technologies Used

- **HTML5**: Used for semantic structure and overall page markup.
- **CSS3 (Advanced)**: Utilizing custom properties, Flexbox, and CSS Grid for complex, responsive layout management.
- **Vanilla JavaScript**: Implemented for all interactivity, including fixing Flexbox gap in older browsers and managing mobile navigation functionality.
- **Netlify Forms**: Integrated into the CTA section to handle form submissions without a custom backend.

## 📐 Design & Styling

- **Brand Color (Primary)**: `#e67e22` (an orange tone).
- **Typography**: Uses the Google Font **Rubik**.
- **Mobile Navigation**: Uses a modern off-canvas menu system triggered by a mobile button.

## 🚀 Deployment Steps (Netlify)

The project was deployed using Netlify's continuous deployment process:

1.  Connected the GitHub repository to a new Netlify site.
2.  Set the Build command to `npm run build` (or left blank for pure HTML/CSS/JS).
3.  Set the Publish directory to the root folder (`/Omnifood`).
4.  Netlify automatically handles the build and deployment on every push to the main branch.
