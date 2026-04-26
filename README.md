# Elite Digital – Frontend Website

A modern, responsive digital marketing agency website built using **HTML**, **CSS**, and **vanilla JavaScript**. This project showcases a sleek UI, smooth user interactions, and a conversion-focused layout suitable for agency portfolios or business landing pages.

---

## 🌐 Live Demo

👉 [https://elitedigital.netlify.app](https://elitedigital.netlify.app)

---

## 📌 Features

- ✅ Fully responsive design (mobile-friendly)
- ✅ Smooth scrolling navigation
- ✅ Modern UI with gradient styling and animations
- ✅ Hero section with key statistics
- ✅ Services showcase (SEO, PPC, Social Media, etc.)
- ✅ About & Why Choose Us sections
- ✅ Contact form with WhatsApp integration
- ✅ Interactive navbar (changes on scroll)
- ✅ Clean and structured layout

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Structure of the website |
| **CSS3** | Styling, layout, and responsiveness |
| **JavaScript (Vanilla)** | Interactivity and behavior |

---

## 📂 Project Structure

```
EliteDigital-Frontend/
│── index.html      # Main HTML file
│── style.css       # Styling and layout
│── README.md       # Project documentation
```

---

## ⚙️ How It Works

### Navigation
Smooth scrolling is implemented using JavaScript for better UX.

### Contact Form
Form submission redirects users to WhatsApp with pre-filled message details.

> ⚠️ **Bug Fix Note:** There is a small issue in the JavaScript:
>
> ```js
> // ❌ Incorrect — 'subject' is not defined
> const whatsappMessage = `... ${encodeURIComponent(subject)} ...`
> ```
>
> Replace with:
>
> ```js
> // ✅ Correct
> encodeURIComponent(service)
> ```

---

## 📱 Responsive Design

Uses **CSS Grid** & **Flexbox**, optimized for:

- 🖥️ Desktop
- 📱 Tablet
- 📲 Mobile devices

---

## 🚀 Deployment

This project is deployed using **Netlify** for fast and easy hosting.

**To deploy yourself:**

1. Upload project to GitHub
2. Connect repository to Netlify
3. Deploy site in one click

---

## 📸 Sections Overview

| Section | Description |
|---|---|
| **Home** | Hero section with CTA |
| **Why Us** | Key strengths & value proposition |
| **About** | Company introduction |
| **Services** | Offered digital marketing services |
| **Contact** | Form + business details |
| **Footer** | Copyright |

---

## 🔧 Customization

You can easily customize the following:

- **Colors** → `style.css`
- **Content** → `index.html`
- **WhatsApp number** → JavaScript section:

```js
const whatsappNumber = '923201480611';
```

---

## 📧 Contact Info *(Demo)*

- **Email:** [hello@elitedigital.com](mailto:hello@elitedigital.com)
- **Phone:** +1 (555) 123-4567

---

## 📄 License

This project is **open-source** and free to use for learning and personal projects.

---

## 💡 Future Improvements

- [ ] Backend integration (Node.js / Firebase)
- [ ] Form validation & email sending
- [ ] CMS integration
- [ ] Animations using libraries (GSAP / AOS)
- [ ] SEO optimization

---

⭐ *If you like this project, consider giving it a star!*
