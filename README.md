# RMachineLearning

Hi this is my Github repo with my R markdown and compiled HTML file describing my analysis for the project. 
My goal was to predict the manner in which the participants in the dataset did the exercise.

I used the RandomForest prediction method because the lecture videos seems to suggest that it is the best; and it has worked out well.
In my model, I managed to accurately predict the 20 test exercises.

I initially did the mistake of including the first column of the training dataset, which is the index. 
I believe that the dataset is somehow sorted, or that I may have sorted it accidentally. I ended up with a really good prediction in the in-training test set, but did terribly at the actual test set, as the model predicted all the exercises to be A.
After I dropped the first column, all was well. :)

In case you cannot view the HTML file properly, I have it published on RPubs as well. 
Link: http://rpubs.com/yonglonglim/machinelearning
