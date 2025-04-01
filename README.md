# Medical Recommendation System

## Overview
The **Medical Recommendation System** is a web-based application that provides personalized medical recommendations based on user health data. The system utilizes **Machine Learning (Scikit-Learn)** and **Flask** for backend processing and ensures the protection of sensitive health information.

## Features
- User authentication and secure data storage
- Health data input and analysis
- Machine learning-based recommendation engine
- REST API integration for frontend communication
- Interactive user interface

## Tech Stack
- **Backend:** Python, Flask, Scikit-Learn
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite
- **Machine Learning:** Scikit-Learn
- **Deployment:** Flask Server

## Installation
### Prerequisites
Ensure you have the following installed:
- Python (>= 3.8)
- pip
- Virtual Environment (optional but recommended)

### Steps to Set Up
1. **Clone the Repository**
   ```sh
   git clone https://github.com/Anilpurrum2011/Medical-Recommendation-System.git
   cd Medical-Recommendation-System
   ```

2. **Create and Activate Virtual Environment (Optional but Recommended)**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the Application**
   ```sh
   python app.py
   ```
   The application should now be running at `http://127.0.0.1:5000/`

## Usage
1. Navigate to `http://127.0.0.1:5000/`
2. Enter your health data
3. Receive medical recommendations based on your input

## API Endpoints
- **POST /predict** - Accepts user health data and returns medical recommendations.
- **GET /health-check** - Returns the status of the application.

## Folder Structure
```
Medical-Recommendation-System/
│── app.py            # Main application file
│── model.pkl         # Trained machine learning model
│── static/           # Static assets (CSS, JS)
│── templates/        # HTML templates
│── requirements.txt  # Dependencies
│── README.md         # Documentation
```

## Future Enhancements
- Improve recommendation accuracy with deep learning models
- Integrate user profiles for better personalization
- Deploy using cloud services (AWS, GCP, or Heroku) 

## Contributors
- **Anil Purrum** - [GitHub Profile](https://github.com/Anilpurrum2011)

## License
This project is licensed under the MIT License.

## Contact
For queries, contact **Anil Purrum** via [GitHub Issues](https://github.com/Anilpurrum2011/Medical-Recommendation-System/issues).
