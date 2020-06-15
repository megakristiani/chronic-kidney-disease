# Chronic Kidney Disease

Chronic Kidney Disease Predictor is a machine learning which can help you to diagnose your kidney condition based on the laboratory test result. But I do not recommend it as your self-diagnosis tool. If you think that you have kidney disease, it would be better to go to the hospital, check your medical condition, and get the right treatment by a licensed doctor and medical staff.

## Insight

The kidney is a metabolic organ that regulates your body fluids and blood. It excretes urine, toxins and produces erythropoietin (which can help you to get new erythrocytes who help your organs work, regenerate, and struggle at every condition). If your kidney has a problem, it could lead you to have kidney disease which can be worse and makes you potentially having kidney failure and other metabolic diseases.

#### What disease commonly appears with chronic kidney disease?

Based on the data, there is 5 kind of disease: hypertension (htn), diabetes Mellitus (dm), coronary artery disease (cad), pedal edema (pe), ane (anemia). We will see what kind of disease usually showed in CKD patience?

<p align="center">
  <img width="460" height="300" src="https://github.com/megakristiani/chronic-kidney-disease/blob/master/5disease.png">
</p>

As we can see, hypertension, diabetes mellitus, and pedal edema are commonly diagnosed with CKD patients. And more than 50% CKD patience getting anemia.

#### What symptoms are commonly detected?

Patients with hypertension are having blood pressure more than 50 points, high value of albumin, blood sugar random, blood urea, serum creatinin, and low hemoglobin. Half of them are having abnormal red blood cell which could be lead to anemia. 

Patients with diabetes mellitus are having a high value of albumin. More than 50% of them having abnormal pus cells, and 'not present' pus cell clumps. Almost 50% of them have abnormal red blood cells, and more than 50% of them infected by bacteria. They also have a high value of blood glucose random, blood urea, serum creatinine, sodium, but the low value of hemoglobin and packed cell volume. I assume that patients with diabetes mellitus are having high potential to get infected, and they also having poor erythropoiesis and leukopoiesis which can lead to a serious case.

Patients with pedal enema are having high albumin, more than 50% of them having abnormal pus cell, but 'not present' edema and has no bacteria. They also have high blood glucose random, blood urea, serum creatinine. They have a low value of hemoglobin, packed cell volume. Their appetite could affect their conditions. It means the fluid of edema does not always related to infection, most of them having the metabolic problem and poor erythropoiesis and leukopoiesis.

There's something interesting with patients with anemia: they have a normal red blood cell but have a low value of hemoglobin, and packed red cells. But their red blood cell count and white blood cell count are normal or high. As we can see, they could produce red blood cells, but not always with normal hemoglobin and form. I assume that chronic kidney disease could lead to every anemia type.

From this EDA, I assume that the metabolic system is truly related, one metabolic problem could lead to another metabolic and non-metabolic disease. Chronic kidney disease is one of the metabolic diseases. It could happen to everybody: in some case, it appears as an effect of lifestyle, but other it appears genetically as a side effect of the poor body system.

## Data Analysis

I applied the Logistic Regression method as a model that predicts the result (because this method is the simplest way to classify the data). First, I do the train-test-split using 0.3 test_size and 101 random_state. Then I apply the Logistic Regression with no special parameter. Then I classify the data and see the classifiaction report and confusion matrix from data train and data test. Here's the result:

<p align="center"> Data Test
  
  <img width="460" height="300" src="https://github.com/megakristiani/chronic-kidney-disease/blob/master/test.png">
</p>

<p align="center"> Data Train
  
  <img width="460" height="300" src="https://github.com/megakristiani/chronic-kidney-disease/blob/master/train.png">
</p>

