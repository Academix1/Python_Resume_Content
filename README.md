
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

**Description:**  
The **Interview App** is an advanced platform designed to simulate and enhance real-time interview experiences. It integrates user authentication, dynamic question loading, voice-based responses, and automated analysis through ChatGPT, providing users with personalized feedback and real-time assessments. This app is tailored for job seekers, helping them prepare for interviews by delivering an interactive and insightful practice environment, coupled with AI-driven feedback on their performance.

---

#### **Frontend (React):**
- **User Authentication:**  
  Secure **JWT (JSON Web Tokens)** based authentication ensures seamless user login and session management. Users' credentials are validated and tokens are stored securely in **local storage**, ensuring a consistent experience across sessions without the need to log in repeatedly.

- **Dynamic Question Loading:**  
  Interview questions are fetched dynamically from the backend, allowing for a personalized experience that adapts to each user’s progress. New questions are served as the user moves through the interview process, preventing repetitive content and providing a fresh challenge with each session.

- **Voice Input Collection:**  
  By integrating the **Web Speech API**, the app allows users to respond to interview questions using voice input. This feature transcribes voice responses in real-time, enhancing the natural feel of the interview and promoting a more interactive experience. The transcribed text is then sent to the backend for further analysis and assessment.

- **User Interface:**  
  The app boasts an intuitive and user-friendly design that facilitates smooth navigation throughout the interview. The interface includes features like interactive question prompts, real-time voice input collection, progress tracking, and immediate feedback displays, ensuring an engaging and efficient experience for the user.

---

#### **Backend (Django):**
- **User Authentication:**  
  The backend implements **JWT Authentication** to manage user sessions securely. Passwords are encrypted using **BCrypt** to safeguard sensitive data, ensuring user credentials remain secure during login and session maintenance.

- **Database Management:**  
  The backend stores interview questions and user responses in a relational database, with data retrieval managed efficiently through **Django ORM**. The backend ensures smooth interaction with the database, including dynamic loading and storage of interview content, and supports easy database migrations via **Django Migrations**.

- **Voice Data Handling:**  
  The backend processes transcribed responses received from the frontend in real-time. These responses are forwarded to the **ChatGPT API** for further analysis. This allows the backend to evaluate and assess each user's performance based on their spoken input.

- **ChatGPT Integration:**  
  Integrated with **OpenAI’s GPT API**, the backend sends transcribed user responses for evaluation. ChatGPT analyzes the responses, providing a detailed assessment based on key factors like relevance, accuracy, clarity, and completeness, making the process of feedback generation seamless and AI-powered.

- **Assessment and Feedback:**  
  After processing each response, the backend generates customized feedback based on the analysis from **ChatGPT**. The feedback is designed to be constructive and detailed, providing specific insights into the user's performance, along with actionable recommendations for improvement.

---

#### **Project Flow:**

1. **User Authentication:**  
   - The user logs into the app, and a **JWT token** is generated, stored securely in **local storage** for session management.
   - User credentials are authenticated, enabling access to the interview session.

2. **Question Management:**  
   - The backend fetches interview questions from the database and presents them dynamically to the user. The questions are presented one at a time, ensuring focus on each individual prompt.

3. **Voice Input Collection:**  
   - The user provides a voice response, which is transcribed in real-time via the **Web Speech API**.
   - The transcribed response is sent to the backend for further processing and analysis.

4. **Response Analysis and Assessment:**  
   - The backend processes the transcribed response and forwards it to the **ChatGPT API** for analysis.
   - ChatGPT evaluates the response based on accuracy, clarity, relevance, and completeness, and generates feedback.

5. **Feedback Display:**  
   - The frontend presents the AI-generated feedback, allowing users to review their performance and gain insights for improvement.
   - The app tracks progress over time and offers personalized recommendations to enhance the user's interview preparation journey.

---

#### **Key Technologies:**
- **Frontend:** React.js, Web Speech API, JWT Authentication, Redux (for state management).
- **Backend:** Django, Django REST Framework (DRF), JWT Authentication, OpenAI ChatGPT API.
- **Database:** PostgreSQL or MySQL (Relational Database), Django ORM for data interaction.

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
