🎨 SVG Drawing Web Application
📌 Project Title

Interactive SVG Drawing Tool with Authentication

📖 Project Description

This project is a fully responsive web application that includes:

User Signup and Login system

Secure page switching between authentication and drawing interface

Interactive SVG Drawing Tool

Shape selection (Freehand & Rectangle)

Color picker

Stroke width control

Undo and Clear functionality

Logout feature

The application is built using HTML, CSS, and JavaScript in a single file and runs entirely on the client side.

🎯 Course Outcome Mapping
CO1

Explain fundamental concepts of front-end development including:

HTML structure

CSS styling

JavaScript DOM manipulation

Event handling

SVG coordinate systems

LocalStorage usage

CO2

Develop interactive and responsive front-end applications using:

Dynamic DOM updates

Mouse event tracking

Real-time drawing functionality

Responsive UI design

⚙️ Technologies Used

HTML5

CSS3 (Flexbox, Media Queries)

JavaScript (ES6)

SVG (Scalable Vector Graphics)

Browser LocalStorage

💻 Hardware & Software Requirements
Hardware

Minimum i5 Processor

8GB RAM

Software

Google Chrome / Mozilla Firefox

Any code editor (VS Code recommended)

🚀 How to Run the Project

Create a file named:

svg-drawing-app.html


Paste the full project code into the file.

Open the file in any modern web browser.

No server setup is required.

🔐 Authentication System

Signup stores user credentials in LocalStorage

Login validates credentials from LocalStorage

Only authenticated users can access the drawing interface

Logout returns user to login page

⚠ Note:
This authentication is for demonstration purposes only and is not secure for production environments.

🖌 SVG Drawing Features
Supported Shapes

Freehand drawing (Path element)

Rectangle drawing (Rect element)

Controls

Color Picker

Stroke Width Selector

Shape Selector

Undo Button

Clear Canvas Button

Logout Button

🧠 How Drawing Works

mousedown → Starts drawing

mousemove → Updates shape dynamically

mouseup → Stops drawing

createSVGPoint() + matrixTransform() → Converts screen coordinates to SVG coordinates

📱 Responsiveness

The application uses:

Flexbox layout

Viewport units (vw, vh)

Media queries

It works on:

Desktop

Tablet

Mobile devices

📂 Project Structure

Since this is a lab experiment, everything is implemented in:

Single HTML File
│
├── HTML (Structure)
├── CSS (Styling)
└── JavaScript (Logic & Events)

🛠 Future Improvements

Add circle and ellipse shapes

Add line tool

Add download as SVG feature

Add backend authentication (Node.js + Express)

Store drawings in database

Add dark mode

Implement drawing history panel

📚 Learning Outcomes

After completing this project, you will understand:

SVG element creation using JavaScript

Event-driven programming

Coordinate transformation in SVG

Client-side storage using LocalStorage

Responsive UI design principles

Interactive front-end application development

📌 Author

Student Name:BLESSING NEH NDI
Course: BE CSE
Subject: Front-End Development Lab
Experiment: SVG Drawing Tool with Authentication