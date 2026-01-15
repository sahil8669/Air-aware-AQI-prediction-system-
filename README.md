🌍 AirAware – Smart Air Quality Prediction System

AirAware is a full-stack Air Quality Monitoring and Prediction system designed to analyze air pollution data,
visualize trends, predict AQI levels, and provide health advisories. The project integrates backend APIs,
database handling, and machine learning logic to deliver a complete data-driven solution.
This project was developed with a strong focus on backend development, API handling, and ML
integration, following a milestone-based approach.

📌 Project Objectives

1. Monitor air quality data across cities (Maharashtra dataset)
2. Visualize PM2.5 and PM10 pollution trends
3. Predict AQI levels based on pollutant values 
4. Provide health advisories based on AQI
5. Enable data download and user interaction

🧩 Project Architecture (Flow)

1. Dataset Ingestion
2. Maharashtra AQI dataset is stored in the database
3. Data includes PM2.5, PM10, city, date, and other attributes
4. Backend Processing (Flask)
5. Flask handles routing, authentication, APIs, and ML logic
6. Environment variables are loaded securely using .env
7. Database Layer (MySQL)
8. Stores air quality data, users, and feedback
9. Queries aggregate pollution values for dashboards
10. Machine Learning & AQI Logic
11. AQI calculated using PM2.5 and PM10 weighted formula
12. AQI category mapping based on Indian AQI standards
13. Frontend Rendering
14. HTML templates render dashboards, charts, prediction pages
15. JavaScript fetches API data dynamically
 
⚙️ Tech Stack Used

1. Backend
   Python (Flask)
   MySQL
   dotenv (Environment configuration)
2. Machine Learning
   NumPy
   Scikit-learn (Linear Regression – basic AQI modeling)
3. Frontend
   HTML, CSS, JavaScript
   Chart-based visualizations

📂 Important Files & Their Role

1. .env

Stores sensitive database credentials securely: - DB_HOST - DB_USER - DB_PASSWORD - DB_NAME

2. app.py

Main backend application file: - User authentication (login/logout)- Dashboard data aggregation - AQI
prediction logic - Health advisory system - Chatbot logic - Language translation support - Data download
APIs

3. Dataset File

Maharashtra AQI dataset used for analysis and predictions

🔌 Key Features Explained

1️⃣ Dashboard
Displays city-wise average PM2.5 and PM10
Month-wise pollution trends via charts

2️⃣ AQI Prediction
Takes PM2.5 and PM10 inputs
Computes AQI using weighted formula
Categorizes AQI into Good, Moderate, Poor, etc.

3️⃣ Health Advisor
Provides health tips based on AQI range
Suggests mask usage and risk level

4️⃣ Chatbot Rule-based chatbot for AQI-related queries
Answers about pollution, masks, health risks

5️⃣ Data Download
Download full dataset as CSV
Download city-wise air quality data

6️⃣ Language Support
English & Hindi language switching

🚀 How to Run the Project

Step 1: Clone the Repository

git clone <repository-url>
cd airaware

Step 2: Create Virtual Environment (Optional)
python -m venv venv
venv\Scripts\activate

Step 3: Install Dependencies
pip install -r requirements.txt

Step 4: Configure Environment Variables
Create a .env file:
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=air_quality_db

Step 5: Setup Database
Create MySQL database air_quality_db
Import AQI dataset into air_quality table
Create required tables ( users , feedback )

Step 6: Run the Application

python app.py

Open browser and visit:

http://127.0.0.1:5000

🧪 Testing Flow

1. Login with valid credentials

2. View dashboard pollution trends

3. Predict AQI using PM values

4. Check health advisory

5. Download datasets

🎯 Milestone Contribution Summary

1. Backend Development: Complete Flask API design

2. API Handling: Dashboard, prediction, download, chatbot APIs

3. Database Integration: MySQL queries & aggregation

4. ML Integration: AQI calculation & prediction logic

🧾 Conclusion

AirAware successfully demonstrates how air quality data can be transformed into meaningful insights using
backend APIs, database systems, and machine learning logic. The project emphasizes real-world problem-
solving by combining data analysis, prediction, and health awareness into a single platform. This system
can be further extended with real-time sensors, advanced ML models, and modern frontend frameworks,
making it a strong foundation for scalable environmental monitoring solutions.

✨ Project developed as part of an academic major project focusing on Backend, APIs, and ML Integration.
