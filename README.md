# 🧹 CleanPro Supplies — Chemical & Cleaning Product Catalog

A professional e-commerce style product catalog website for cleaning and hygiene supplies. Built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies.

🌐 **Live Site:** [https://aiworkflow287-dotcom.github.io/chemical-product/](https://aiworkflow287-dotcom.github.io/chemical-product/)

---

## 📦 What's Inside

| File | Description |
|------|-------------|
| `index.html` | The entire website — single file, ready to deploy |

---

## 🗂️ Product Categories

| # | Category | Products |
|---|----------|----------|
| 01 | 🧹 Floor Cleaning Mop | 10 |
| 02 | 🪣 Brushes & Wiper / Squeeze | 13 |
| 03 | 🚿 Bathroom Commodities | 25 |
| 04 | 🧤 Essential Commodities | 12 |
| 05 | ⭐ Special Request | 18 |
| 06 | 🧪 Taski Chemical | 6 |
| | **Total** | **74** |

---

## ✨ Features

- 🔍 **Live Search** — search any product by name instantly
- 🗂️ **Category Filter** — sidebar to browse by category
- 📱 **Fully Responsive** — works on mobile, tablet, and desktop
- ⚡ **No frameworks** — pure HTML/CSS/JS, loads instantly
- 🚫 **No prices shown** — catalog only
- 🌙 **Professional design** — clean e-commerce style layout

---

## 🚀 How to Deploy on GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select `Deploy from a branch`
4. Choose `main` branch → `/ (root)` folder
5. Click **Save**
6. Your site will be live at `https://<username>.github.io/<repo-name>/`

---

## 🛠️ How to Update Products

Open `index.html` and find the `catalog` object in the `<script>` section:

```js
const catalog = {
  mop: {
    icon: '🧹',
    label: 'Floor Mop',
    items: [
      "Wet Mop Round Set",
      "Wet Mop Round",
      // add more products here
    ]
  },
  // other categories...
};
```

Just add or remove product names from the `items` array for any category.

---

## 📬 Contact

For bulk orders and enquiries, contact us directly.

---

> Built with ❤️ using plain HTML — no build tools required.
