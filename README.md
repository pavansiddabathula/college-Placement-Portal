**College Placement Portal**
============================

A full-stack web application designed to simplify and streamline college placement activities.This portal provides separate workflows for **Students** and **Placement Officers**, offering secure logins, job postings, job applications, training modules, preparation material, and more.Built with **React (frontend)** and **Spring Boot, Spring Security, Spring JPA (backend)** following industry-level clean architecture and RESTful API design.

🚀 **Overview**
---------------

The **College Placement Portal** is a web-based platform designed to simplify and streamline the entire campus placement process.It allows **students** to register, explore job opportunities, apply for roles, access training materials, get guidance, and stay updated about upcoming campus placements.At the same time, **placement officers** can manage job postings, share training resources, send notifications, and support students throughout the placement journey.

This platform brings students and placement teams into one organized system, making the entire placement workflow smooth, transparent, and easy to manage.


🧩 **Core Features**
--------------------

### **1\. Authentication & Authorization**

*   Student and Placement Officer logins
    
*   Role-based access control using Spring Security
    
*   JWT-based secure session management
    
## ✨ Key Features

### 👨‍🎓 Student Features
- **Student Registration & Login**  
  Students can create accounts, log in securely, and access personalized dashboards.

- **Apply for Jobs**  
  Browse available job openings posted by the placement cell and apply instantly.

- **Training Programs**  
  View available training programs (Aptitude, Communication Skills, Technical Skills) and register.

- **Placement Roadmaps**  
  Guided preparation path based on company patterns, rounds, and skill expectations.

- **Counselling & Guidance**  
  Access mentorship content, previous students’ experiences, and interview tips.

- **Placement Information**  
  Know about upcoming company visits, number of rounds, eligibility, and selection process.

- **Learning & Preparation Material**  
  Aptitude, coding, resume building, soft skills, company-specific resources, and more.

- **Email Notifications**  
  Students get email alerts when new jobs or training programs are posted.

---

### 🧑‍💼 Placement Officer Features
- **Login for Placement Team**
- **Add New Job Openings**
- **Update Job Details**
- **Delete Job Posts**
- **Manage Training Programs**
- **View Student Applications**
- **Send Notifications & Alerts**
- **Share Roadmaps and Guidance Materials**

---

## 🏗️ System Overview (Simple)
This portal connects **students** and **placement officers** on a single platform:

1. Placement officer posts job → student receives email → student applies.  
2. Placement officer posts trainings/guidance → students register & access.  
3. Students get complete placement-related information in one place.  
4. Officers can track job postings and manage placement activities.

---
🏗️ **Tech Stack**
------------------

### **Frontend**

*   React.js
    
*   HTML5, CSS3, JavaScript
    
*   Axios / Fetch API
    
*   Component-based modular design
    

### **Backend**

*   Spring Boot
    
*   Spring Security (JWT Authentication)
    
*   Spring Data JPA
    
*   MySQL / AWS RDS
    
*   RESTful APIs
    

### **DevOps / Cloud**

*   AWS EC2 (deployment)
    
*   AWS RDS (database)
    
*   GitHub for repository hosting
    

📦 **How It Works (High-Level Flow)**
-------------------------------------

1.  **User Registration & Login**
    
    *   Students and officers authenticate using JWT tokens.
        
2.  **Role-Based Access**
    
    *   Students only see student functionalities.
        
    *   Officers get admin privileges.
        
3.  **Job Posting System**
    
    *   Officers create jobs → stored via Spring JPA → displayed to students via React.
        
4.  **Job Application & Notifications**
    
    *   Students apply → backend updates status → student gets notification.
        
5.  **Training & Resources Access**
    
    *   Students browse training, roadmaps, preparation content.
        

📚 **Future Enhancements**
--------------------------

*   Resume Builder
    
*   Advanced analytics for placement officer
    
*   Mock test module
    
*   AI-based job recommendation for students
