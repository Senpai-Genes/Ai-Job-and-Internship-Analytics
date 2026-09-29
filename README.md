AI Job & Internship Analytics Platform

A full-stack web application that helps users discover relevant job and internship opportunities using machine learning, while providing job-market analytics through interactive dashboards.

🚧 Project Status

In Development

This project is being developed as a two-person team.

---

📌 Overview

The platform combines:

- Job and internship search
- User profiles and skill management
- ML-based job matching
- Personalized job recommendations
- Job-market analytics
- Interactive data visualizations
- User authentication and role-based access

The goal is to combine full-stack development, machine learning, and data analytics into one practical application.

---

✨ Planned Features

👤 User

- User registration and login
- JWT-based authentication
- User profile
- Add and manage skills
- Search and filter jobs
- View job details
- Apply for jobs
- Track applications
- View personalized job recommendations

🤖 Machine Learning

The system will analyze a user's profile and compare it with job requirements to generate a job-match score.

Example:

User Skills:
Python, Django, SQL, React

Job:
Backend Developer

Match Score:
87%

The ML component will include:

- Data preprocessing
- Feature engineering
- Model training
- Model evaluation
- Job matching
- Recommendation generation

📊 Job Market Analytics

The platform will provide insights such as:

- Most demanded skills
- Job distribution by location
- Experience requirements
- Salary analysis
- Job-category distribution
- Skill combinations
- Entry-level job trends

Detailed analytics will also be developed using Power BI.

---

🛠️ Tech Stack

Frontend

- React
- JavaScript
- HTML
- CSS

Backend

- Python
- Django
- Django REST Framework

Database

- PostgreSQL

Authentication

- JWT

Machine Learning

- Python
- Pandas
- NumPy
- Scikit-learn

Data Analytics

- Pandas
- Matplotlib
- Seaborn
- Power BI

Development Tools

- Git
- GitHub
- Postman

---

🏗️ System Architecture

                    React Frontend
                          |
                          | REST API
                          ↓
                Django REST Framework
                     /           \
                    /             \
                   ↓               ↓
             PostgreSQL        ML Model
                   |               |
                   |               ↓
                   |        Job Match Score
                   |               |
                   └───────┬───────┘
                           ↓
                  Job Recommendations


              Job Dataset
                   |
                   ↓
             Data Cleaning
                   |
                   ↓
                  EDA
                   |
                   ↓
               Power BI
                   |
                   ↓
          Job Market Analytics

---

📂 Project Structure

AI-Job-Analytics-Platform/
│
├── frontend/
│   └── ...
│
├── backend/
│   └── ...
│
├── ml/
│   └── ...
│
├── analytics/
│   └── ...
│
├── dataset/
│   └── ...
│
└── README.md

---

📈 Data Pipeline

Raw Job Dataset
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
       ├──────────────→ Power BI Analytics
       │
       ↓
Machine Learning Model
       ↓
Job Matching
       ↓
Recommendations

---

🔐 Authentication

The application will use JWT-based authentication.

User
 ↓
Login
 ↓
Django verifies credentials
 ↓
JWT Token
 ↓
Authenticated API Requests

Protected APIs will use authentication and appropriate permissions.

---

👥 Team Contributions

Developer 1 — Full Stack & Machine Learning

- React frontend
- Django backend
- Django REST Framework APIs
- PostgreSQL database
- JWT authentication
- API integration
- Machine learning model
- Job matching and recommendation system
- Deployment

Developer 2 — Data Analytics

- Data collection
- Data cleaning
- Exploratory Data Analysis
- Statistical analysis
- Data visualization
- Power BI dashboard
- Job-market insights
- Supporting ML feature analysis

Both developers will collaborate on API integration, testing, documentation, and deployment.

---

🗓️ Development Roadmap

- [ ] Select and validate dataset
- [ ] Design database
- [ ] Set up Django backend
- [ ] Create REST APIs
- [ ] Implement JWT authentication
- [ ] Build React frontend
- [ ] Implement job search
- [ ] Implement applications
- [ ] Perform EDA
- [ ] Build Power BI dashboard
- [ ] Prepare ML dataset
- [ ] Train ML model
- [ ] Implement job matching
- [ ] Build recommendation system
- [ ] Integrate analytics
- [ ] Testing
- [ ] Deployment
- [ ] Documentation

---

🚀 Future Improvements

- Resume parsing
- Automatic skill extraction
- Improved recommendation algorithms
- More job-market data
- Real-time job data ingestion
- Email notifications
- Advanced recruiter features

---

👨‍💻 Team

Developer 1: Sourik Paul
GitHub:Senpai-Genes 

Developer 2: Swastik Chakraborty 
GitHub:swxstik31 

---

📄 License

This project is developed for educational and portfolio purposes.
