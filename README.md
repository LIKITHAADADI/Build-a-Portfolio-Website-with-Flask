# 🌐 Build a Portfolio Website with Flask

A full-stack portfolio website built using **Flask (Python)** and styled with **HTML & CSS**. This project showcases your personal background, skills, projects, and includes a functional contact form — all served through a lightweight Flask web application.

---

## 🎯 Objective

To develop a personal portfolio that:

- Highlights professional and academic background
- Displays technical skills and completed projects
- Accepts messages through a contact form
- Demonstrates real-world Flask web development skills

---

## 🧰 Tools & Technologies Used

- **Python 3.x**
- **Flask** – Web framework for Python
- **HTML5 & CSS3** – Frontend structure and styling
- **Git & GitHub** – Version control and code hosting
- **Visual Studio Code** – Code editor

---

---

## 🚀 How to Run This Project Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/LIKITHAADADI/Build-a-Portfolio-Website-with-Flask.git
cd Build-a-Portfolio-Website-with-Flask
```

### 2️⃣ Create and Activate Virtual Environment (Optional but Recommended)

Creating a virtual environment helps manage dependencies for your project without affecting global Python settings.

#### 🔹 For Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Flask

Install Flask using `pip` inside your activated virtual environment:

```bash
pip install flask
```

### 4️⃣ Run the Application

Start the Flask server by running:

```bash
python app.py
```

### 5️⃣ Open in Browser

Go to http://127.0.0.1:5000 to view your portfolio.


You should now see your personal portfolio website running locally.

---

## 📄 Pages & Files Included

### 🐍 `app.py`

- The main Flask application file
- Handles all routing (`/`, `/contact`)
- Processes contact form submissions via POST
- Renders HTML templates using `render_template()`

### 🖼️ `templates/index.html`

- Homepage of the portfolio site
- Sections: Hero, About, Skills, Projects, Education, Footer
- Connected to Flask via `app.py`

### 📩 `templates/contact.html`

- Contact form page
- Full-width, user-friendly form to collect name, email, and message
- Includes alternate contact details and social links

### 🎨 `static/style.css`

- Combined stylesheet for all pages
- Handles layout, colors, spacing, and responsiveness
- Designed to fill the full page and provide a professional look



