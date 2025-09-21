# Netflix-Clone

LIVE LINK :  https://devanshu896.github.io/Netflix-Clone/

Based on the provided `index.html` file, here are the details and technologies used for this Netflix clone project that you can include in your README file. 💻

## Project Overview

This is a **Netflix landing page clone**, built to replicate the look and feel of the original Netflix homepage. The project focuses on a responsive design that adapts to different screen sizes, from mobile to desktop. 
***

## Key Features

* **Responsive Layout:** The design adjusts dynamically for various devices, ensuring a consistent user experience on phones, tablets, and desktops.
* **Hero Section:** A prominent, full-screen hero section with a background image and a call to action.
* **Content Sections:** Multiple sections showcasing features like watching on TV, downloading shows, and streaming on various devices, each with a title, description, and an illustrative image.
* **FAQ Section:** An interactive section for frequently asked questions, designed to mimic an accordion with a simple click-to-expand functionality.
* **Navigation Bar:** A fixed navigation bar that changes its background color upon scrolling down the page, providing a smooth visual effect.
* **Dynamic Icons:** Integration of lightweight vector icons from Feather Icons for a clean, modern look.

***

## Technologies Used

### Frontend
* **HTML5:** The foundational markup language used to structure the page content.
* **CSS:** The project uses a **utility-first CSS framework**, which means most of the styling is applied directly in the HTML using classes.
    * **Tailwind CSS:** This is the primary styling library, imported via a CDN. It provides pre-defined utility classes like `flex`, `bg-black`, `text-white`, `px-4`, and `md:w-1/2`, which were used to build the layout and design. The CSS code in the `<style>` tag extends Tailwind's functionality with custom classes like `.hero-bg` and `.nav-scrolled`.

### Libraries and Scripts
* **AOS (Animate On Scroll):** A JavaScript library for creating animations that trigger when elements are scrolled into view. It's used for the fade-in and fade-up effects on various sections of the page.
* **Feather Icons:** An open-source library of simple, elegant vector icons. The icons are dynamically replaced on the page using JavaScript (`feather.replace()`) to ensure they scale and render cleanly.

### Other
* **CDN (Content Delivery Network):** All external libraries (Tailwind, AOS, Feather Icons) are loaded directly from CDNs, meaning they don't need to be hosted locally.
* **Static Photos:** The project uses placeholder images from `http://static.photos/` to represent content in the different sections.
* **Netflix Logo:** The logo is linked directly from Wikimedia Commons.
