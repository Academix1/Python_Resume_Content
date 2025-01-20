
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

Here's an enhanced and more effective version of the **Interview App** description:

---

### **Interview App (Full-Stack Web Application)**

**Description:**  
The **Interview App** is a cutting-edge platform designed to simulate real-time interview assessments. It integrates core features like user authentication, dynamic question loading, voice-based response collection, and automated assessment powered by ChatGPT, creating an engaging and seamless experience for users. This app is ideal for individuals preparing for interviews by providing real-time feedback and personalized guidance.

---

#### **Frontend (React):**
- **User Authentication:**  
  Secure user authentication is managed using **JWT (JSON Web Tokens)**, ensuring that each session is uniquely validated. Credentials are stored securely in **local storage**, enabling persistent login sessions and smooth navigation throughout the app.

- **Dynamic Question Loading:**  
  Interview questions are dynamically fetched from the backend database. The system ensures that each question is delivered in real-time, based on the user’s progress.

- **Voice Input Collection:**  
  Leveraging the **Web Speech API**, the app enables users to provide voice responses. These responses are transcribed in real-time, providing a natural way to interact with the system. The transcribed text is sent to the backend for further analysis.

- **User Interface:**  
  The frontend is designed to be intuitive, guiding users through the interview process. The UI includes features such as question prompts, live voice input collection, and interactive feedback displays, ensuring an engaging experience.

---

#### **Backend (Django):**
- **User Authentication:**  
  The backend uses **JWT Authentication** to securely manage user sessions. **BCrypt** is utilized to encrypt user passwords, adding an additional layer of security to sensitive data.

- **Database Management:**  
  The backend stores interview questions and user responses in a relational database, managed through **Django ORM**. This allows for efficient retrieval, updates, and management of data. **Django Migrations** ensure smooth database updates.

- **Voice Data Handling:**  
  Transcribed responses from the frontend are received, processed, and sent to the **ChatGPT API** for analysis. The app handles voice data with efficiency, ensuring that each user’s response is accurately processed.

- **ChatGPT Integration:**  
  Integrated with **OpenAI’s GPT API**, the app leverages AI to analyze and assess the quality of user responses. The system evaluates responses based on various criteria, such as accuracy, clarity, relevance, and completeness.

- **Assessment and Feedback:**  
  After each interview response, the backend generates detailed feedback based on **ChatGPT’s analysis**. This feedback, tailored to each user’s performance, is sent back to the frontend for display, offering actionable insights and recommendations for improvement.

---

#### **Project Flow:**

1. **User Authentication:**  
   - Users log in using their credentials, and **JWT tokens** are securely stored in **local storage** for session management.

2. **Question Management:**  
   - The app fetches interview questions from the backend database and presents them one at a time. This ensures a smooth and focused interview experience.

3. **Voice Input Collection:**  
   - Users respond to questions using voice input, which is transcribed in real-time via the **Web Speech API**. These transcribed responses are sent to the backend for processing.

4. **Response Analysis and Assessment:**  
   - The backend sends the transcribed responses to **ChatGPT** for analysis. The AI evaluates the responses and generates detailed feedback based on accuracy, completeness, and relevance.

5. **Feedback Display:**  
   - Feedback is presented to the user, allowing them to review their performance. The app also tracks progress over time, offering personalized tips and suggestions for future improvement.

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
