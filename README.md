## <centered>Linear Regression Analysis: House Prices in the USA </centered>

This project uses a linear regression model to predict the prices of houses in the USA based on several factors. The model takes the following inputs:

- Average income earned by people in the area
- Average age of houses in the area
- Average number of rooms in houses within the area
- Average number of bedrooms in houses within the area
- Population of the area

The model uses these inputs to predict the prices of houses in the area.

### <b>Getting Started </b>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

<b>Prerequisites </b>
You will need to have Python 3 and the following libraries installed on your machine:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

You can install these libraries using pip:

_pip install numpy pandas scikit-learn_

Running the model
To use the model, you can simply import it and use it like so:

Copy code
from house_prices import predict_price

## inputs
average_income = 50000
average_age = 10
average_rooms = 3
average_bedrooms = 2
population = 1000

## get the predicted price
predicted_price = predict_price(average_income, average_age, average_rooms, average_bedrooms, population)
The function predict_price takes the five inputs mentioned above and returns the predicted price of a house in the area.

### Built With

- Python 3
- NumPy
- Pandas
- scikit-learn

<b> <h2>Authors</h2>
Name: Jacktone Etemesi

Email: jacktoneetemesi1@gmail.com




