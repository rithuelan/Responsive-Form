# Employee Information Form Project

This is a simple **employee registration system** built using **HTML, CSS, and JavaScript**.  
It includes a form for employees to submit their details, a thank-you confirmation page, and an admin page to view all submitted registrations.  

All submitted data is stored in the browser’s **localStorage** (no backend required).

---

## 📂 Project Structure

├── index.html # Employee Information Form (main form page)
├── thankyou.html # Thank You page after successful submission
├── submissions.html # Page to view all submitted registrations
├── assets/
│ └── halleyxlogo.png # Favicon/logo (used in all pages)

yaml
Copy code

---

## 🚀 Features

- **Employee Information Form**
  - Collects employee details:  
    - First Name, Last Name  
    - Email  
    - Address  
    - District, State  
    - Pincode (6 digits)  
    - Phone Number (10 digits)  
  - Validates required fields with inline error messages.
  - Validates:
    - Email format
    - Pincode (must be 6 digits)
    - Phone number (must be 10 digits)
  - Stores data into **localStorage**.

- **Thank You Page**
  - Simple confirmation message after form submission.

- **Submissions Page**
  - Displays all submitted employee registrations in a **responsive table**.
  - Shows `"No submissions yet."` if no data exists.
  - Uses sticky headers for easy navigation.

---

## 🛠️ How It Works

1. Open `index.html` in your browser.
2. Fill out the form and click **Submit**.
3. The form validates inputs:
   - Missing or invalid fields will show error messages.
4. On successful submission:
   - Data is stored in `localStorage`.
   - Redirects to `thankyou.html`.
5. Open `submissions.html` to view all saved registrations.

---

## ⚡ Future Improvements

- Add **Edit/Delete** options for each row in submissions.
- Add a **Clear All Submissions** button.
- Export data as **CSV/Excel**.
- Connect to a **backend (Node.js / PHP / Python)** for persistent storage.

---

## 🧑‍💻 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Storage:** Browser LocalStorage
- **Fonts:** Google Fonts (Roboto)

---

## 📌 Usage Notes

- This project is for **learning/demo purposes**.
- Since it uses `localStorage`, submitted data is **browser-specific** and will not be shared across device.
