# Questions for the month of April
---
### 12/4/22 
***Ted wants to sell more cars***

Ted is just starting his first job.He is working at a major car dealership. Hundreds of cars go out the door every month, and Ted plans to help the company understand their customers a little bit more.After a week of obsessing over all the information they capture about every customer, Ted starts thinking about a good way to slice them into segments based on their characteristics.

The problem is that Ted is unsure about the best approach. Should he segment customers based on their purchase history, or should it be better to do it by age? What about the type of vehicle or purchase power?
How would you approach this problem if you were in Ted's shoes?
 Options-

 - [ ] Use an unsupervised learning algorithm to produce potentially interesting ways to segment the customers. 
 - [ ] Define beforehand a few segments, and train a supervised learning algorithm to classify every customer into one of them.
 - [ ] Use a supervised learning algorithm to produce potentially interesting ways to segment the customers.
 - [ ] Use a semi-supervised learning algorithm to process the data, thus taking advantage of both supervised and unsupervised techniques.
---
### 13/4/22
***Handling missing values***
    
The customer data the team received was not in great shape.After some analysis, they found that many values were missing, entire fields were incomplete, and some of the data was corrupted.Everyone knew they had to fix this before building the machine learning application they had been planning for a year. The team lead called a special meeting to discuss their next steps, and after some time, they narrowed it down to a few possibilities.

Which of the following are valid techniques they could use to handle the problems with their data?
 Options-
  
 - [ ] Replace missing values with the mean, median, mode, or other imputation techniques.
 - [x] Drop any rows or columns that contain missing or corrupted data.
 - [x] Predict the missing values using a separate machine learning model.
 - [x] Using machine learning algorithms that are robust to missing values.

---
### 14/4/22
***The mysterious case of the strange loss***

Jena has finally finished building a neural network!It took her some time to deal with the dataset, but she is finally ready to train the model.Fifteen minutes later, Jena notices that her training loss is not decreasing as expected; it stays much higher than she hoped for.Jena got back to the drawing board to investigate what could be happening.After a couple of hours, Jena has come up with a few potential reasons that could explain the problem.

Which of the following could be causing the loss to behave this way?

- [x] The regularization that Jena is using is too aggressive.
- [x] Jena is using a learning rate that's too low.
- [x] The neural network is getting stuck at local minima.
- [ ] Jena is using a learning rate that's too high.
---
### 15/4/22
***Looking behind François's Tweet***

Recently, François Chollet mentioned that you should never try to use a learning-rate schedule from an old dataset to train a new one. Imagine a scenario where you create a deep learning classification model to train on images from a security camera. During the exploration phase, you set up a specific training schedule that works well for your problem and gives you good performance.

When training a new version of the model — even when using the same architecture — with images from a different security camera, François' advice is to avoid using the same training schedule.

Which of the following could be François' thinking behind his advice?

 - [ ] The learning-rate schedule depends on the number of samples in the dataset, so the exact schedule won't work with a different size dataset.
 - [ ] The learning-rate schedule should change whenever we have a dataset from a different target distribution. This won't be the case if the target distribution is the same.
 - [x] A new dataset changes the tradeoff between optimization and regularization. The learning-rate schedule is dataset-specific.
- [ ] Learning-rate schedules are specific to the optimization mechanisms used by the model. A new dataset usually requires that we change the optimization process, which will invalidate the learning-rate schedule as well.
---
### 16/4/22
***Patricia is building a logistic classifier***

Patricia has been working on a logistic classifier for a new project.

She knows that the key to getting successful predictions depends on the error function she decides to use. She wants this function to have the following characteristics:

**The function should return a small number if the sample is correctly classified.
    The function should return a large number if the sample is incorrectly classified.
    The error for a set of samples should be the sum or average of the errors for all the samples.**

Patricia has several choices but would like to hear your opinion.
Which of the following would be the best error function for a logistic classifier?
    
- [ ] Absolute error: a function that returns the absolute value of the difference between the prediction and the label.
- [ ] Square error: a function that returns the square of the difference between the prediction and the label.
- [x] Log loss: a function that returns the negative logarithm of the product of probabilities.
- [ ] Mean percentage: a function that returns the average error of the differences between predicted and actual values.
---
### 17/4/22
***The birthday paradox***

After a lot of begging, Lucia convinced Anna to go to a party together. Anna likes to spend most of her time with math books. The change of scenery was good, so she showed up.After an hour or so, Lucia noticed that Anna was not having fun, so she decided to cheer her up with an interesting problem."Anna, there are 23 people at this party right now. What is the probability that two of them share the same birthday?"

What is the correct answer to Lucia's question?

- [ ] There's about a 1% probability of two people sharing the same birthday.
- [ ] There's about a 6% probability of two people sharing the same birthday.
- [ ] There's about a 17% probability of two people sharing the same birthday.
- [x] There's about a 50% probability of two people sharing the same birthday.
---    
### 18/4/22
***Keeping pedestrians safe***

