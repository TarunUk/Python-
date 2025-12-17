# Automated Resume Generator

This project is a simple **Automated Resume Generator** developed using Python. It allows users to generate a professional resume automatically by providing basic details. The project focuses on automation and simplicity and can run on different systems with minimal setup.

---

## 📌 Project Overview

Creating resumes manually can be time-consuming and repetitive. This project solves that problem by generating a formatted resume automatically from user input. The output resume is generated in HTML format, which can be easily viewed in a web browser.

The project is suitable for students, beginners, and academic submissions.

---

## 🎯 Objectives

* To automate the process of resume creation
* To reduce manual formatting effort
* To generate resumes with a consistent structure
* To make the project easy to run and share

---

## 🛠 Tools and Technologies

* **Python** – Core application logic
* **HTML** – Resume template and output
* **Docker** – Packaging the application for easy execution
* **Command Line Interface (CLI)** – Running the project
* **Git & GitHub** – Version control and project sharing

---

## ⚙️ How the Project Works

1. User provides resume details through input
2. Python script processes the input data
3. Data is mapped to a predefined resume template
4. Resume is generated automatically in HTML format
5. Output file is saved in the output folder

---

## ▶️ How to Run the Project (Without Docker)

1. Make sure Python is installed on your system
2. Open command prompt in the project folder
3. Run the following command:

```bash
python generate_resume.py
```

4. The generated resume will be available in the output folder

---

## ▶️ How to Run the Project (Using Docker)

1. Make sure Docker is installed
2. Build the Docker image:

```bash
docker build -t resume-generator .
```

3. Run the container:

```bash
docker run -it resume-generator
```

4. Resume will be generated automatically

---

## 📂 Project Structure

```
project-folder/
│── generate_resume.py
│── templates/
│── output/
│── Dockerfile
│── README.md
```

---

## ✅ Features

* Automated resume generation
* Easy to use
* Consistent formatting
* Portable and reusable
* Beginner-friendly project

---

## 🔮 Future Enhancements

* Add multiple resume templates
* Convert into a web-based application
* Export resume as PDF
* Add form-based input

---

## 📄 Conclusion

This project demonstrates how simple automation can make resume creation easier and faster. It is a practical project for learning Python automation and basic application packaging concepts.

---

## 📚 References

* Python Official Documentation
* HTML Reference Guides
* Docker Documentation

---

**Author:** Tarun Rajput
