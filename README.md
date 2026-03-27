# Facebook Clone (Primitive)

A basic, full-stack web application designed to replicate the core, primitive functionalities of a social media platform like Facebook. The project is organized into a distinct Frontend and Backend architecture.

## 📁 Project Structure

This is a full-stack repository containing both the client and server code:
- `/Backend`: Handles the API, database connection, and server logic.
- `/Frontend`: The user interface built with modern web tooling.

---

## 🛠️ Tech Stack

### Backend
* **Runtime:** Node.js
* **Framework:** Express.js (App routing and middleware)
* **Database:** MongoDB (Database connection handled via `src/db/db.js`)
* **Environment:** `dotenv` (For managing secret keys and database URIs)

### Frontend
* **Build Tool:** Vite (`vite.config.js`)
* **Framework:** React.js (Inferred from Vite + standard structure)
* **Code Quality:** ESLint (`eslint.config.js`)
* **Package Manager:** npm (indicated by `package-lock.json`)

---

## ⚙️ Core Functions & Features

As a "primitive" clone, this application aims to support the following fundamental social media functions:

* **User Authentication:** 
  * Sign up, Log in, and Log out functionality.
  * Secure password hashing and session management (JWT).
* **News Feed / Timeline:** 
  * Fetch and display a chronological list of posts from the database.
* **Post Creation:** 
  * Users can create and publish basic text (and potentially image) posts.
* **Social Interactions:**
  * **Likes:** Ability to like/unlike posts.
  * **Comments:** Ability to reply to posts.
* **Basic User Profile:** 
  * Viewing a user's details and their specific posts.

---