A team has been working on a self-driving car model to detect pedestrians crossing the street on images captured from the car cameras.Their model will help cars navigate busy areas while keeping everyone around safe. It's a critical and delicate piece to get to full autonomy.Despite initial promising results, they haven't settled on the best way to evaluate the model's performance.

A discussion starts with some initial ideas. Which of the following evaluation metrics would be the best for this problem?

 - [ ] The team should use the recall of the model, as defined by the percentage of detected pedestrians with respect to every image containing a pedestrian.
 - [ ] The team should use the precision of the model, as defined by the percentage of legitimate detected pedestrians with respect to every detected pedestrian.
 - [x] The team should use the Fβ-Score of the model with a high value of β.
 - [ ] The team should use the Fβ-Score of the model with a low value of β.
---
### 19/04/22
***Thinking about softmax***

Remember the last time you built a machine learning multi-class classification model?

You probably used a softmax activation on the output layer of your network. It's a widespread practice, so there's a good chance you've done it. It's usually fun to think about why we do things the way we do them, so let's get into it.Which of the following statements is true about the softmax activation function when used in the output layer of a neural network?


- [ ] The softmax function turns the network's input into a vector of probabilities that sum to 1.
- [x] The softmax function is a probabilistic or "smooth" version of the function that returns the index of the vector's largest value.
- [ ] The softmax function turns a vector of real values into a sorted vector of probabilities that sum to 1.
- [ ] The softmax function is a probabilistic or "smooth" version of the function that returns the vector's maximum value.
---
### 20/04/22
***Alice can't remember how One-Hot Encoding works***

When building a machine learning model, much of the work happens well before starting training.

Alice knows that she needs to prepare the data before it's ready. She has been looking into encoding some of the features on her dataset. One-Hot Encoding seems like a good candidate.It's been quite a while since Alice used One-Hot Encoding, and she can use some help.

Which of the following statements explains how One-Hot Encoding works?

- [ ] One-Hot Encoding encodes a numerical feature into its categorical representation.
- [x] One-Hot Encoding creates additional features based on the number of unique values in a categorical feature.
- [ ] One-Hot Encoding encodes a string-encoded feature into its numerical representation.
- [ ] One-Hot Encoding encodes a string-encoded feature into its categorical representation.
---
### 21/04/22
***The anatomy of ReLU***

The Rectified Linear Activation Function, or ReLU, returns its input if it's positive or a zero otherwise.

In other words: ReLU turns any negative values into zero and leaves everything else unmodified. ReLU has become a popular activation function when training neural networks. Since it's a linear function and computationally straightforward to implement, models become easier to optimize and achieve better performance.There's something very interesting about combining Gradient Descent with ReLU, and to get there, we have to think a bit about the mathematical properties of ReLU.

Which of the following is true about the Rectified Linear Activation Function (ReLU)?

- [ ] The function is neither continuous nor differentiable.
- [ ] The function is differentiable but not continuous.
- [ ] The function is both continuous and differentiable.
- [x] The function is continuous but not differentiable.
---
### 22/04/22
***Australian birds***

Marc was excited about the performance of his model.

He's been working on an app to classify photos of birds, and his model is performing very well on all metrics. Marc knows what he is doing and followed all the best practices: he split training and test data, used the proper evaluations metrics, balanced his dataset, and reviewed examples regularly to ensure there were no labeling errors. Finally, Marc launched his app.Positive feedback started rolling in except from one place: users in Australia complained the performance was awful. Marc was baffled.

**What is the most likely reason for the problem?**

- [ ] Marc didn't train the model long enough to capture all the necessary details of different bird species.
- [ ] Marc's model is too simple, and it couldn't learn the entire dataset of birds, leaving out those from Australia.
- [x] Marc's model suffers from sampling bias. He probably didn't include enough examples of Australian birds.
- [ ] Marc's model is suffering from data or concept drift.
---
### 23/04/22
***Breaking a function down into pieces***

We are trying to predict the price of a car.

Our company has a website where users sell and buy used cars. Deciding how much we should charge for a used car is complicated and error-prone.
We want to build an automatic price recommendation system using supervised learning. The Manufacturer's Suggested Retail Price (MSRP) of the car is our target variable. Since its distribution has a very long tail, we apply a log transformation before training the model.

**If our model for a single observation is y = f(x), what are x and y for this project?**

- [x] x is a feature vector containing the variables that describe the car, and y is the logarithm of the price of the car.
- [ ] x is a feature vector containing the variables that describe the car, and y is the price of the car.
- [ ] y is a feature vector containing the variables that describe the car, and x is the logarithm of the price of the car.
- [ ] y is a feature vector containing the variables that describe the car, and x is the price of the car.
---
### 24/04/22
***Mia and the feedback loop***

Mia was crushing her thesis!

