# 📧 AI Email Writer with Gmail Chrome Extension  

![React](https://img.shields.io/badge/Frontend-React.js-61DAFB?logo=react&logoColor=white)  
![Spring Boot](https://img.shields.io/badge/Backend-Spring%20Boot-6DB33F?logo=springboot&logoColor=white)  
![Spring AI](https://img.shields.io/badge/AI-Spring%20AI-brightgreen)  
![Gemini](https://img.shields.io/badge/Model-Google%20Gemini-4285F4?logo=google&logoColor=white)  
![Chrome Extension](https://img.shields.io/badge/Extension-Chrome-blue?logo=googlechrome&logoColor=white)  

---

## 📌 Overview  
**AI Email Writer** is a full-stack application that leverages **Google Gemini via Spring AI** to automatically generate professional and context-aware email responses.  
It includes a **Chrome Extension** that integrates directly with Gmail, adding a one-click **“AI Reply”** button for seamless email drafting.  

---

## ✨ Features  
- 📝 **AI-Powered Responses** → Generates personalized replies using Gemini.  
- 🔗 **Gmail Integration** → Chrome extension injects an "AI Reply" button into Gmail.  
- ⚡ **Full-Stack Architecture** → React.js frontend + Spring Boot backend with Spring AI.  
- 🔒 **Secure API Handling** → Gemini API key managed via environment configs.  
- 🌐 **Real-Time Processing** → Fetches email context, returns instant drafts.  

---

## 🛠️ Tech Stack  
- **Frontend**: React.js, Material UI  
- **Backend**: Spring Boot, Spring AI  
- **AI Model**: Google Gemini API  
- **Extension**: Chrome Extension (Manifest V3, JavaScript, Gmail DOM handling)  
- **Others**: Axios, JSON parsing, secure API configs  

---

## 🚀 How It Works  
1. User selects an email inside Gmail.  
2. Chrome Extension injects an **“AI Reply”** button.  
3. On click → email content is sent securely to backend.  
4. Backend uses **Spring AI + Gemini API** to generate response.  
5. Draft reply is inserted into Gmail’s compose box instantly.  

---

## ⚙️ Setup & Installation  

### 🔹 Backend (Spring Boot + Spring AI)  
1. Clone repo and navigate to `backend/`  
2. Configure `application.properties` with:  
   ```properties  
   spring.application.name=email-writer-sb
   gemini.api.url=...
   gemini.api.key=...
---

## Run the Project  
### Backend  
cd email-writer-sb  
mvn spring-boot:run  
### Frontend  
cd email-writer-react  
npm install  
npm run dev  

---

## Author  
- Jai Anand


