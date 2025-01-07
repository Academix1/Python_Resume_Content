# Resume Content

## **Summary**

I’m a passionate FullStack Developer (Python) with hands-on experience in end-to-end web application projects. I enjoy building responsive UIs with React, developing robust backends using Python and Django, and tackling coding challenges on platforms like HackerRank to continuously improve my skills. Excited to bring my creativity, coding passion, and problem-solving mindset to a dynamic team.

## **Skills**

### **Programming Language**

- Python

### **Frontend Technologies**

1. React.js
2. HTML
3. CSS
4. JavaScript
5. Redux

### **Backend Technologies**

1. Django
2. RESTful APIs
3. Maven

### **Databases**

1. H2db
2. MongoDB

### **Libraries/Frameworks**

1. Django
2. Django REST Framework (DRF)
3. Django JWT Authentication (djangorestframework-simplejwt)
4. Django Migrations
5. Django Celery (Optional for Background Tasks)
6. Django MongoDB Integration (with pymongo or djongo)
7. Django Admin Panel
8. Django CORS Headers
9. Django Logging (for Activity Logging)
10. Django Email (for Notifications)

### **API Tools**

1. Django REST Framework (DRF)
2. Postman
3. Axios

### **Version Control**

1. Git
2. GitHub

### **Problem Solving**

- HackerRank

## **Projects**


### **Frontend (React):**
- Managed **user authentication** with JWT tokens for secure login and session handling, ensuring efficient token validation and storage in local storage.
- Implemented **form validation algorithms** using regular expressions for fields like email, password, and course details to ensure secure and valid data submission.

### **Backend (Django):**
- **User Authentication**: Used **JWT (JSON Web Tokens)** for secure user authentication and password encryption. Implemented secure token-based authentication with **`djangorestframework-simplejwt`** to handle user login and session management efficiently.
- **Database Modeling**: Created relational models for courses and user progress, implementing **Foreign Key** relationships and ensuring data integrity through **Django Migrations**.

---

### **Project 1: User Authentication Microservice**
#### **Frontend (React):**
- Managed **user authentication** flow with form validation using **regular expressions** for secure input validation (e.g., password strength, email format).
- Stored JWT tokens in **local storage** for secure, persistent sessions.  

#### **Backend (Django):**
- Used **JWT Authentication** for handling secure login sessions.
- Implemented **password encryption** with **BCrypt** to store user credentials safely.
- Integrated **JWT-based user authentication system** using `djangorestframework-simplejwt`, ensuring secure login and registration processes.

---

### **Project 2: Course CRUD Operations Microservice**
#### **Frontend (React):**
- Implemented a dynamic **course management UI** that allows users to add, update, and delete courses. Used **arrays** to manage the list of courses on the frontend and updated the UI using **state management** via **Redux**.
- Applied **sorting algorithms** to display the courses in chronological order, showing the latest added courses at the top.

#### **Backend (Django):**
- Developed **CRUD APIs** using Django REST Framework (DRF) to manage course data.
- Created models for **Course** with attributes like title, description, and video URL. Implemented **RESTful APIs** to handle course creation, updating, retrieval, and deletion.
- Optimized data retrieval and storage with **Django ORM** for seamless database interactions.

---

### **Project 3: Activity Logging Microservice**
#### **Frontend (React):**
- Used **local storage** and **session management** for tracking user actions in the app (such as course views, interactions, etc.).
- Implemented **pagination algorithms** to efficiently display past activities without overwhelming the user, retrieving activity logs in manageable chunks.

#### **Backend (Django):**
- Integrated **MongoDB** for storing user activity logs and actions within the platform.
- Used **Django MongoDB integration** to connect the Django app with MongoDB for scalable activity tracking.
- Optimized the logging system with **indexing algorithms** to quickly retrieve and filter user activities by date or course.

---

### **Project 4: AI-Powered Quiz Generation and Course Recommendation Microservice**
#### **Frontend (React):**
- Implemented a dynamic quiz generation interface that interacts with the backend for real-time quiz generation based on course progress.
- Managed user inputs using **hash maps** to store quiz answers and results, ensuring efficient data management and user interaction.

#### **Backend (Django):**
- Integrated **OpenAI API** for generating AI-powered quizzes based on user progress.
- Implemented **recommendation algorithms** that analyzed user course completions and interactions to suggest relevant courses.
- Employed **data modeling** to link user data and course details for personalized recommendations.

---

### **Project 5: Progress Tracking and Notifications Microservice**
#### **Frontend (React):**
- Used **arrays** to dynamically track the user’s progress in each course and display completion percentages and milestones.
- Incorporated **state management** using **Redux** to update user progress in real-time as they interact with course materials.

#### **Backend (Django):**
- Implemented **progress tracking models** to store and update user progress data across various courses.
- Integrated **Celery** for handling background tasks related to real-time progress tracking and **email notifications** for user progress milestones.
- Used **Django REST Framework** for pushing progress updates and sending notifications to users based on their activities.

---

# Additional Projects

### **Movie App**
**Description**: A feature-rich movie app to explore popular movies, search by genre, and create personalized watchlists. It fetches movie data from a third-party API using Axios.  
**Technologies Used**: React.js, Redux, Axios, HTML, CSS, JavaScript

---

### **Weather App**
**Description**: A weather forecasting app that provides real-time updates and a 5-day weather outlook for any location.  
**Technologies Used**: React.js, Redux, Axios, HTML, CSS, JavaScript

---

# Mini Projects

### **Calculator**
**Description**: A functional calculator web application capable of performing basic arithmetic operations. Designed with an intuitive UI to enhance usability.  
**Technologies Used**: HTML, CSS, JavaScript

---

### **Personal Portfolio**
**Description**: This project showcases a portfolio website with a focus on clean design and responsiveness. The site features sections like "About Me," "Projects," "Skills," and "Contact." Visitors can explore past projects and reach out through the contact form.  
**Technologies Used**: HTML, CSS

---

### **ATM Functionality**
**Description**: Developed an ATM simulation backend application to mimic banking functionalities such as balance inquiries, deposits, and withdrawals.  
**Technologies Used**: Python

---

### **Inventory Management**
**Description**: A Python-based application to manage inventory with features for adding, removing, and tracking items in stock.  
**Technologies Used**: Python
"""


