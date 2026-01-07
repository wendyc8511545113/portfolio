# Wendy Caffey Portfolio Website

Welcome to my personal portfolio website! This repository contains all the files needed to run my minimalist portfolio site with green accents, built from scratch using HTML, CSS, and JavaScript.

---

## 📂 Repository Structure

Here’s a quick overview of the main files and folders:

### **1. `index.html`**
- This is the **main page** of the website — the landing page.
- Contains the structure of your site:
  - Header with your name
  - Profile photo
  - About Me section
  - Portfolio section with project cards
  - Contact Me section
  - Footer
- All content visible on the page is defined here.

### **2. `styles.css`**
- Contains all **visual styling** for the site.
- Controls:
  - Fonts, colors, and backgrounds
  - Layouts and spacing
  - Portfolio card appearance and hover effects
  - Profile photo styling

### **3. `script.js`**
- Contains **interactive functionality**.
- Currently used for:
  - Smooth scrolling to different sections
  - Can be extended for other interactive features (animations, pop-ups, filtering projects, etc.)

### **4. `assets/` folder**
- Stores **images and other media** used in the website.
- Example: profile photo (`profile.jpg`)
- Keep all future images or media files here for easy organization.

---

## 🛠 How to Use / Update the Website

Here’s a quick guide for adding pages, images, or other content:

### **1. Adding a New Page**
1. Create a new HTML file in the root of the repository, e.g., `projects.html`.
2. Copy the basic structure from `index.html` and update content as needed.
3. Update navigation links in `index.html` to include the new page if desired.

### **2. Adding Images**
1. Upload images to the `assets` folder.
2. Reference them in your HTML with the path `assets/filename.ext`.  
   Example:
   ```html
   <img src="assets/my-image.jpg" alt="Description of image">
