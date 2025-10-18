# AI-ML-Driven-Crowd-Management-In-Indian-Railways
### Jabalpur Railway Station Passenger Footfall Prediction
This project analyzes passenger footfall at Jabalpur Railway Station and develops a predictive model using deep learning techniques to aid effective planning and scheduling of railway operations.

#### Project Overview
Passenger management at railway stations is a critical task for station authorities. This project explores factors affecting daily passenger footfall, including:
- Seasonality
- Weekends and holidays
- Weather conditions
- Temperature

Historical data comprising PRS (Passenger Reservation System) and NON-PRS data for Jabalpur station has been analyzed to understand trends and patterns in footfall.

A Bidirectional GRU (Gated Recurrent Unit) neural network has been implemented to predict passenger flow at the station. The model successfully predicts daily footfall with an accuracy of 81%, providing insights for effective scheduling and operational planning.

Key Features
- Analysis of historical passenger data
- Consideration of multiple external factors (season, weather, holidays, weekends)
- Prediction of daily passenger footfall using Bidirectional GRU
- Visualization of trends and prediction results

Installation

Clone the repository:

git clone https://github.com/your-username/jabalpur-railway-forecast.git


Install required dependencies:

pip install -r requirements.txt

Usage

Preprocess your data (note: original data is highly confidential and not included).

Train the model:

python train_model.py


Predict passenger footfall:

python predict_footfall.py

Note on Data

Confidentiality Warning: The passenger data used in this project is highly confidential and cannot be shared publicly. Users must replace it with their own data for experimentation.

Results

Achieved 81% accuracy in predicting daily passenger footfall

Helps railway authorities in planning, scheduling, and decision-making

License

This project is for educational and research purposes only.
