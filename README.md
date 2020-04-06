# Neural Networks

## Project Overview
Explore and implement neural networks using the TensorFlow platform in Python. Discuss the background and history of computational neurons as well as current implementations of neural networks as they apply to deep learning.

## Resources
Data Sources: charity_data.csv<br>
Software: Jupyter Notebook, Python 3.7.6 <br>
Python dependencies: Pandas, Scikit-learn, TensorFlow

### Project Summary
Build your own machine learning model that will be able to predict the success of a venture paid by Alphabet soup. Your trained model will be used to determine the future decisions of the company—only those projects likely to be a success will receive any future funding from Alphabet Soup.

### Project Objectives
- Import, analyze, clean, and preprocess a “real-world” classification dataset.
- Select, design, and train a binary classification model of your choosing.
- Optimize model training and input data to achieve desired model performance.
 
### Code can be found [Here](https://github.com/hillarykrumbholz/Neural_Networks/blob/master/AlphabetSoupChallenge.ipynb)<br><br>

## Conclusion

#### How many neurons and layers were selected, and why?

To predict the success of an organization, a deep learning neural network was used. Deep learning models do not require as many neurons to have a high accuaracy, as they have additional layers that can identify and account for more information than a greater number of neurons in a single layer.

There are a total of 43 input features, and since it is important to not overfit a model, there were 7 neurons used in the first hidden layer and 3 neurons used in the second hidden layer. A third layer was considered; however, it did not offer a significant increase in accuracy. 

#### Was the target model performance achieved? What steps were taken to increase model performance?

Yes, the target performance was achieved. The model had an accuracy of 0.9992, meaning that it can predict if an organization will be successful with a 99.92% accuracy. There was a loss function of 0.0067, the lower the number indicates how good the model is at making a prediction. 

I played around with the model quite a bit, plugging in different neuron values into each of the hidden layers. The more neurons that were added, there was less accuracy and higher loss. I also looked at different activation functions - relu, sigmoid, and tanh. I finally settled on a sigmoid activation for the first hidden layer, a relu activation for the second hidden layer, and a sigmoid for the output. 

#### What different models could be implemented to solve this problem?

A random forest could also be used to accurately predict if an organization would be successful. Random forests only handle tabular data - which this dataset is comprised of. Random forests are much easier to run, interpret, and run at a faster rate. With this dataset a random forest was used and it had an accuaracy of 99.9%. If this model is to be shared with many people in the company, I would recommend using random forest as it is easer to digest and follow. 



