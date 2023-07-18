# deep-learning-challenge


Overview: 

This analysis aims to create a deep learning model using a neural network to predict the success of funding applicants for Alphabet Soup. By training a model on historical data, we aim to classify future applicants into successful or unsuccessful funding categories, assisting Alphabet Soup in making informed decisions. 

Results: 
•	Data Preprocessing
•	Target variable(s): The target variable for the model is the "success" or "failure" of funding applicants 
•	Feature Variables: all the relevant information about the applicant like classification, application type, affiliation, organization etc.
•	Variables removed: Even "EIN" and "NAME" initially did not contribute to the prediction. It did not give me a high accuracy, above 75%, however after a different approach, I decided to add the "NAME" column to my model and got an accuracy of 75% 
•	Compiling, Training, and Evaluating the Model
•	Neurons, layers, and activation functions: The first hidden layer has 30 neurons; The second hidden layer has 15 neurons, both of them using the ReLu; for my output layer, I use a single neuron with a Sigmoid activation function; this last layer will predict the success or failure of my model 
•	Goal Achievement: It reached an accuracy of 75.02% on the test data
•	Steps taken to increase model performance: Various techniques can be applied to improve model performance, such as adjusting the model architecture, tuning hyperparameters, increasing the training data size, regularizing the model, or using more advanced optimization techniques. Even after all these steps, I decide to add and binning Name column helping me to reach the minimum accuracy of 75%

 
4. Summary: The deep learning model developed using a neural network demonstrates moderate performance in predicting the success of funding applicants for Alphabet Soup. The model achieved an accuracy of approximately 75.02% on the test data.
 
As a recommendation, I will take a different approach because 75% is not a high accuracy of this model; exploring different algorithms may improve the accuracy. 

![image](https://github.com/yamilethcova/deep-learning-challenge/assets/124878139/bb5b1f1a-8463-41ff-9bd6-c2875383ba02)
