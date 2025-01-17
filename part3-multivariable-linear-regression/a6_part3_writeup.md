# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
0.86 meaning the model is 86% accurate.
2. Is your model accurate? Why or why not?
I would say the model is fairly accurate but not perfect since its r squared value is 0.86 but there still is variation.
3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?
For the 10 year old car, the model says it is worth $10,601.26. For the 20 year old car, the model says it is worth $2,802.54.
4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening?
I think this is happening cause the age and mileage are so high that it exceeds the threshold of the model causing it to go below zero and into the negatives.