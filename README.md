# Car Price Prediction Web App

![Car Price Prediction](https://adspassets.blob.core.windows.net/1-3/content/service_forecasting.svg)

## Description

This web application is designed to predict the selling price of used cars based on various features such as the year of manufacture, present price, kilometers driven, fuel type, seller type, transmission, and the number of previous owners. The prediction model is built using the Random Forest Regression algorithm, trained on a dataset of historical car details.

## How it Works

1. Users can access the web application through their browser.
2. Upon loading the application, users will be presented with an interface to input car details like the year of manufacture, present price, kilometers driven, fuel type, seller type, transmission, and the number of previous owners.
3. After submitting the car details, the application processes the data and passes it through the trained Random Forest Regression model.
4. The model predicts the selling price of the car based on the provided information.
5. The predicted selling price is then displayed to the user on the web page.

## Features

- User-friendly interface to input car details.
- Prediction of the selling price with just a few clicks.
- Proper handling of categorical features like fuel type, seller type, and transmission.
- Error handling for invalid input or cars that cannot be sold.
- Real-time prediction using the trained Random Forest Regression model.

## Installation

1. Clone or download this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Flask application with `python app.py`.
4. Access the web application through your browser at `http://localhost:5000/`.

## Technologies Used

- Python![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
- Flask (web framework)![Flask](https://img.shields.io/badge/Flask-2.0.1-lightgrey)
- Scikit-learn (machine learning library)![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24.2-orange)
- Pandas (data manipulation library)![Pandas](https://img.shields.io/badge/Pandas-1.3.0-brightgreen)
- HTML/CSS (for frontend) ![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-5%2B%20%7C%204.01%20%7C%203-blueviolet)

## Dataset

The dataset used to train the Random Forest Regression model contains historical car details, including the year of manufacture, present price, kilometers driven, fuel type, seller type, transmission, and the number of previous owners. This dataset was preprocessed and used to train the machine learning model.

## Disclaimer

This web application provides an estimated selling price of used cars based on historical data. The predictions may not always be accurate and are for reference purposes only. The actual selling price may vary due to other factors not considered in this model.

## Future Improvements

- Addition of more features to enhance prediction accuracy.
- Support for more car brands and models.
- Deployment to a production server for public access.

## Author

- [Syed Razauddin Shahlal](https://github.com/syedshahlal)

Feel free to contribute to this project by opening issues or creating pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
