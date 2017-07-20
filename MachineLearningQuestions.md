# Machine Learning Questions



##### The following questions go over the basic knowledge of Machine Learning. They are from the end of Chapter 1 of Aurelien Geron's *Hands-On Machine Learning with Scikit-Learn & TensorFlow*. 



1. How would you define Machine Learning?

   *Machine learning is defined by programming machine to learn from data to solve a specific problem.*

2. Can you name four types of problems where it shines?

   *Machine learning is great for problems whose solution requires a great deal of work or a long list of rules, complex problems that are hard to get a solution of using a traditional method, fluctuating environments and getting insights about complex problems and large data.*

3. What is a labeled training set?

   *Labeled training set is a set of training data which has a solution to the problem or task (a.k.a. label)*.

4. What are the two most common supervised tasks?

   *Two most common supervised tasks are classification and regression.*

5. Can you name four common unsupervised tasks?

   *Four common unsupervised tasks inclused clustering, visualization, dimensionality reduction , and association rule learning.*

6. What type of Machine Learning algorithm would you use to allow a robot to walk in various unknown terrains?

   *The best Machine Learning algorithm to allow a robot to walk in unknown terrain is Reinforced Learning, where the robot can learn from response of the terrain to optimize itself.*

7. What type of algorithm would you use to segment your customers into multiple groups?

   *The best algorithm to segment customers into multiple groups is either supervised learning (if the groups have known labels) or unsupervised learning (if there are no group labels).*

8. Would you frame the problem of spam detection as a supervised learning problem or an unsupervised learning problem?

   *Spam detection is a supervised learning problem because the labels are known (spam or no spam).*

9. What is an online learning system?

   *Online learning system is a learning system in which the machine learns  as data is given in small streams continuously.*

10. What is out-of-core learning system?

    *Out-of-core learning system is a system that can handle data that cannot fit into your computer memory. It uses online learning system to feed data in small bits.*

11. What type of learning algorithm relies on a similarity measure to make predictions?

    *Learning algorithm that relies on a similarity measure to make predictions is instance-based algorithm.*

12. What is the difference between a model parameter and a learning algorithm's hyperparameter? 

    *Model parameter determines how a model will predict given a new instance; model usually has more than one parameter (i.e. slope of a linear model). Hyperparameter is a parameter for the learning algorithm, not of a model.*

13. What do model-based learning algorithms search for? What is the most common strategy they use to succeed? How do they make predictions?

    *Model based learning algorithm search for the optimal value of parameters in a model that will give the best results for the new instances. We often use a cost function or similar to determine what the parameter value has to be in order to minimize the function. The model makes prediction by using the value of the new instance and the parameters in its function.*

14. Can you name four of the main challenges in Machine Learning? 

    *Four main challenges in Machine Learning include overfitting the data (using a model too complicated), underfitting the data (using a simple model), lacking in data and nonrepresentative data.* 

15. If your model performs great on the training data but generalizes poorly to new instances, what is happening? Can you name three possible solutions?

    *If the model performs poorly to new instances, then it has overfit on the training data. To solve this, we can do any of the following three: get more data, implement a simpler model, or eliminate outliers or noise from the existing data set.*

16. What is a test set and why would you want to use it?

    *Test set is a set that you test your model (fit using training data) to see how it performs. Test set is necessary so that you can determine how good (or bad) your model performs.*

17. What is the purpose of a validation set?

    *Validation set is a set used to compare between different training models.*

18. What can go wrong if you tune hyperparameters using the test set?

    *If you tune hyperparameters using the test sets, then it may not perform well on the out-of-sample data because the model is tuned just for that specific set.* 

19. What is cross-validation and why would you prefer it to a validation set?

    *Cross-validation is a tool to compare models without needing a separate validation set. It is preferred over validation set because we can save from breaking of part of the training set to create a validation set, as having more data is valuable regardless.*