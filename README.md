# Boston House Pricing Prediction

We perform a few wrangling on the dataset. We split it into training and testing purposes and scale the values using the StandardScaler. We create a LinearRegression model and train and test the model with a portion of the data. We perform EDA analysis to test the performance of our model.<br>
We predict house prices using variables including crime rate in the location, age of the building, distances to employment sectors and many others.

### Software and Tools Requirements

1. [GitHub Account](https://github.com)
2. [VS Code IDE](https://code.visualstudio.com)
3. [Heroku Account](https://heroku.com)
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment

```
conda create -p venv python==3.7 -y
```

Install neccessary libraries

```
pip install -r requirements.txt
```

Create a Web Application with flask

```
app = Flask(__name__)
```

Deploy Application onto Heroku

> Login to [Heroku](https://heroku.com) and create account

At the the end of the project, we get a front end application where we
input the necessary variables for predicting the price of the house.
<br>

![Image](Capture.JPG?)
