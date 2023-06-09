Module 13 Challenge

Description:

In this challenge I was tasked with creating a machine learning model that would predict if an applicant for a business loan would have a successful business and be able to pay their loan back. This was done with information from 34,000 other businesses who would previously been given this loan. 

Details:

The process begins with importing the nessecary libraries and functions:

![screenshot1](https://github.com/nahinhayat/Module13Challenge/blob/main/module13screenshots/Screen%20Shot%202023-06-13%20at%209.20.59%20PM.png)

Then the CSV file containing all the information for each business was read in as a DataFrame:

![screenshot2](https://github.com/nahinhayat/Module13Challenge/blob/main/module13screenshots/Screen%20Shot%202023-06-13%20at%209.22.22%20PM.png)

After dropping some columns, the data was put through the process of encoding, using OneHotEncoder:

![screenshot3](https://github.com/nahinhayat/Module13Challenge/blob/main/module13screenshots/Screen%20Shot%202023-06-13%20at%209.23.59%20PM.png)

With a new DataFrame containing all the encoded variables and the already numerical variables from the original DataFrame, we create datasets for the features and the target. Then the datasets are split into training and testing datasets and scaled as well:

![screenshot4](https://github.com/nahinhayat/Module13Challenge/blob/main/module13screenshots/Screen%20Shot%202023-06-13%20at%209.27.11%20PM.png)

After setting number of layers, neurons for each layer, and activation functions for each layer, the model is ready to be fit:

![screenshot5](https://github.com/nahinhayat/Module13Challenge/blob/main/module13screenshots/Screen%20Shot%202023-06-13%20at%209.29.53%20PM.png)

This model was then optimized into two different models, each with their own configuration of layers, neurons, and epochs. These are the results of all three models:

![screenshot6](https://github.com/nahinhayat/Module13Challenge/blob/main/module13screenshots/Screen%20Shot%202023-06-13%20at%209.31.06%20PM.png)

Author:
Nahin Hayat https://www.linkedin.com/in/nahinhayat/