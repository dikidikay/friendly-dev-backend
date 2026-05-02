# The Friendly Dev — Backend 🗄️

Headless CMS backend for [The Friendly Dev](https://github.com/dikidikay/friendly-dev) portfolio website. Built with **Strapi v5**, connected to a **Neon Postgres** database, with **Cloudinary** for image storage — deployed on **Railway**.

## 🔗 Related Repository

- **Frontend:** [friendly-dev](https://github.com/dikidikay/friendly-dev) — React Router v7, SSR, Vercel

---

## 🧰 Tech Stack

| Tool                                 | Role                         |
| ------------------------------------ | ---------------------------- |
| [Strapi v5](https://strapi.io)       | Headless CMS & REST API      |
| [Neon](https://neon.com)             | Serverless Postgres database |
| [Cloudinary](https://cloudinary.com) | Image upload & storage       |
| [Railway](https://railway.app)       | Deployment & hosting         |

---

## ✨ What's Configured

- **Strapi** scaffolded with content types for **Projects** and **Blog Posts**
- **Neon Postgres** connected as the production database
- **Cloudinary** integrated via `@strapi/provider-upload-cloudinary` for media uploads in the admin panel
- **Public API** enabled for read access, powering the frontend's server-side loaders
- **Live Strapi Admin:** [friendly-dev-backend-production-65b6.up.railway.app](https://friendly-dev-backend-production-65b6.up.railway.app)

---

## 📚 Course Reference

This project was built while following:

**[Modern React From The Beginning](https://www.udemy.com/course/modern-react-from-the-beginning)** on Udemy.