She was about to release a new neural network architecture that promised to raise the bar on image classification problems. Mia did not start from scratch. She modified an existing model but added a key ingredient: feedback loops. A feedback loop is when connections between units form a directed cycle, thus creating loops in the network. This gave Mia's network the ability to save information in the hidden layers. Mia did a lot of research before deciding in favor of this architecture. She knew the advantages of her decision.

**Which was the architecture that Mia studied to learn about feedback loops?**

- [x] Recurrent Neural Networks
- [ ] Convolutional Neural Network
- [ ] Multilayer Perceptron
- [ ] Radial Basis Function Network
---
### 25/04/22
***Harper and the small gradients***

Harper's team is struggling with the deep neural network they have been building.

Unfortunately, during backpropagation, the gradient values of their network decrease dramatically as the process gets closer to the initial layers, preventing them from learning at the same pace as the last set of layers. Harper knows their model suffers from the vanishing gradient problem. She decides to research every possible option to improve their model.

**Which of the following techniques will make Harper's model more robust to the vanishing gradient problem?**

- [x] Harper should try ReLU as the activation function since it's well-known for mitigating the vanishing gradient problem.
- [x] Harper should modify the model architecture to introduce Batch Normalization.
- [x] Harper should make sure they are initializing the weights properly. For example, using He initialization should help with the vanishing gradient problem.
- [ ] Harper should increase the learning rate to avoid getting stuck in local minima and thus reduce the chance of suffering vanishing gradients.
---
### 26/04/22
***Exploring data before anything else***

An essential step in any machine learning project is the Exploratory Data Analysis process.

Before we can train a model, we need to understand our data. As the name suggests, Exploratory Data Analysis allows us to explore the data to discover potential problems or patterns that we can use.

**Which of the following are some of the steps we take during this process?**

- [x] Learn the distribution of the target variable.
- [x] Understand the features in the dataset and the distribution of their values.
- [ ] Evaluate the performance of our models on this data.
- [x] Assess the data quality, including missing or corrupt values.
---
### 27/04/22
***Susan needs to make a decision***

The deadline is approaching, and Susan still hasn't decided which version of her classification model to deploy to production.

She experimented with different hyperparameters, and now she has two models that perform pretty well. Her problem is that none of these models is better than the other in every situation. One model has a higher recall but worse precision than the other. Susan can improve the precision by playing with different thresholds, but now the recall decreases.

**How can Susan decide which is the best overall model?**


- [ ] Susan should tune the thresholds until both have a recall of 95% and choose the one with higher precision.
- [ ] Susan should tune the thresholds until both have a precision of 95% and choose the one with a higher recall.
- [x] Susan should compute the area under the curve for both models and choose the one with the higher value.
- [ ] There's no objective way to decide which model is best. Susan should pick either one of them.
---
### 28/04/22
***Linear regression by hand***

The best way to learn something new is to rip the band-aid and tackle a problem from scratch.

Imagine you get a dataset with thousands of samples of houses sold in the U.S. over the last five years. We know the value of a few different features of each home and the price it was sold for. The goal is to build a simple model capable of predicting the price of a new house given those features. A linear regression model seems like an excellent place to start. But you are not writing any code yet. You want to do this manually, starting with a matrix X containing the value of the features and a vector w containing the weights.

The next step is to multiply X and w, but you aren't sure about the result of this operation.

**Which of the following better describes the result of multiplying X and w?**

- [ ] The result will be a vector y containing the actual price of each house as provided in the dataset.
- [x] The result will be a vector y containing the predicted price of each house.
- [ ] The result will be a matrix y containing the actual price of each house and the features from the matrix X.
- [ ] The result will be a matrix y containing the predicted price of each house and the features from the matrix X.
---
### 29/04/22
***20,000 sunny and cloudy samples***

Today is your very first day.

You get access to weather data. Twenty thousand samples with the weather of sunny and cloudy days. You want to build a model to predict whether a future day will be sunny or cloudy.

You already know this is a binary classification problem, and now it's time to pick a model.
**Which of the following techniques can you use to build a binary classification model?**

- [x] Logistic Regression
- [x] k-Nearest Neighbors
- [x] Neural Networks
- [x] Decision Trees 
---
### 30/4/22
***The true meaning of hyperparameter tuning***

Marlene is trying to build an audience. Writing content seems easy, but taking a complex subject and boiling it down to its essence is not an obvious task. Marlene wants to start from the basics and write as much as possible about the fundamentals of machine learning. She picked her first topic: hyperparameter tuning.

**If you were trying to summarize the core idea of hyperparameter tuning, which one of the following sentences would you use?**

- [ ] Hyperparameter tuning is about choosing the set of optimal features from the data to train a model.
- [ ] Hyperparameter tuning is about choosing the set of optimal samples from the data to train a model.
- [x] Hyperparameter tuning is about choosing the optimal parameters for a learning algorithm to train a model.
- [ ] Hyperparameter tuning is about choosing the set of hypotheses that better fit the goal of the model.
---
