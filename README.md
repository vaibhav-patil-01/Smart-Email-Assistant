# Smart Email Assistant  

An **AI-powered email assistant** built using **Spring Boot** and **Spring AI** that helps users **generate, organize, and optimize emails** with ease.  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://linkedin.com/in/vaibhavpatil2003)  
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black)](https://github.com/vaibhav-patil-01)  
[![Email](https://img.shields.io/badge/Email-vaibhavvpatil8%40gmail.com-red)](mailto:vaibhavvpatil8@gmail.com)  

---

## 🚀 Project Overview  
The **Smart Email Assistant** leverages **Generative AI** and **Spring Boot** to help users **write professional emails, auto-suggest subject lines, and summarize threads**.  
This project highlights my ability to **integrate AI APIs, design robust backend services, and build production-ready applications**.

---

# Smart Email Assistant  
![Java](https://img.shields.io/badge/Java-17-blue) 
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.0-green)
![React](https://img.shields.io/badge/React-18-blue)
![Google Gemini](https://img.shields.io/badge/AI-Google%20Gemini-orange)
![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-yellow)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

An **AI-powered Smart Email Assistant** that integrates directly into **Gmail** using a Chrome extension, enabling users to generate **personalized, context-aware email replies** with a single click.  
Built using **Spring Boot**, **Spring AI (Google Gemini)**, **ReactJS**, and **Chrome Extension APIs**.

---

## ✨ Features
- **AI-Powered Replies** – Generates context-aware, tone-customized email responses using Google Gemini.  
- **Gmail Integration** – Adds an “AI Reply” button directly in Gmail for instant use.  
- **Full-Stack Architecture** – Backend (Spring Boot + Spring AI), Frontend (ReactJS), and Chrome Extension.  
- **Customizable Tone** – Adjust reply tone (formal, casual, etc.) via prompts.  
- **Plug & Play Extension** – Works inside Gmail without disrupting workflow.  

---

## 🛠️ Tech Stack
- **Backend**: Java 17, Spring Boot, Spring AI  
- **AI**: Google Gemini  
- **Frontend**: ReactJS  
- **Browser Integration**: Chrome Extension (Content Scripts, MutationObserver)  
- **Build Tools**: Maven, npm  
- **Version Control**: Git & GitHub  

---

## 📂 Project Structure

```bash
smart-email-assistant/
│
├── backend/                              # Spring Boot backend
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/smartemail/      # Java code
│   │   │   │   ├── controller/           # REST controllers
│   │   │   │   │   └── EmailController.java
│   │   │   │   ├── service/              # Business logic
│   │   │   │   │   └── EmailService.java
│   │   │   │   ├── config/               # Configurations (CORS, AI, etc.)
│   │   │   │   │   └── GeminiConfig.java
│   │   │   │   └── SmartEmailAssistantApplication.java
│   │   │   └── resources/
│   │   │       ├── application.properties
│   │   │       └── static/               # (Optional) static assets
│   │   └── test/                         # JUnit tests
│   │       └── EmailServiceTest.java
│   └── pom.xml                           # Maven build file
│
├── frontend/                             # React frontend
│   ├── public/
│   │   ├── index.html
│   │   └── favicon.ico
│   └── src/
│       ├── components/                   # Reusable components
│       │   ├── GmailButton.js            # AI reply button
│       │   └── ReplyPreview.js           # Modal to preview AI reply
│       ├── pages/                        # App pages (if multi-page)
│       │   └── Home.js
│       ├── App.js
│       ├── index.js
│       └── styles/                       # CSS files
│           └── App.css
│   └── package.json
│
├── chrome-extension/                     # Chrome extension
│   ├── content.js                        # Injects AI button into Gmail
│   ├── background.js                     # Handles events & API calls
│   ├── popup.html                        # (Optional) Extension popup UI
│   ├── popup.js
│   ├── styles.css
│   └── manifest.json                     # Extension configuration
│
├── .gitignore
├── README.md
└── LICENSE

```
---

## 🔗 Connect With Me  
**Vaibhav Patil**  
- [LinkedIn](https://linkedin.com/in/vaibhavpatil2003)  
- [GitHub](https://github.com/vaibhav-patil-01)  
- [vaibhavvpatil8@gmail.com](mailto:vaibhavvpatil8@gmail.com)  

---
