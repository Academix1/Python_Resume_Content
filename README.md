
# **Resume**

## **Summary**
I am a passionate Full-Stack Developer with hands-on experience in end-to-end web application projects. I enjoy building responsive UIs with React, developing robust backends using Python and Django, and tackling coding challenges on platforms like HackerRank to continuously improve my skills. I am excited to bring my creativity, coding passion, and problem-solving mindset to a dynamic team.

## **Skills**

### **Programming Languages**
- Python

### **Frontend Technologies**
1. React.js
2. HTML5
3. CSS3
4. JavaScript
5. Redux

### **Backend Technologies**
1. Django
2. RESTful APIs

### **Databases**
1. H2DB
2. MongoDB

### **Libraries/Frameworks**
1. Django
2. Django REST Framework (DRF)
3. Django Authentication (`djangorestframework-simplejwt`)
4. Django Migrations
5. Django Database Integration
6. Django CORS Headers
7. Django Logging (for Activity Logging)

### **API Tools**
1. Django REST Framework (DRF)
2. Postman
3. Axios

### **Deployment & Containerization**
1. Netlify
2. Docker

### **AI & Automation**
1. OpenAI
2. Codeium
3. Prompt Engineering

### **Version Control**
1. Git
2. GitHub

### **Problem Solving**
- HackerRank

---

## **Projects**

### **Interview App (Full-Stack Web Application)**

**Description:** Developed a comprehensive **Interview App** designed to simulate real-time interview assessments. The app seamlessly integrates user authentication, dynamic question loading, voice-based responses, and automated assessment using ChatGPT, providing a smooth, unified user experience.

---

#### **Frontend (React):**
- **User Authentication:** Handled secure user authentication using **JWT (JSON Web Tokens)**. Users sign in with their credentials, and their session is managed with JWT tokens stored securely in **local storage**.
- **Dynamic Question Loading:** Interview questions are loaded dynamically from the database and presented to the user for real-time interaction.
- **Voice Input Collection:** The app captures user responses through **voice input**, leveraging the **Web Speech API** for real-time transcription. Once transcribed, the text is sent to the backend for further processing.
- **User Interface:** Designed a user-friendly and intuitive interface to guide the user through the interview process, including question prompts, voice input collection, and feedback display.

---

#### **Backend (Django):**
- **User Authentication:** The backend uses **JWT Authentication** to securely handle user login sessions. Passwords are securely stored with **BCrypt** encryption for added security.
- **Database Management:** The app stores and manages interview questions and user responses in a relational database. Using **Django ORM**, the app retrieves questions from the database, ensuring smooth data interactions.
- **Voice Data Handling:** The backend receives transcribed text responses from the frontend, processes them, and forwards them to **ChatGPT’s API** for analysis.
- **ChatGPT Integration:** Integrated **OpenAI's GPT API** to analyze user responses. ChatGPT evaluates the answers, providing an **assessment** on the accuracy, relevance, and quality of the responses.
- **Assessment and Feedback:** After processing the user response, the backend generates detailed feedback based on ChatGPT's analysis. This feedback is sent back to the frontend to be displayed to the user.

---

#### **Project Flow:**
1. **User Authentication:**
   - The user logs into the app using their credentials.
   - JWT tokens are generated and stored in local storage for session management.

2. **Question Management:**
   - The app dynamically loads interview questions stored in the backend database.
   - The user is presented with questions one at a time for answering.

3. **Voice Input Collection:**
   - The app captures the user’s response through the voice input feature using the Web Speech API.
   - The transcribed response is sent to the backend for analysis.

4. **Response Analysis and Assessment:**
   - The backend sends the user’s transcribed response to **ChatGPT** for evaluation.
   - ChatGPT provides an analysis of the response and generates feedback based on criteria such as accuracy, completeness, and relevance.

5. **Feedback Display:**
   - The frontend displays the feedback, allowing the user to review their performance and improve for future interviews.
   - Users can track their progress over time and receive personalized tips based on past assessments.

---

#### **Key Technologies:**
- **Frontend:** React.js, Web Speech API, JWT Authentication, Redux for state management.
- **Backend:** Django, Django REST Framework (DRF), JWT Authentication, OpenAI ChatGPT API.
- **Database:** Relational database (e.g., PostgreSQL or MySQL), Django ORM for database interaction.

---


## **Additional Projects**

### **Movie App**

**Description:** Developed a dynamic OTT platform with TMDB API integration to provide up-to-date movie data. Created a responsive, user-friendly frontend using React, displaying movie information like titles, genres, release dates, and ratings. Implemented Redux for efficient state management, enhancing the app’s scalability and performance.

**Technologies Used:** React.js, Redux, Axios, HTML, CSS, JavaScript

---

### **Weather App**

**Description:** Built a real-time weather application with a responsive frontend using React, integrating a weather API for live data (temperature, humidity, etc.) worldwide. Enabled users to search locations and instantly view current weather updates, with a focus on smooth user experience and efficient API handling.

**Technologies Used:** React.js, Redux, Axios, HTML, CSS, JavaScript

---

## **Certifications**

- **HackerRank Certificate in Python**  
  Awarded for proficiency in solving Python-based challenges and demonstrating problem-solving skills.

- **Course Completed Certificate**  
  Completed various courses on platforms such as Coursera and Udemy, including topics in Python, Django, React, and Full-Stack Web Development.

---

This resume is now using clearer naming conventions and is ready for a Full-Stack Developer role. Let me know if you'd like to make any additional changes!
