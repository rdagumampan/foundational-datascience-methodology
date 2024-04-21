## Modeling
- How can we visualize our datasets to help us find answers to the question we were asked
- We build data models and use training sets and testing sets to find answers to business question
- The success of the modeling largely depends of understanding of the problem or business question, the analytical and methods approach used
- For building the data model, we need to compile, prepare and model
- Data scientists may train different algorithms on training set and fine tune variables that best support the answer to the question
- Model can use statistical process or machine learning
- The result of modeling can be Prescriptive (Do something) or Predictive (This is likely to happen)

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
    - We can use Decision Tree to find areas for improvement
  - Statistical significance
    - Test and verifies that data is properly processed and interpreted in the model.
 
### Case Study
- Which model is best if we are to tune the Relative Cost parameter
- We can use Receiver Operating Characteristics (ROC) Curver to evaluate the binary classification models
- Model that is farthest than the central line is best, aka maximum separation
 
(![image](https://i0.wp.com/sefiks.com/wp-content/uploads/2020/12/roc-curve-original.png?ssl=1))

### Confusion Matrix
![image](https://github.com/rdagumampan/datascience-methodology-and-practice/assets/5895952/48d65101-9ca9-4b14-958c-bc5989e92eb7)
  
## References
https://www.youtube.com/watch?v=prWyZhcktn4
