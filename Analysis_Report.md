# deep-learning-challenge
UO Data Visualization Bootcamp | Module 21: Deep Learning
#Report on the performance of the deep learning model you created for Alphabet Soup.#

##Overview of the analysis:##
The nonprofit foundation Alphabet Soup wanted a tool to help in selection of applicants for funding. The wanted the best return on the investment by funding the application with the greatest chance of success. I created a model using machine learning and neural networks to create a binary classifier. The model attempted to predict whether applicants will be successful if funded by Alphabet Soup.

##Results:##

###Data Preprocessing###

* What variable(s) are the target(s) for your model?
** All variables aside from 'IS_SUCCESSFUL' were used as targets within the model.

* What variable(s) are the features for your model?
** There was only one variable used as the defining feature, 'IS_SUCCESSFUL'. It would be helpful to note if there were more defining characterists of successful funding.

* What variable(s) should be removed from the input data because they are neither targets nor features?
** 'SPECIAL_CONSIDERATIONS' should be removed. I couldn't determine relevancy to the question at hand. Also removed anything that could not be calculated numerically. 

###Compiling, Training, and Evaluating the Model###

* How many neurons, layers, and activation functions did you select for your neural network model, and why?
* Were you able to achieve the target model performance?
* What steps did you take in your attempts to increase model performance?

##Summary:## 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

Overall, I am not confident we have successfully trained the model to have a high accuracy for the predictions. I recommend the working with Alphabet Soup to better define criteria for success and quantify those measurements. 