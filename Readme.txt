# Te Unga Waka Website

This is a static website built with simple HTML and CSS, designed to be hosted using **GitHub Pages**.  
It contains a collection of pages (`index.htm`, `page2.htm` … `page109.htm`) representing the history, people, and stories of Te Unga Waka.

## 📂 Project Structure

.
├── index.htm # Main index page with navigation links
├── page2.htm - page109.htm
├── style.css # Shared stylesheet (if separated)
├── images/ # Image files (if used)
└── README.md # Project documentation

> Note: In this project, images are stored in the root directory (not in a subfolder).

## 🚀 How to View

1. Open [GitHub Pages settings](https://docs.github.com/en/pages/quickstart).
2. Ensure the site is published from the **main branch** with the **root directory**.
3. Visit your site at:

https://<your-username>.github.io/<repository-name>/


## 🛠️ How to Edit

- Each page is a standalone `.htm` file.  
- Update text or images directly in the corresponding file.  
- If you want consistent styling across all pages, use or extend the `style.css`.

## ✅ Features

- Clean, mobile-friendly layout with styled images:
```css
img {
 display: block;
 margin: 20px auto;
 max-width: 90%;
 height: auto;
 border: 2px solid #ccc;
 border-radius: 8px;
 box-shadow: 2px 2px 8px rgba(0,0,0,0.2);
}