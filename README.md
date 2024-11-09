# Water_Quality_Prediction

**Introduction**

The AI Water Quality Prediction system is designed to monitor river water quality, leveraging data from IoT sensors dataset from the rivers and using advanced machine learning models for accurate predictions. This solution is cost-effective, designed for accessibility, and can provide actionable insights to improve water quality management.

# Technologies Used

- **FastAPI**: For building the web API and handling HTTP requests.
  
- **pandas**: For loading and processing water quality data.
  
- **scikit-learn**: For machine learning tasks including data scaling, imputation, and model training.
  
- **HTML/Jinja2**: For rendering the web interface.

# Installation

1. **Clone this repository:**

    ```bash
    git clone https://github.com/Sreejith2003/Water_Quality_Prediction
    ```

2. **Install required dependencies:**

    ```bash
    pip install fastapi scikit-learn pandas numpy jinja2
    
    ```

4. **Run the application:**

    ```bash
    python app.py
    
    ```


# Features

- Water Quality Prediction: Predicts if water is polluted or not based on various water parameters.
  
- State and Location Filtering: Users can select a state and location to get a water quality prediction for that area.
  
- Model Training and Inference: The application preprocesses the data, trains a RandomForestClassifier model, and uses it for making predictions.
  
- Web Interface: An interactive web interface to input location details and get water quality predictions.

# Future Developments

- Realtime satellite data forcasting and monitoring
  
- Local community Forum
  
- Feedback from the user
