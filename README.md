# MyCalculator 🧮

MyCalculator is an **offline calculator web application** built with HTML, CSS, and JavaScript.

It provides both **Basic Mode** and **Scientific Mode**, allowing users to perform normal arithmetic calculations as well as scientific calculations. The calculator also includes a **calculation history** feature.

## ✨ Features

* ➕ Addition
* ➖ Subtraction
* ✖️ Multiplication
* ➗ Division
* 🔢 Decimal calculations
* 🧮 Scientific calculator mode
* 📐 Trigonometric functions:

  * sin
  * cos
  * tan
* 📊 Logarithmic functions:

  * log
  * ln
* √ Square root
* x² Square
* xʸ Power
* π Pi
* e Euler's number
* % Percentage
* ± Positive/negative conversion
* Parentheses
* 📝 Calculation history
* 🗑️ Clear calculation history
* 🔄 Switch between Basic and Scientific modes

## 🛠️ Technologies Used

* **HTML5** – Structure of the calculator
* **CSS3** – Styling and layout
* **JavaScript** – Calculator functionality and logic
* **Docker** – Containerization
* **Nginx** – Web server used inside the Docker container

## 📂 Project Structure

```text
MyCalculator/
│
├── index.html
├── Dockerfile
└── .dockerignore
```

## 🚀 Running the Calculator Locally

### Option 1: Run directly in a browser

Open `index.html` in your web browser.

The calculator can perform its calculations directly in the browser using JavaScript.

### Option 2: Run with Docker

First, build the Docker image:

```bash
docker build -t mycalculator .
```

Run the container:

```bash
docker run -d -p 8082:80 --name mycalculator-container mycalculator
```

Then open your browser and visit:

```text
http://localhost:8082
```

## 🐳 Docker Hub

The Docker image is available on Docker Hub as:

```text
20041803/mycalculator:latest
```

To pull the image:

```bash
docker pull 20041803/mycalculator:latest
```

To run it:

```bash
docker run -d -p 8082:80 --name mycalculator-container 20041803/mycalculator:latest
```

Then visit:

```text
http://localhost:8082
```

## 📚 Scientific Mode

Scientific Mode provides additional mathematical functions such as trigonometry, logarithms, powers, square roots, percentages, constants, and parentheses.

The trigonometric functions use **degrees** for their calculations.

## 📝 Calculation History

MyCalculator keeps a history of calculations made during the current session.

Users can:

* View previous calculations
* Select a previous result
* Clear the entire history

The history can store up to **50 calculations**.

## 🎯 Project Purpose

This project was created to practice:

* Web development
* HTML and CSS
* JavaScript programming
* JavaScript event handling
* Mathematical operations
* User interface design
* Docker containerization
* Git and GitHub

## 👩‍💻 Author

**Reddleyna20**

Built as a personal web development and programming project.

---

⭐ If you like this project, feel free to explore the code and try the calculator yourself!

