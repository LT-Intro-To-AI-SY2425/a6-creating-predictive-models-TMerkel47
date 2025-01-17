# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
The accuracy of the model dropped to 70% because the data has some points that hold more weight than others without scaling them leading to misconstrued data.
2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
It is 86% accurate with StandardScaler and I would say it is just under being accurate enough since I feel like with the goal of this model, at least 905-95% accuracy is achievable with more data.
3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
The model did fairly well. Problems started arising when inputs with high salaries were being used as the model became more inaccurate.
4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
According to the model, no. She would not buy an SUV.
