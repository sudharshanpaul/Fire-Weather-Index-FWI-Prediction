
# FWI Prediction using Machine Learning

This project predicts the Fire Weather Index (FWI) based on environmental conditions such as temperature, humidity, wind speed, and rainfall. The prediction helps to anticipate fire risks in specific regions.


## Features

- User-friendly web interface for inputting data and displaying predictions.

- Predicts FWI using a machine learning model (Ridge Regression).

- Dark mode interface for better usability.

- Persistent input values after submission.


## Technologies Used
- **Flask:** For building the web application.

- **HTML/CSS:** For creating a responsive and visually appealing user interface.

- **Scikit-learn:** For implementing the Ridge Regression model.

- **Pickle:** To save and load the trained machine learning model and scaler.
## Prerequisites
Ensure you have the following installed:

- **Python** (3.8 or higher)

- **Flask**

- **Scikit-learn**
## Setup Instructions

1.Clone this repository:

```bash
  git clone https://github.com/sudharshanpaul/Fire-Weather-Index-FWI-Prediction
```

2.Install the required dependencies:
```bash
  pip install -r requirements.txt
```

3.Ensure the trained Ridge Regression model (`ridge.pkl`) and scaler (`scaler.pkl`) are present in the models/ directory.

4.Run the Flask application:
```bash
  python app.py
```

5. Open your web browser and navigate to:
```arduino
  http://127.0.0.1:5000/
```

    
## Usage
1.On the home page, click Go to Predictions.

2.Enter the required environmental data in the provided fields:

- Temperature
- Relative Humidity
- Wind Speed
- Rainfall
- Fine Fuel Moisture Code (FFMC)
- Duff Moisture Code (DMC)
- Initial Spread Index (ISI)
- Classes
- Region

3.Click **Predict** to get the FWI prediction.
## Home Page

![image alt](https://github.com/sudharshanpaul/Fire-Weather-Index-FWI-Prediction/blob/033cbe2ea18ddc50970bf942921afe404517e061/Screenshot%202024-12-28%20162548.png)
## Prediction Page
![image alt](https://github.com/sudharshanpaul/Fire-Weather-Index-FWI-Prediction/blob/c0eb194105a8793e8f64d523be49501bfcde1cc0/Screenshot%202024-12-28%20163613.png)
## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

