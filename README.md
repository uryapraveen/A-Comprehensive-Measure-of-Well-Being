Project Title: A Comprehensive Measure of Well-Being (HDI Prediction)
Overview
This project leverages Machine Learning to predict the Human Development Index (HDI) based on key socio-economic indicators. The application utilizes a Linear Regression model to provide accurate forecasts, enabling data-driven insights into global well-being.

Live Application
You can access the live version of the project here:
https://hdiproject.onrender.com

Key Features
Predictive Modeling: Uses a trained Linear Regression model to estimate HDI scores.

User-Friendly Interface: A responsive web form built with HTML/CSS for easy data input.

Dynamic Results: Real-time updates displaying the predicted HDI score and development category.

Cloud Deployment: Fully deployed and accessible via the web using Render.

Tech Stack
Backend: Python (Flask)

Machine Learning: Scikit-Learn, Pandas, NumPy

Frontend: HTML5, CSS3, JavaScript

Deployment: Render

Project Structure
app.py: Main Flask application handling routing and model inference.

models/: Contains the serialized hdi_model.pkl and scaler.pkl files.

templates/: Contains the index.html frontend file.

static/: Contains CSS styling and project assets.

requirements.txt: List of necessary Python dependencies.

Installation Instructions
Clone the repository:
git clone https://github.com/uryapraveen/A-Comprehensive-Measure-of-Well-Being

Install the required dependencies:
pip install -r requirements.txt

Run the application locally:
python app.py

Performance Metrics
The model was evaluated and achieved an R-squared score of 0.981, indicating high predictive accuracy. Stress testing was conducted using Postman, confirming stable response times under concurrent user load.
