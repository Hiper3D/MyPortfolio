# 💻 IDE-Themed Personal Portfolio: Source Code

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## 📋 Project Overview
This repository contains the source code for my personal portfolio. To demonstrate frontend proficiency and architectural control, I designed and built a custom, zero-dependency web application styled as a modern code editor (IDE). 

The application behaves like a lightweight SPA (Single Page Application [a web app or site that interacts with the user by dynamically rewriting the current web page with new data from the web server, instead of the default method of a web browser loading entire new pages]). It uses Vanilla JavaScript to dynamically inject content into the DOM based on user interaction, resulting in lightning-fast load times and seamless navigation.

## 🚀 Live Environment
**View the Live Portfolio:** [ d1m1fa948besma.cloudfront.net ]

## 🛠️ Frontend Architecture & UI/UX Design

### 1. Zero-Dependency Tech Stack
* **HTML5 & CSS3:** Custom CSS variables (`:root`) used for strict theme management (GitHub Dark Dimmed palette). Implemented a fully responsive Flexbox layout.
* **Vanilla JavaScript (ES6+):** Utilized modern JS features (template literals, arrow functions, dynamic rendering) to manage application state and content injection without external libraries.

### 2. Dynamic Component Rendering
* **File Explorer Simulation:** Built a functional, collapsible sidebar that maps JSON-structured project data to interactive DOM elements.
* **State Management:** Tracks active files and toggle states (`isProjectsOpen`, `activeFileId`) to update breadcrumb navigation and UI highlighting dynamically.

### 3. Mobile-First Responsiveness
* Engineered a custom mobile header with a hamburger toggle that triggers a smooth off-canvas sidebar transition, ensuring the complex IDE layout remains highly usable on mobile viewports.

---

## ☁️ Cloud Infrastructure & Deployment
I do not use basic shared hosting for this project. The source code in this repository is securely deployed on a custom, production-grade **AWS [Amazon Web Services - a comprehensive cloud computing platform]** architecture. 

* **Storage:** Amazon S3 [Simple Storage Service - an object storage service provided by Amazon for storing files] (Private Origin)
* **Delivery:** Amazon CloudFront [Content Delivery Network - a system of distributed servers that deliver content to users based on their geographic location] (Global Edge Caching)
* **Security:** OAC [Origin Access Control - a security feature that restricts access to your storage so only your distribution can read it] & End-to-End HTTPS [Hypertext Transfer Protocol Secure - the encrypted and secure version of the standard web protocol] Enforcement

🔗 **[View the complete AWS Infrastructure Documentation Here](https://github.com/Hiper3D/aws-S3-static-hosting)**

---

## 👤 Author
**Priyanshu Patra**
*Aspiring Software & Cloud Network Engineer focused on AI-Augmented Development and scalable cloud infrastructure.*
