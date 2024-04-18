## Modeling
- How can we visualize our datasets to help us find answers to the question we were asked
- We build data models and use training sets and testing sets
- The success of the modeling largely depends of understanding of the question, the analytical and methods approach used
- For building the data model, we need to compile, prepare and model

### Case Study
- Using decision tree to classify readmission of a patient
- In the example while the Overall accuracy represents highest accuracy, it only represents 45% of the Yes answers
- To tune the model, we need to make adjustment to the Relative Cost Y:N which is the ration of Yes to No answers
- Type 1 Eror aka False Positive
- Type 2 Error aka False Negative
- Sensitivity is the Accuracy in respect to Yes answers
- Specificity is the Accuracy in respect to No answers

## Evaluation
- Have we indeed answer the question using the designed model or we need to calibrate the model further
- Involves feedback loop to determine relevance and fitness of the model
- Evaluations run during development before its deployed
- Phases of model evaluation
  - Diagnostic measures. Test and verifies that the model work as intended.
  - Statistical significance. Test and verifies that data is properly processed and interpreted in the model.
 
  ### Case Study
  - Which model is best if we are to tune the Relative Cost parameter
  - We can use Receiver Operating Characteristics (ROC) Curver to evaluate the models
  - Model that is farthest than the central line is best, aka maximum separation
 
  (![image](https://i0.wp.com/sefiks.com/wp-content/uploads/2020/12/roc-curve-original.png?ssl=1))

  ### Confusion Matrix
![image](https://github.com/rdagumampan/datascience-methodology-and-practice/assets/5895952/d592433c-b206-4f9a-a597-39aef79380ad)

  
## References
https://www.youtube.com/watch?v=prWyZhcktn4
