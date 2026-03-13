# 📚 Library Management System

## 🔹 Project Overview

This project is a **Library Management System (Frontend Only)** developed according to the provided requirement document from Acxiom Consulting.

The system simulates:

- Admin and User Login
- Maintenance Module (Admin Only)
- Transactions Module
- Reports Module
- Membership Management
- Book Management
- Fine Calculation System
- Role-Based Access Control

---

## 🔐 Authentication System

### 🔑 Admin Login
Username: adm
Password: adm
Admin Key: LIBADMIN2024


Admin must enter the secret Admin Key after login for full access.

---

### 👤 User Login
Users must first register via:
register.html


Registered users are stored in browser `localStorage`.

---

## 👥 Role-Based Access

| Feature        | Admin | User |
|---------------|--------|--------|
| Maintenance   | ✅     | ❌     |
| Transactions  | ✅     | ✅     |
| Reports       | ✅     | ✅     |

---

## 📘 Implemented Modules

### 1️⃣ Login Module
- Password hidden
- Admin verification with secret key
- Secure logout message page

---

### 2️⃣ Maintenance Module (Mandatory)
- Add Membership
- Update Membership
- Add Book / Movie
- Update Book / Movie
- User Management

✔ Radio buttons allow only one selection  
✔ Checkboxes follow checked = Yes / unchecked = No  
✔ All mandatory fields validated  

---

### 3️⃣ Transactions Module

#### 📗 Book Availability
- At least one field required
- Radio button selection for available books

#### 📘 Issue Book
- Book name required
- Author auto-populated (non-editable)
- Issue date cannot be less than today
- Return date auto-populated (+15 days)
- Return date editable earlier but not beyond 15 days
- Remarks optional

#### 📙 Return Book
- Book name required
- Serial number mandatory
- Author auto-populated
- Issue date non-editable
- Redirects to Pay Fine page

#### 💰 Pay Fine
- Fine calculated automatically (₹5 per day)
- If fine > 0 → Fine Paid checkbox required
- If fine = 0 → Confirm directly

---

### 4️⃣ Reports Module

Includes pages for:

- Master List of Books
- Master List of Movies
- Master List of Memberships
- Active Issues
- Overdue Returns
- Pending Issue Requests

---

## 🎨 UI Features

- Modern gradient theme
- Glassmorphism sidebar
- Responsive layout
- Bootstrap 5.3.3
- Role-based navigation control
- Logout confirmation page

---

## 🧠 Validation Rules Implemented

✔ Required field validation  
✔ Password confirmation check  
✔ Duplicate username prevention  
✔ Radio single selection  
✔ Checkbox logic  
✔ 15-day return rule  
✔ Fine calculation logic  
✔ Admin key verification  
✔ Logout confirmation  

---

## 🛠 Technologies Used

- HTML5  
- CSS3  
- Bootstrap 5.3.3  
- JavaScript  
- LocalStorage (Frontend database simulation)

---

## ▶️ How to Run

1. Download the repository
2. Open `index.html`
3. Login as Admin or Register as User

No server required.

---

## 🚀 Deployment

This project can be deployed using:

- GitHub Pages
- Netlify
- Vercel

---

## ⚠ Assumptions Made

1. Fine calculated as ₹5 per day.
2. Backend not implemented (frontend simulation only).
3. Data stored in browser localStorage.
4. Book inventory is simulated (not persistent across devices).

---

## ❌ Remaining Tasks (For Full Production Version)

The following items can be implemented in future upgrades:

- Real database integration (MySQL / MongoDB / PostgreSQL)
- Backend authentication system
- Dynamic report generation
- Real book inventory management
- Membership expiry automation
- Book status auto update in reports
- Data persistence across devices
- Inline form validation messages (instead of alert)
- Admin dashboard analytics (charts)
- Secure password encryption

---

## 🏁 Final Status

✔ Admin & User login working  
✔ Maintenance module implemented  
✔ Transactions module implemented  
✔ Fine calculation implemented  
✔ 15-day rule implemented  
✔ Role-based access working  
✔ Professional UI complete  
✔ Ready for academic submission  

---

## 👨‍💻 Author

Developed as part of assessment process from Acxiom Consulting.

Built By Farhan Abid
