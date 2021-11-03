# MOORES_LAW-ANN-PROJECT

**PROBLEM STATEMENT** : To Prove Moore's Law

What is **Moore's Law ?**
It says that the number of transistors per square inch on an integrated circuit board foubles approx every 2 years.

In model.compile(), I have realized after doing hyperparameter tuning that the default optimizer 'adam' doesnt perform that well.
Therefore, I will be using my most basic optimizer 'Stochastic Gradient Descent'.SGD( learning rate, momentum)

Another interesting thing which I have observed wrt this dataset is that the Initial learning rate performs well at the begining, however, it becomes too large by the end and because of this, the cost function jumped up and down and never converged. So to tackle this, reduced the learning rate gradually depending upon the the number of epochs. This concept is called as "Learning Rate Scheduling".

