# Employee Directory Web Interface

A responsive and interactive Employee Directory frontend built with **HTML, CSS, JavaScript**, and **Freemarker templates**. This project simulates a full-fledged employee management dashboard with client-side data handling, filtering, sorting, and pagination.

## 🚀 Features

### 📋 Dashboard Page
- Displays a list/grid of employees with:
  - **Employee ID**
  - **First Name**
  - **Last Name**
  - **Email**
  - **Department**
  - **Role**
- Each row/card includes **Edit** and **Delete** buttons.
- Rendered using **Freemarker template** with mock data passed via `<#assign>`.

### 📝 Add/Edit Form Page
- Form includes:
  - First Name
  - Last Name
  - Email (validated)
  - Department
  - Role
- Real-time validation using **JavaScript**.
- Form is styled and validates on client-side before updating in-memory data.

### 🔍 Filter / Sort / Search
- **Filter Sidebar/Popup**:
  - Filter by **First Name**, **Department**, and **Role**.
- **Search bar** at the top to find employees by name or email.
- **Sorting** supported for First Name and Department.

### 🔄 Pagination / Infinite Scroll
- Pagination options: **10, 25, 50, 100** rows per page.
- Implemented using JavaScript.

### 📱 Responsive Design
- Fully responsive across:
  - Desktop 💻
  - Tablet 📱
  - Mobile 📲

## ⚙️ Technology Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **Freemarker (FTL) Templates**

## 🗃️ Project Structure

```bash
employee-directory/
│
├── index.html               # Dashboard Page
├── form.html                # Add/Edit Employee Page
├── templates/
│   └── employee.ftl         # Freemarker Template
├── js/
│   ├── main.js              # Core JS (render, filter, paginate)
│   ├── form-handler.js      # Form submission and validation logic
│   └── data.js              # Mock employee data (array)
├── css/
│   ├── style.css            # Base styles
│   └── responsive.css       # Media queries for responsiveness
└── assets/
    └── icons/, images/      # UI assets
