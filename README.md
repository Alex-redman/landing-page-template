
---

# Bang & Olufsen Landing Page

A responsive landing page inspired by Bang & Olufsen’s product aesthetics.
The project includes multiple sections, such as Recommended Products, Categories, About Us, and a Contact Form.
The primary goal is to practice layout building, SCSS architecture, responsive design, UI components, and clean project structuring.

---

## Live Preview

- [DEMO LINK](https://Alex-redman.github.io/landing-page-template/)
Make sure the link works in incognito mode.

---

## Design Reference

[Figma link here](https://www.figma.com/design/DtkQmQ797hk0nI4KfMi2Uq/BOSE-New-Version?node-id=6817-212)

---

## Technologies Used

* HTML5
* SCSS (modular structure with partials)
* JavaScript (ES6+, menu handling, interactions)
* BEM methodology
* Responsive design (Flexbox / Grid)
* File structure based on scalable front-end architecture

---

## Project Structure

```
src/
│
├── images/
│   ├── icons/
│   │   ├── favicon.svg
│   │   ├── icon-burger-menu.png
│   │   ├── icon-cross.svg
│   │   ├── icon-phone.png
│   │   └── ...
│   ├── beoplay-hx.png
│   ├── beosound-a5.png
│   ├── beosound-theatre.png
│   ├── earphones-1.png
│   ├── smart-home-1.png
│   └── ...
│
├── scripts/
│   └── main.js
│
├── styles/
│   ├── blocks/
│   │   ├── about-us.scss
│   │   ├── categories.scss
│   │   ├── category.scss
│   │   ├── contacts.scss
│   │   ├── header.scss
│   │   ├── icon.scss
│   │   ├── main.scss
│   │   ├── menu.scss
│   │   ├── nav.scss
│   │   ├── page.scss
│   │   ├── recommended.scss
│   │   ├── section-title.scss
│   │   └── top-bar.scss
│   │
│   ├── utils/
│   │   ├── mixins.scss
│   │   └── variables.scss
│   │
│   ├── main.scss
│   └── style.scss
│
└── index.html
```

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### Install dependencies

```bash
npm install
```

### Run the project locally

If you have a dev server configured:

```bash
npm start
```

If not — simply open `index.html` in your browser.

---

## Features

* Fully responsive layout
* Burger menu and mobile navigation
* Dynamic tooltips (phone icon in the header)
* Card-based product layout
* SCSS modular structure with partials
* Contact form with front-end validation
* Clean BEM class naming for maintainability

---

## Notes About the Code

* Image paths in HTML should use `/src/images/...` (your project uses SCSS & structured assets, so absolute paths are correct).
* The contact form currently uses `onsubmit="this.reset(); return false;"` meaning it **only resets** instead of sending data.
  If you want to connect Formspree or backend — this must be replaced.
* SCSS partials are well-organized; keep naming consistent.
* Ensure that favicon paths match your deployment environment.

---

## Deployment Tips

* GitHub Pages requires compiled CSS in the root (no SCSS).
* Vercel / Netlify fully support SCSS if your build step compiles it.
* When deploying, verify that absolute paths (`/src/images/...`) resolve correctly — on GitHub Pages they often break.
  If you deploy to GitHub Pages, change them to **relative paths**:
  `./src/images/...`

---

## README Checklist

* [x] Clear project description
* [x] Working live demo link
* [x] Accurate technologies list
* [x] Clean installation instructions
* [x] No Mate Academy–specific instructions
* [x] Repository contains only required files, no unused assets

---

