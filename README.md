# 🔐 Password Generator Web App

A modern and secure **Password Generator Web Application** built using **Flask (Python)**, with a stylish UI and advanced features like password strength detection and crack time estimation.

---

## 🚀 Features

* 🔢 Generate passwords of custom length
* 🔠 Include uppercase letters (A-Z)
* 🔢 Include numbers (0-9)
* 🔣 Include symbols (!@#$%)
* 📋 Copy to Clipboard functionality
* 🎨 Beautiful UI with gradient and glassmorphism

---

## 🛠️ Tech Stack

* **Backend:** Python (Flask)
* **Frontend:** HTML, CSS
* **Libraries:**

  * string
  * secrets

---

## 📁 Project Structure

```
password_generator/
│
├── app.py
├── static/
│     └── style.css
├── templates/
│     └── index.html
└── README.md
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```
git clone https://github.com/your-username/password_generator.git
```

2. Navigate to project folder:

```
cd password_generator
```

3. Install Flask:

```
pip install flask
```

4. Run the application:

```
python app.py
```

5. Open in browser:

```
http://127.0.0.1:5000
```

---

## 📸 Screenshot

<img width="1919" height="915" alt="image" src="https://github.com/user-attachments/assets/62edd8e7-17a6-4baf-a26e-bf92790405bb" />


---

## 🎯 How It Works

* User selects password length and options
* Backend generates password using Python `secrets` module
* Strength is calculated based on:

  * Length
  * Character variety
* Crack time is estimated based on strength

---

## 💡 Future Improvements

* 🌙 Dark Mode Toggle
* 💾 Save passwords in database
* 👁️ Show/Hide password
* 🔐 User login system

---

## 👨‍💻 Author

**AMSHU_RATHOD**
GitHub: https://github.com/ramavathamshu

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
