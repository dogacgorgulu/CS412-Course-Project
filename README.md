# CS412-Course-Project


### Prompt matching with questions

#### Improvements:
* Cleaned questions[].
* Both cosine and jaccard similarities calculate to improve matching.

### Feature Engineering  

#### Improvements:
* Prompts marked as question (-1) or statement (+1).
* Keywords added to determine copy/paste prompts.
* Directive words searched since assingment is fragmented into questions.
* Uncertain answers from ChatGPT determined.

### Fitting a model, predicting & evaluation 

#### Improvements:

* Random Forest Regressor implemented.
* Feature importances plotted.
* 100, 1000 and 2000 random states used to calculate mean value of MSE and R2.
* K-fold cross-validation algorithm is implemented for further evaluations.

Initial Results
MSE Train: 8.279  
MSE TEST: 101.5512  
R2 Train: 0.9493  
R2 TEST: 0.0954  

Final Results  
Mean value of MSE Train: 16.088397199999996  
Mean value of MSE TEST: 15.795384533333332  
Mean value of R2 Train: 0.7470926415079063  
Mean value of R2 TEST: 0.6059878139438487  

