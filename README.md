# Express-HW: Tips and Feedback App

## 📋 Description
This is a Node.js + Express app that allows users to:
- Submit UI/UX tips.
- Leave feedback.
- Log failed form submissions for diagnostics.
- Handle non-existent routes with a custom 404 page.

It uses routes, middleware, the fs module, and dynamic HTML rendering to complete a simple but functional web tool.

---

## 🚀 How to Use

1. Install dependencies:

2. Start the server:

3. Visit the app:

---

## 🧪 Routes

### Tips
- `GET /api/tips` - returns all tips
- `POST /api/tips` - add a new tip

### Feedback
- `GET /api/feedback` - returns all feedback
- `POST /api/feedback` - submit new feedback

### Diagnostics
- `GET /api/diagnostics` - returns error logs
- `POST /api/diagnostics` - logs failed form validation

### Wildcard
- `GET *` - serves a custom `404.html`

---

## ✅ Tests
- Use [Insomnia](https://insomnia.rest/) or Postman to test the API endpoints.
- Submit invalid forms on the site to test diagnostics logging.

---

## 📸 Screenshots

| Home Page | Feedback Page | 404 Page |
|-----------|----------------|-----------|
| ![Home](./assets/screenshots/home.png) | ![Feedback](./assets/screenshots/feedback.png) | ![404](./assets/screenshots/404.png) |

---

## 🎥 Walkthrough Video
[Watch Demo Video](https://your-video-link-here.com)

---

## 📁 File Structure

📁 Develop/ ├── server.js ├── routes/ │ ├── index.js │ ├── tips.js │ ├── feedback.js │ └── diagnostics.js ├── public/ │ ├── index.html │ ├── pages/ │ │ ├── feedback.html │ │ └── 404.html │ └── styles/ │ └── index.css ├── db/ │ ├── tips.json │ ├── feedback.json │ └── diagnostics.json └── helpers/ ├── clog.js └── fsUtils.js

---

## 📦 Dependencies
- express
- uuid

---

## 🧠 Author
Tyler Harry

