# 🪑 Mebleria

Mebleria is a responsive furniture store web app built as a JavaScript team
project.

The project demonstrates working with a REST API, dynamic product rendering,
category filtering, pagination, modal windows, sliders, form validation, and
responsive UI.

**Live site:** https://alisapagan.github.io/mebleria/ **API docs:**
https://furniture-store-v2.b.goit.study/api-docs/ **Figma design:**
https://www.figma.com/design/xmuUuDiEAbT0mjmpgzPrc0/%D0%9C%D0%B5%D0%B1%D0%BB%D0%B5%D1%80%D1%96%D1%8F?node-id=5999-10563

---

## Features

- Furniture catalog loaded from a REST API
- Category filtering
- “Show more” pagination
- Product details modal
- Popular products slider
- Customer feedback slider
- FAQ accordion
- Order form with validation
- Toast notifications for user actions and errors
- Responsive layout for mobile, tablet, and desktop
- Retina-ready images

---

## My Role

**Role:** Scrum Master, Front-End Developer

My contributions included:

- Organized team workflow, communication, and task coordination as Scrum Master
- Worked on responsive header and burger menu behavior
- Implemented popup/modal logic
- Added anchor navigation and section scrolling behavior
- Helped with UI fixes, layout cleanup, and bug fixing
- Worked on image optimization and responsive polish
- Supported final project cleanup and presentation readiness

---

## Tech Stack

- HTML5
- CSS3 / SCSS
- JavaScript ES6+
- REST API
- Async/Await
- Swiper.js
- iziToast
- Accordion.js
- Raty.js
- Vite

---

## Main Functionality

### Header

- Logo and navigation menu
- Burger menu for smaller screens
- Smooth navigation to page sections
- Scroll locking when the mobile menu is open

### Furniture List

- Fetches furniture data from `/furniture`
- Displays initial product cards
- Filters products by category from `/categories`
- Loads more products with pagination
- Opens a product details modal

### Popular Products

- Fetches popular products from `/furniture?type=popular`
- Displays products in a Swiper slider
- Opens product details modal
- Allows moving from product details to the order form

### Feedback

- Fetches customer feedback from `/feedbacks`
- Displays feedback in a Swiper slider
- Shows rating stars with Raty.js

### Order Form

- Collects user name, phone, and comment
- Sends order data with a POST request to `/orders`
- Validates form input
- Shows success/error notifications with iziToast

### FAQ

- Accordion section with common questions and answers

### Footer

- Logo, navigation, and social links
- External links open in a new tab with `rel="noopener noreferrer"`

---

## Run Locally

```bash
git clone https://github.com/AlisaPagan/mebleria.git
cd mebleria
npm install
npm run dev
npm run build
```

---

## Team

Team project built during the GoIT Full-Stack Developer course.

Team Lead: Alina Slipenka Scrum Master: Alisa Pagan Developers: Alina
Yashchenko, Vitalii Ivashchenko, Anastasiia Melnyk, Dasha Kazarina, Tetiana
Shcherbyna, Tetiana Kovpak, Mykhailo Pyroh

---

## License

This is an educational project created during the GoIT Full-Stack Developer
course.
