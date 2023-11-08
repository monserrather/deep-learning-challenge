
For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

*Data Preprocessing*

1.  What variable(s) are the target(s) for your model?
- is_successful
2.  What variable(s) are the features for your model?
- All the columns other than is_successful
3.  What variable(s) should be removed from the input data because they are neither targets nor features?
- EIN and NAME


*Compiling, Training, and Evaluating the Model*

1.  How many neurons, layers, and activation functions did you select for your neural network model, and why?
- 8 hidden_nodes_layer1 and 5 hidden_nodes_layer2 picked randomly as initial set
2.  Were you able to achieve the target model performance?
- No
3.  What steps did you take in your attempts to increase model performance?
- Add hidden nodes and removed columns 

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

I was able to get a 73% of accuracy.
Perhaps if doing further data clean up or using other activation functiins we could achieve higher accuracy.

