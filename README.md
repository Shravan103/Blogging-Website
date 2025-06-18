# 📝 Blogging Website

A dynamic and responsive blogging platform built using **PHP** and **MySQL**. This project supports full blogging functionality including user authentication, article management, topic categorization, and an admin panel for content moderation.

---

## 🚀 Features

- ✅ User Registration & Login  
- 📝 Create, Edit, and Delete Posts  
- 📂 Categorize Posts by Topics  
- 🔍 Search Functionality for Blogs  
- 🧑 Admin Dashboard (Manage Posts, Users, Topics)  
- 💬 Comment-ready Structure (future expansion)  
- 📅 Posts display with author and date   

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS (Custom + Font Awesome), JavaScript, jQuery  
- **Backend**: PHP 
- **Database**: MySQL  
- **Extras**: Google Fonts, Slick Carousel  

---

## ⚙️ How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shravan103/Blogging-Website.git
   cd Blogging-Website
   ```

2. **Import the database**:
   - Open **phpMyAdmin** or your preferred MySQL tool.
   - Import the file named `blogg (1).sql`.

3. **Configure Paths**:
   - Open `path.php` and set:
     ```php
     define("ROOT_PATH", realpath(dirname(__FILE__)));
     define("BASE_URL", "http://localhost/your-folder-name");
     ```

4. **Run the Application**:
   - Use a local server like **XAMPP**, **WAMP**, or **MAMP**.
   - Visit:  
     ```
     http://localhost/your-folder-name/index.php
     ```

---

## 👤 Admin Panel

Admins have full access to:
- Manage posts (add/edit/delete)
- Create and manage topics
- Manage users

---

## 📌 Notes

- Home page displays trending and recent posts.
- Blog search and category filtering are fully dynamic.
- Designed for extendability (add comment system, likes, etc.).

---
