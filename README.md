# ML-for-Classification-of-Tomatoes-Using-Particle-Argon

With this project classify your tomatoes into Grade A, Grade B and Grade C with TensorFlow Lite and Particle Argon.

My basic purpose is to analyze what, why and how things are used in this project along with the code...

Hardware components

* 1 Particle Argon
* 1 Adafruit TCS34725

Software apps and online services

* Particle Build Web IDE
* TensorFlow	

Tomato is one of the most popular and widely grown vegetable crops in the world. It belongs to the family Solanaceae. It is one of the very perishable fruit and it changes continuously after harvesting. Depending on the humidity and temperature it ripens very soon, ultimately resulted in poor quality as the fruit become soft and unacceptable. Color in tomato is the most important external characteristic to assess ripeness and post harvest life, and is a major factor in the consumer’s purchase decision. Degree of ripening is usually estimated by color charts. There are six ripening stages reflecting human ability to differentiate ripeness: green, 100% green; breaker, a noticeable break in color with lesser than 10% of other than green color; turning, between 10 and 30% of surface, in the aggregate, of red(ish) color; pink, between 30 and 60% of red(ish) color; light red, between 60 and 90% and red, more than 90% red. We have taken 3 stages and classified them into grades.

Hardware

We have used Particle Argon for computations and Adafruit TCS34725 sensor to capture the colors.

Training Data

The data for training was collected from the sensor using a simple code.

This code prints data in serial monitor. The Red, Green and Blue values are copied to an excel sheet and is saved in CSV format.

The data is next uploaded in a new google colaboratory file which runs TensorFlow.

Google Colaboratory

TensorFlow is installed by another simple code

The data is uploaded and visualized in pixels

The model is built and Trained

Then we run the prediction

The data is then converted into TensorFlow Lite model and is embedded into.h file using python code

Running ML in Argon

The model.h file is then used with our code to run the prediction. We had successful output and the classification was done right.

Thank you
