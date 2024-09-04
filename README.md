# 🏡 Nexter - Your Home, Your Freedom

**Nexter** is a fictional real estate website designed to showcase luxurious homes and provide users with a seamless home-buying experience. This project demonstrates advanced **CSS Grid** and **SCSS** techniques, resulting in a fully responsive layout with rich features and an elegant design.

## 🌍 Live Demo

Check out the live version of **Nexter** here: <a href="https://yasakura-nexterproject.netlify.app/" target="_blank">Nexter Live Demo</a>

![Nexter](img/logo.png)
![Screenshot 2024-09-04 at 15 27 32](https://github.com/user-attachments/assets/c6a090af-ffff-4b78-bd0a-34f92a8108af)

## 🎯 Project Overview

The **Nexter** project is developed using modern CSS methodologies, focusing on responsive design and scalability. This project leverages **SCSS** for efficient styling and code management. It includes sections for property listings, top realtors, customer testimonials, and more.

## 🌟 Features

### 📱 Responsive Design
- The design is fully responsive, ensuring a seamless user experience across all devices.
- The grid-based layout adapts to various screen sizes using custom **breakpoints** for devices ranging from mobile to large desktops.

### 🏆 Property Highlights
- A gallery of **luxurious properties** showcasing homes with details like location, size, rooms, and price.
- Each property has a **contact realtor button** for quick inquiries.

### 🧑‍💼 Top Realtors
- A **top realtors** section highlights the best-performing real estate agents with their photos and number of houses sold.

### 🖼️ Image Gallery
- A **grid-based image gallery** that displays multiple property images, making it easy to showcase beautiful homes in various layouts.

### 💡 Featured Advantages
- The **features section** outlines the advantages of choosing Nexter, including luxury homes, top locations, and secure payments.

### 🎥 Customer Testimonials
- A dedicated **customer testimonials section** showcases satisfied clients with a gallery of images, adding trust and credibility to the website.

### 🖼️ SVG Icon Integration
- Uses **SVG icons** for various sections, such as home features, realtor contact details, and more, making the site visually appealing and interactive.

## 💻 Tech Stack

- **HTML5**: Semantic markup for structuring the webpage content.
- **SCSS (Sass)**: Used to manage styles efficiently with variables, mixins, and responsive breakpoints.
- **CSS Grid**: The primary layout tool, used to create a flexible, grid-based design.
- **SVG Icons**: Integrated for various visual elements such as icons and logos.

## 🛠️ Key Sections

### Sidebar
- A **sidebar** with a minimalist design and a responsive toggle button for smaller screens.

### Header
- The **header** features the Nexter logo, a call-to-action button, and logos of popular brands where Nexter has been featured.

### Realtors
- Highlights the top 3 realtors, showcasing their photos and performance.

### Features
- Displays key features such as **luxury homes**, **top locations**, and **secure payments** using SVG icons.

### Homes
- A grid-based **property listing** showcasing various homes with features like price, location, number of rooms, and contact buttons for realtors.

### Gallery
- A **dynamic image gallery** that adapts to different screen sizes, presenting beautiful photos of homes.

### Footer
- The **footer** contains essential navigation links and a copyright notice.

## 🎨 SCSS Structure

This project utilizes **SCSS** for styling, making use of **variables**, **mixins**, and **nested styles** to create reusable and maintainable CSS.

### Color Variables

```scss
$color-primary: #c69963;
$color-primary-dark: #b28451;
$color-secondary: #101d2c;
$color-grey-light-1: #f9f7f6;
$color-grey-light-2: #aaa;
$color-grey-dark-1: #54483a;
$color-grey-dark-2: #6d5d4b;
```

### Font Variables

```scss
$font-primary: "Nunito", sans-serif;
$font-display: "Josefin Sans", sans-serif;
```

### Responsive Breakpoints

```scss
$bp-largest: 75em;
$bp-large: 62.5em;
$bp-medium: 50em;
$bp-small: 37.5em;
```

### SCSS Mixins

```scss
@mixin clearfix {
  &::after {
    content: "";
    display: table;
    clear: both;
  }
}

@mixin respond($breakpoint) {
  @if $breakpoint == phone {
    @media only screen and (max-width: 37.5em) { @content; }
  }
  @if $breakpoint == tab-port {
    @media only screen and (max-width: 56.25em) { @content; }
  }
  @if $breakpoint == tab-land {
    @media only screen and (max-width: 75em) { @content; }
  }
  @if $breakpoint == big-desktop {
    @media only screen and (min-width: 112.5em) { @content; }
  }
}
```

## 🚀 Getting Started

### Prerequisites

To run this project locally, you’ll need:

- A modern browser (Chrome, Firefox, Safari) that supports **HTML5**, **CSS Grid**, and **Flexbox**.
- A code editor like **VSCode** to modify or view the code.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/nexter-project.git
   ```
2. **Navigate into the project directory:**
   ```bash
   cd nexter-project
   ```
3. **Install SCSS (optional)**
   - If you want to modify the styles, you'll need **Sass** installed on your machine:
   ```bash
   npm install -g sass
   ```
4. **Compile SCSS to CSS**
   ```bash
   sass --watch scss/main.scss css/style.css
   ```
5. **Open `index.html` in your browser**:
   - You can open the `index.html` file directly in your browser to view the website.

## 📄 License

This project is licensed under the **MIT License**.

## 🤝 Contributing

Contributions are welcome! If you would like to improve the design or functionality, feel free to:

1. Fork the repository.
2. Create a new branch.
3. Submit a pull request for review.

---

Developed by **Yuta Asakura** as part of an advanced CSS and Sass course by **Jonas Schmedtmann**.
