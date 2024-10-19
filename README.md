# Learning-Management-System (LMS) 🚀
This project is an intermediate-level Learning Management System (LMS) site built with Django. It provides essential features to manage learning resources and enhance the educational experience.

---

## 📥 Getting Started

### Step 1: Download the Project
- Download ZIP (or clone the repository).
- Extract the ZIP file to a local directory.

### Step 2: Install Dependencies
Ensure you have **Python** and **Django** installed on your machine.

- Install Python: [Download Python](https://www.python.org/downloads/)

- Install Django:  
  Open your terminal or command prompt and run:
  ```bash
  pip install django
  ```

### Step 3: Set up a Code Editor
We recommend **Visual Studio Code**:  
[Download Visual Studio Code](https://code.visualstudio.com/download)  
(Alternatively, use any code editor of your choice.)

---

## 🔧 Setting Up the Django Project

1. Open your terminal in the extracted project folder.
2. Create a new Django project:
   ```bash
   django-admin startproject lms_project
   ```
3. Inside the project, create a Django app named `learnbetter`:
   ```bash
   python manage.py startapp learnbetter
   ```

4. **Note!!!**  
   The `urls.py` file is **not automatically created** in the app directory.  
   You need to create it manually inside your `learnbetter` folder.

5. Copy the relevant code from the provided Python files into your app folder or move the files directly to the appropriate locations in your project.

---

## 🎥 Troubleshooting Setup Issues
If you encounter any setup problems, watch this helpful video:  
[Watch Video](https://youtu.be/f1NQnhFFV-E?si=YUkLWv8C5rSdby9z)

---

## 📄 Additional Information
Please refer to the **readMe.txt** inside the ZIP file for further details about the project.

---

## 🚀 Run the Project

1. Navigate to the project directory in the terminal:
   ```bash
   cd lms_project
   ```
2. Run the Django development server:
   ```bash
   python manage.py runserver
   ```
3. Open a browser and go to:  
   [http://127.0.0.1:8000](http://127.0.0.1:8000) to view the LMS site.

---

## 📝 Contributing
Feel free to fork this repository and contribute. Pull requests are welcome!

---

## 📃 License
This project is licensed under the **MIT License**.
