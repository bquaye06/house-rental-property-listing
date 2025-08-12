# 🏠 House Rental & Property Listing CRUD Application

## 📌 Overview
This is our **Web Programming group project**: a **House Rental & Property Listing CRUD Application** built with **HTML, CSS (Bootstrap)**, JavaScript, and PHP/MySQL.  
The app allows users to **Create, Read, Update, and Delete** property listings.

---

## 👥 Team Roles

### **1. Frontend Developer**
- Design pages using **Bootstrap**.
- Work on:
  - `index.html` (Property listing page)
  - `add-property.html` (Add property form)
  - `edit-property.html` (Edit property form)
  - `view-property.html` (Detailed property view)
- Keep all CSS changes in `assets/css/style.css`.
- Write any JavaScript UI logic in `assets/js/app.js`.

### **2. Backend Developer**
- Handle PHP scripts in the `backend/` folder:
  - `add_property.php` → Add property to database.
  - `edit_property.php` → Update property details.
  - `delete_property.php` → Remove property.
  - `fetch_properties.php` → Get property list from DB.
- Ensure all backend files connect through `data/db.php`.

### **3. Database Manager**
- Create the MySQL database and tables.
- Export the `.sql` file into the `data/` folder.
- Keep the DB connection credentials updated in `data/db.php`.
- Work closely with backend dev to ensure queries work correctly.

---

## 📂 Folder Structure
house-rental-property-listing/
│
├── index.html
├── add-property.html
├── edit-property.html
├── view-property.html
│
├── assets/
│ ├── css/
│ ├── js/
│ ├── img/
│ └── fonts/
│
├── includes/
├── data/
├── backend/
└── README.md



---

## 🔄 How to Collaborate (Git Workflow)

### 1️⃣ Fork the Repository
- Go to the project repo link on GitHub.
- Click **Fork** (top-right corner).
- This creates a copy under your GitHub account.

### 2️⃣ Clone Your Fork
Open your terminal (Git Bash, CMD, or VS Code terminal) and run:
```bash
git clone https://github.com/bquaye06/house-rental-property-listing.git
cd house-rental-property-listing


