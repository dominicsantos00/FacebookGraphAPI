# Facebook Graph API Project

## 📌 Project Overview

This project is a **Facebook Graph API integration** that demonstrates how to interact with Facebook Pages using access tokens. It allows developers to fetch page data, posts, comments, and manage page-related operations through Facebook’s official API.

This project is intended for **learning, testing, and academic use**, especially for understanding token-based APIs and social media integrations.

---

## 🎯 Objectives

* Learn how Facebook Graph API works
* Understand access tokens and permissions
* Fetch and manage Facebook Page data
* Practice API requests using JavaScript and Postman

---

## 🛠 Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend (optional):** Node.js / PHP (Laravel)
* **API:** Facebook Graph API
* **Tools:** Postman, Graph API Explorer

---

## ✨ Features

* 🔐 Access Facebook Graph API using tokens
* 📄 Fetch Facebook Page information
* 📝 Retrieve Page posts
* 💬 Read comments on posts
* 📊 Access Page engagement data
* 🧪 Test endpoints using Postman

---

## 🔐 Permissions Used

The following Facebook permissions are required:

* `public_profile`
* `pages_read_engagement`
* `pages_manage_metadata`
* `pages_read_user_content`
* `pages_manage_posts`

⚠️ Some permissions require **Meta App Review**.

---

## 🚀 Getting Started

### 1️⃣ Prerequisites

* Facebook Developer Account
* Facebook App created in Meta Developer Dashboard
* Facebook Page
* Page Access Token

---

### 2️⃣ Generate Access Token

1. Go to **Meta Developer Dashboard**
2. Open **Graph API Explorer**
3. Select your App
4. Add required permissions
5. Generate **Page Access Token**

---

### 3️⃣ Example API Request

```
GET https://graph.facebook.com/v19.0/{page-id}/posts?access_token=PAGE_ACCESS_TOKEN
```

---

## 🧪 Testing with Postman

1. Open Postman
2. Create a new GET request
3. Paste the Graph API endpoint
4. Add `access_token` as a query parameter
5. Send request and inspect response

---

## ❗ Common Errors

| Error Code | Description              |
| ---------- | ------------------------ |
| 190        | Invalid or expired token |
| 200        | Permission denied        |
| 2500       | Invalid endpoint         |
| 100        | Invalid parameter        |

---

## 🛡 Security Notes

* ❌ Never commit access tokens to GitHub
* ✅ Use environment variables (`.env`)
* 🔄 Handle token expiration properly
* 🔐 Limit permissions to required scope

---

## 📦 API Versioning

This project uses:

```
Facebook Graph API v19.0
```

Always check Meta changelogs for updates and deprecations.

---

## 📁 Project Structure (Example)

```
project-root/
│── index.html
│── script.js
│── style.css
│── .env
│── README.md
```

---

## 📚 Resources

* Meta for Developers Documentation
* Facebook Graph API Explorer
* Meta App Dashboard

---

## 📝 License

This project is for **educational purposes only**. Facebook and Meta are trademarks of Meta Platforms, Inc.

---

## 👨‍💻 Author

Luchavez Psalmer, Dominic lewis Santos, Richmond Gupo, Jerwin Ravancho

IT Student

