# Modeling-Response-Redux-DecisionTree-RandomForest-NeuralNetwork-Sklearn-Keras
Intuit Quickbooks Redux: Modeling response rate from an upselling campaign, evaluating the performance of Decision Tree, Random Forest, and Scikit-Learn/Keras Neural Networks against one another.

The purpose of this exercise is to gain experience modeling the response to an upsell campaign 
with Tree-based models and Neural Networks (or Deep Learning). You will use the same data 
(“intuit75k.pkl”) as in the previous assignment. 
 
I have created assignments on DataCamp for you to work through to help prepare with your 
group to complete this assignment successfully.   
 
Assignment guidelines: 
1.  As in the previous assignment, determine which of the 22,500 businesses in the test set (i.e., 
training == 0) to mail in wave-2 (i.e., generate a list of IDs). 10 points for this group 
assignment will be based on the profit (not ROME) achieved using this list of IDs. After you 
submit the list of IDs I will be able to determine the final outcome because all customers who 
did not respond in wave-1 were actually mailed in wave-2. You will not have access to this 
extra data set with information on response in wave-2. 
2.  Your selection of models should contain only Tree-based models (e.g., decision trees, 
random forests,  gradient boosting from sklearn) or Neural Networks (MLP in sklearn or DL 
models in Keras).  
3.  No case write-up is required but the code you used to estimate different models must be 
reproducible and must be pushed to GitLab before the start of class. Also, make sure the 
code is well commented and formatted (e.g., the Black code formatting for python). 
4.  You can run python code on the server in Jupyter notebooks and/or VS Code 
5.  I recommend you use Git and GitLab to move estimation code to and from the server. 
GitGadget is installed on the server and is available from Jupyter or the Addins Dropdown in 
Rstudio. You can also use the Git extension that is part of Jupyter. See the playlist below for 
more information 
https://www.youtube.com/playlist?list=PLNhtaetb48EfTV5_ZW5X7GQdBo2-l26PP  
6.  As before, assume each mail piece costs $1.41 and that the margin (or net revenue) from each 
responder, excluding the mailing cost, is $60. Make sure to correct the (predicted) purchase 
probabilities appropriately (i.e., the 50% drop-off as discussed in class). There is no need to 
calculate how to “project” your profits to the remaining customers in this assignments.  
7.  Each model used should return a predicted probability of response so you can use it to 
calculate a “mailto” variable 
