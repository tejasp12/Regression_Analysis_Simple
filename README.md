# Simple Linear Regression Analysis
The repository that explains all the basic aspects behind Simple Linear Regression Analysis.

Before dive into the implementation of Simple Linear Regression,let's first learn the theory behind **Regression**.
### What is Regression Analysis?
  **Regression Analysis** is the process of predicting a **continous value**.It is known as one of the methods of prediction and the fundamentals of Regression Analysis is frequently used in Supervised Machine Learning so it is very important to learn Regression Analysis.
### When to use Regression Analysis?
  The Regression Analysis is useful in the scenarios when their is a **Causal Relationship** between 2 or more variables. Now, there is always a common confusion between terms **Correlation** and **Causation**. So,let's try to understand these terms first.
   * __Correlation__: It is a **Statistical Measure(expressed in number format)** that describes the __strength and direction__ of a relationship between 2 or more variables.Say for example if we consider two variables "number of hours worked" and "amount of income earned" we can see that there is a relationship between the two in the scenario that if the increase in "number of hours of work" is **associated**(not effect) with an "increase in income" earned. Consider the second example,there is an association between "product price" and "purchasing power"we can say that as the price of products increases a person's ability to buy these products decreases(if we assure the constant income).
      >Howerver,we can't say this firmly that **correlation does not imply causation.** This simple means that a correlation between variables, however, does not automatically   mean that the change in one variable is the cause of the change in the values of the other variable.And that's why the concept **Causation** comes into picture.
   * __Causation__:It shows that one event is the result of occourence of the another event.In other words,there is a causal relationship between 2 variables.We can say this scenario as **Cause and Effect** scenario.Say for an example,chewing tobaco causes an increase in the risk of developing Mouth Cancer.
Now,let's back to our topic "Causal Relationship" and see some examples of it in different domains:
1. __Healthcare:__
    * Is there a relationship between Sodium and High blood pressure?
    * Is there a relationship between chewing tobaco and Mouth Cancer?
    * Is there a relationship between usage of Cosmatics and Skin Cancer?
    * Is there a relationship between eating red meat and Stomoch cancer?
2. __Corporate:__
     * Did a company's marketing campaign increase their product sales?
     * Did integration of automation reduce production cost?
     * Did work from home increase in productivity and reduce in operational cost?
These and other questions are exploring whether a correlation exists between the two variables, and if there is a correlation then this may guide further research into investigating whether one action causes the other. 
#### The structure of Simple Regression Analysis:
   In Simple Regression Analysis there is mostly consist of **One Independent Variable** and **Dependent Variable**. The dependent variable should be **continous** and can't be binary. **Linearity** of regression is basically depend on the nature of relationship between dependent and independent variables. Following are some of the cases where we can use Regression Analysis:
   * Sales forecasting
   * Satisfaction analysis
   * Price estimation
   * Employment income
#### Difference between Correlation and Regression:
Correlation |  Regression
------------|------------
It measures the degree or strength of relationship between 2 variables.|It demonstrate how one variable is the cause or how one variable affects on the other.
It represent using a single point on the graph.|It is the best fitting line that goes through all data points. 
It can represent in two way.|It is only one way.
#### Process of implementation of Simple Linear Regression:
   1. Get the sample data.
      * **Dependent variable:** y(called target)
      * **Independent variable/s :** X1(X2,X3,...Xn in Multiple Linear Regression)Called Feature,Predictor
   2. Design a model that works for that sample data.
   3. Make prediction for the whole population.
   4. Evaluate the Model.
