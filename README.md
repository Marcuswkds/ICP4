# ICP4

In Class Programming for basics of machine learning, models such as Naïve Bayes and Support Vector Classification. 

Marcus Wong Ken Ji

2/12/2021

Description of ICP:  machine learning, and how to implement models such as Naïve Bayes and Support Vector Classification on different data sets. I was also introduced to more modules and learn how to split the x and y data.

#Question 1 Code

![image](https://user-images.githubusercontent.com/72952948/107841218-918a5100-6d7e-11eb-90c6-910d1da417c7.png)

I started by importing the module pandas as pd and reading the 'train.csv' file. I was then able to find the correlation between the 'Sex' and 'Survived' columns. The output returned was 0.5433513806577551 which meant that we should definitely keep this feature because there is a high correlation between the 'Sex' and 'Survived' columns. In conclusionm, the correlation shows that if you were a female that is a higher chance of you surviving.

![image](https://user-images.githubusercontent.com/72952948/107841367-e9758780-6d7f-11eb-9f08-82c02faaac36.png)

#Question 2 Code

![image](https://user-images.githubusercontent.com/72952948/107841387-26417e80-6d80-11eb-8ded-3746f7e93122.png)

I began by implementing the modules and libraries such as pandas as pd and sklearn. I then used the 'type' columns as the predicted columns such as y_train and x_train. I used test_split to split the data into 2 and used a test size of  0.4. Using the GaussianNB model I was able to predic the y_test values by giving the x_test values to the model. Lastly I printed the accuracy by using the metrics module, and the result of the accuracy was 0.313953488372093.

![image](https://user-images.githubusercontent.com/72952948/107841608-e1b6e280-6d81-11eb-8887-3e40339f25da.png)
