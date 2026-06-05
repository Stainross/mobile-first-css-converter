# MobileFirstCSS

<p align="center">
  <img src="https://img.shields.io/badge/MobileFirstCSS-CSS%20Converter-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/built%20with-Angular-red?style=for-the-badge" />
</p>

<h1 align="center">MobileFirstCSS</h1>

<p align="center">
Convert <b>desktop-first CSS</b> into <b>mobile-first CSS</b> instantly.
</p>

<p align="center">
<a href="https://mobilefirstcss.com"><b>🚀 Try it live</b></a>
</p>

---

## 🚨 The problem

Most frontend projects start with desktop-first CSS and gradually accumulate messy `max-width` media queries.

Migrating to mobile-first architecture is:
- repetitive
- error-prone
- time-consuming

---

## ⚡ The solution

MobileFirstCSS automatically converts desktop-first CSS into clean mobile-first CSS in one click.

---

## 🧪 Example

### Input

```css
.card {
  padding: 32px;
  font-size: 18px;
}

@media (max-width: 768px) {
  .card {
    padding: 16px;
    font-size: 14px;
  }
}
```

### Output

```css
.card {
  padding: 16px;
  font-size: 14px;
}

@media (min-width: 769px) {
  .card {
    padding: 32px;
    font-size: 18px;
  }
}
```

---

## ✨ Features

- 🔁 Converts `max-width` → `min-width`
- 📱 Produces mobile-first CSS structure
- ⚡ Fast client-side processing
- 🧩 Preserves CSS structure
- 🚫 No backend required

---

## 🌍 Try it now

👉 https://mobilefirstcss.com

---

## 🧠 Why it matters

Mobile-first CSS improves:
- performance
- maintainability
- responsive consistency

---

## 🛠 Built with

- Angular SSR
- PostCSS
- TypeScript

---

## 👤 Author

Built by **Evoctal**  
https://sofyannsafsaf.fr

---

## ⭐ Support

If you like this project, please star the repo ⭐
