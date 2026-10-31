# Laura's Sweet Delight - Web Development (WEDES020POE Part 2)

**Student Name:** Ntobeko Mabona  
**Student Number:** ST10510446  
**Module:** Web Development 5020 (WEDE5020POE)  
**Group:** Group 4 (Four)  
**Submission Date:** August 2026  
**Live Domain / Project:** [Laurassweetdelight.co.za](http://Laurassweetdelight.co.za)  

---

## 1. Project Overview & Feedback Corrections

### Overview
Laura's Sweet Delight is an e-commerce website designed for a South African candy business founded in 2021. The platform transitions the business from manual WhatsApp orders to an interactive web presence where customers can browse in-stock products, select sizes (Small, Medium, Large) with real-time price updates (R45 - R100), view their shopping cart, and request bulk orders for special events (weddings, parties, corporate functions).

### Changelog (Edits & Corrections from Part 1 Feedback)
Based on lecturer feedback from Part 1, the following improvements and corrections were made to the repository:

* **Structure & Multi-page Separation:** Refactored the website into 5 dedicated, clear HTML pages (`index.html`, `services.html`, `gallery.html`, `about.html`, `contact.html`) to improve user navigation.
* **Separation of Concerns:** Removed all inline/internal CSS `<style>` blocks from HTML pages and created a centralized external stylesheet (`styles.css`).
* **Enhanced E-Commerce Logic:** Standardized pricing ranges based on potion sizes (Small: R45, Medium: R70, Large: R100) and added a dedicated bulk ordering request form for events.
* **Accessibility Fixes:** Added explicit `alt` tags to all product images, labeled all form inputs correctly, and added focus indicator states for keyboard navigation.
### Part 3 Changelog
- Added `enquiry.html` for service quotes, sponsorship, and dynamic pricing calculations.
- Added interactive Leaflet.js store location map and FAQ accordions
- Integrated full lightbox modal viewing on `gallery.html`.
- Implemented Regex validation for phone numbers and email fields on enquiry and contact forms.
- Created SEO optimization assets (`robots.txt`, `sitemap.xml`, canonical URLs, and meta tags).
- Deployed live solution to Netlify/GitHub Pages.
---

## 2. CSS Visual & Responsive Design Implementation (Part 2)

### Technical Architecture
* **External Stylesheet:** All pages are linked to `styles.css` using `<link rel="stylesheet" href="styles.css">`.
* **CSS Reset & Custom Properties (Variables):** Implemented a complete CSS reset alongside root variables for standardized color schemes, font scales, box shadows, and relative spacing.
* **Typography Scale:** Harmonized headings using `Comic Neue` (playful brand display) and body text using `Poppins` (readable typography).
* **Layout Structure:** Built multi-column grid containers (`.grid-3`, `.gallery-grid`, `.layout-grid`) using **CSS Grid** and flex alignment using **Flexbox**.
* **Interactive States:** Styled interactive elements with `:hover`, `:focus`, and `:active` pseudo-classes on buttons, navigation links, and inputs.
* **Relative Units:** Used `rem`, `em`, and percentages (`%`) for font sizes, padding, margins, and layout widths to ensure fluid scalability.

---

## 3. Responsive Design Evidence & Developer Tools Testing

The website was thoroughly tested across multiple screen resolutions using Browser Developer Tools. The layout dynamically adapts across key breakpoints:

### 3.1. Desktop View (Width: ≥ 1200px)
* Features full-width horizontal sticky navigation.
* Multi-column product grid (`grid-template-columns: repeat(auto-fit, minmax(280px, 1fr))`).
* Side-by-side shopping cart layout with order summaries.
![alt text](images/Desk-view.png)

---

### 3.2. Tablet View (Width: 768px)
* Multi-column layouts scale down to fit mid-sized screens smoothly without horizontal scrollbars.
* Grids automatically transition to a 2-column or stacked layout.
![alt text](images/Tablet-view.png)

---

### 3.3. Mobile View (Width: 375px - 430px)
* Multi-column CSS grids collapse into a clean, single-column vertical feed.
* Navigation links and buttons resize to $100\%$ width for touch-friendly mobile navigation.
![alt text](images/Mobile-view.png)

---

## 4. Git & GitHub Repository Workflow

This project follows a regular, descriptive commit strategy. Below is the command sequence used to push changes to the remote repository:

```bash
# 1. Check status of modified files
git status

# 2. Stage all updated HTML, CSS, README, and image files
git add .

# 3. Commit changes with a descriptive message
git commit -m "Refactor layout with external CSS, implement responsive media queries and add screenshot evidence"

# 4. Push updates to the remote GitHub repository
git push origin main

## 5. References and Resources 
Google Fonts: Poppins & Comic Neue font families (fonts.google.com)

MDN Web Docs: CSS Grid Layout & Flexible Box Module guides (developer.mozilla.org)

1. **Google Fonts** (2026) *Poppins and Comic Neue Font Families*. Available at: https://fonts.google.com (Accessed: October 2026).
2. **Leaflet.js** (2026) *An Open-Source JavaScript Library for Mobile-Friendly Interactive Maps*. Available at: https://unpkg.com/leaflet@1.9.4/dist/leaflet.js (Accessed: October 2026).
3. **MDN Web Docs** (2026) *CSS Grid Layout Module*. Mozilla Developer Network. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout (Accessed: October 2026).
4. **MDN Web Docs** (2026) *Client-Side Form Validation*. Mozilla Developer Network. Available at: https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_forms_through_JavaScript (Accessed: October 2026).
5. **OpenStreetMap** (2026) *Map Data & Tile Layer Services*. Available at: https://www.openstreetmap.org (Accessed: October 2026).
6. **Sitemaps.org** (2026) *Sitemap XML Protocol Standard*. Available at: https://www.sitemaps.org/protocol.html (Accessed: October 2026).
7. **Unsplash** (2026) *High-Resolution Royalty-Free Confectionery Photography*. Available at: https://unsplash.com (Accessed: October 2026).
8. **W3C** (2026) *HTML5 & CSS3 Web Standards and Accessibility Guidelines*. World Wide Web Consortium. Available at: https://www.w3.org/TR/html52/ (Accessed: October 2026).
