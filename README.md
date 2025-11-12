# 📝 Mdaedalus Blog Platform

**Mdaedalus Blog Platform** is a full-featured blog application built with **Node.js**, **Express**, **EJS**, and **MongoDB**.  
It supports user authentication, post management, tagging, and rich media content.

---

## 🚀 Features

- User authentication with **Passport.js** and **express-session**
- Create, edit, delete, and view blog posts
- Rich media support: images and YouTube links
- Tag-based content filtering
- Pagination for home page posts
- Archive view for historical posts
- Search functionality
- Secure password hashing with **passport-local-mongoose**
- Date-based timestamps for posts
- Responsive design ready for frontend integration

---

## 📂 Project Structure


├── public/ # Static assets (CSS, images, JS)
├── views/ # EJS templates
│ ├── home.ejs
│ ├── about.ejs
│ ├── contact.ejs
│ ├── compose.ejs
│ ├── post.ejs
│ ├── archive.ejs
│ ├── admin.ejs
│ └── auth.ejs
├── .env # Environment variables (MongoDB URI, secrets)
├── app.js # Main application
├── package.json # Node.js dependencies
└── README.md

---

## ⚙️ Requirements

- Node.js >= 14.x
- MongoDB (Atlas or local)
- NPM packages:
  - `express`
  - `body-parser`
  - `ejs`
  - `lodash`
  - `mongoose`
  - `striptags`
  - `dotenv`
  - `express-session`
  - `passport`
  - `passport-local`
  - `passport-local-mongoose`

Install dependencies:

```bash
npm install
```


# Environment Variables

PORT=3000
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
