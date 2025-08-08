# The Bengal Bite - Restaurant Landing Page

This is a simple, elegant, and fully responsive landing page for a fictional restaurant in Kolkata called "The Bengal Bite." It's built with modern web technologies and designed to be easily customizable.

## ✨ Features

* **Visually Appealing Hero Section:** A full-screen background image with centered text to immediately capture the visitor's attention.
* **Responsive Navigation:** A sticky navigation bar that includes a mobile-friendly hamburger menu.
* **Multi-Section Layout:** Includes sections for Home, About, Menu, and Contact, allowing for smooth scrolling.
* **Interactive Menu:** A clean grid layout for signature dishes, complete with images, descriptions, and prices. The cards have a subtle hover effect.
* **Contact & Booking Form:** A simple and clear form for users to make inquiries or table reservations.
* **Clean & Modern Design:** Uses a professional font pairing (Playfair Display for headings, Inter for body text) and a warm, inviting color palette.

## 🛠️ Technologies Used

* **HTML5:** For the structure and content of the website.
* **Tailwind CSS:** A utility-first CSS framework used for all styling and for creating the responsive layout.
* **JavaScript:** A minimal amount of vanilla JavaScript is used to toggle the mobile navigation menu.

## 🚀 Local Setup

To run this website on your local machine, follow these simple steps:

1.  **Download the files:**
    * `index.html`
    * (Optional) Create a `styles.css` file if you choose to separate the CSS.

2.  **Open `index.html` in your browser:**
    * Navigate to the folder where you saved the file.
    * Double-click on `index.html`, and it will open in your default web browser.

No special servers or build tools are required to view the page.

## 📂 File Structure

The project is contained within a single `index.html` file for simplicity.

```
.
└── index.html
```

For better organization, you can separate the CSS:

1.  Create a file named `styles.css`.
2.  Move all the CSS rules from the `<style>` tags in `index.html` into `styles.css`.
3.  Link the stylesheet in `index.html` by adding `<link rel="stylesheet" href="styles.css">` in the `<head>` section.

The structure would then be:

```
.
├── index.html
└── styles.css
```

## 🎨 Customization

This template is designed to be easily customized.

### Changing Text Content

* **Restaurant Name:** Find "The Bengal Bite" in the `<header>` and `<footer>` and replace it with your own.
* **Menu Items:** Navigate to the "Signature Dishes Section" (`<section id="menu">`). Each dish is in a `<div>` with the class `dish-card`. You can change the `<h3>` for the name, the `<p>` for the description, and the final `<p>` for the price.
* **About & Contact Info:** Simply edit the text within the `<section id="about">` and `<section id="contact">`.

### Changing Images

* **Hero Background Image:** In the `<style>` section (or your `styles.css` file), find the `.hero-bg` class. Replace the URL in `background-image: url('...');` with a link to your desired image.
* **Dish Images:** In the `<section id="menu">`, each dish card has an `<img>` tag. Change the `src="..."` attribute to the URL of your dish's image.
* **About Us Image:** In the `<section id="about">`, find the `<img>` tag and change its `src` attribute.
