## FACEBOOK DATA EXPLORER 📊


## 📌 DESCRIPTION
Facebook Data Explorer is a simple web-based application that allows users to fetch and display Facebook profile or page data using the Meta Graph API. By entering an Object ID or the keyword me, the app retrieves and presents profile information in a clean, user-friendly interface.

This project demonstrates:
- API integration using JavaScript (Fetch API)
- Dynamic DOM manipulation
- Error handling and loading states
- Clean UI with HTML & CSS


## 🚀 FEATURES
- 🔍 Fetch Facebook profile or page data using Object IDs
- 👤 Display profile details:
    - Name
    - User ID
    - Email (if public)
    - Birthday (requires permission)
    - Profile link
    - Profile picture
- 📝 Show recent public posts (up to 2)
- ⏳ Loading spinner while fetching data
- ⚠️ Error handling for invalid IDs or API issues
- ⌨️ Supports both button click and Enter key

## 🛠️ TECHNOLOGIES USED
- HTML5 – Structure
- CSS3 – Styling and layout
- JavaScript (ES Modules) – Logic and API handling
- Meta (Facebook) Graph API – Data source

## 📂 PROJECT STRUCTURE
project-folder/
│
├── index.html      # Main HTML file
├── style.css       # Styling
├── script.js       # Main JavaScript logic
├── config.js       # API configuration (not included in repo)
└── README.md       # Project documentation

## 🔑REQUIRED PERMISSIONS
- Some fields require additional Facebook permissions:
    - email → Requires public email access
    - birthday → Requires user_birthday permission
    - posts → Only public posts are accessible
- If permissions are not granted, the app will gracefully display fallback messages.

## ❗LIMITATIONS
- Requires a valid and active access token
- Private profiles cannot be fully accessed
- Some data may not appear due to Facebook privacy policies

## 🧩👩‍💻 Role Assignment

To keep the project organized and running smoothly, each member was given a specific role with clear responsibilities:

**Jessalyn S. Peralta** – GitHub & Documentation Manager
Manages the GitHub repository, handles commits, and keeps the README and project documentation updated.

**Janiza Dela Cruz** – API & Authentication Handler
Handles API integration, data fetching, and manages API keys and authentication.

**Ernie Roble** – JavaScript Logic / Data Processing
Works on the main JavaScript functions, data handling, validation, and overall app logic.

**Vanessa Jimenez** – UI & CSS Designer
Designs the user interface, styles the app using CSS, and ensures a clean and user-friendly layout.
