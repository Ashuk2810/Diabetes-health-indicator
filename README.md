# Diabetes-health-indicator
Our project is focused on developing a diabetic health indicator and early warning system. The aim is to improve patient outcomes and reduce the risk of complications associated with diabetes.

# OVERVIEW:

Diabetes is a disease that occurs when your blood glucose is too high. Blood glucose is your 
main source of energy and comes from the food you eat. Over time, having too much glucose in 
your blood can cause health problems. Although diabetes has no cure, you can take steps to 
manage your diabetes and stay healthy.


# BUSINESS PROBLEM UNDERSTANDING

Diabetes is a chronic disease that affects millions of people worldwide and can lead to severe 
complications such as heart disease, kidney failure, and blindness.

Early detection and intervention are critical to manage diabetes and preventing these 
complications.

Healthcare providers can use data science and predictive modelling techniques to identify 
patients at risk of developing diabetes and provide targeted interventions to prevent the onset of 
the disease.

However, identifying at-risk patients could be a time consuming and challenging task, especially 
in a large patient population.

Therefore, there is a need for accurate and effective prediction models that can help healthcare 
providers to identify the patients at risk of developing diabetes and provide a timely intervention.

# BUSINESS OBJECTIVE

To develop a predictive model that can accurately identify the patients at risk of developing 
diabetes.

Use this model to provide timely intervention and reduce the risk of complications to the 
patients.

By making an early-stage identification of the disease, we can help the patients to reduce the
costs which they may incur due to the complications.

To check the factors affecting diabetes and provide a precaution to the patients so that they can 
avoid becoming a diabetes victim

# DATASET AND DOMAIN:

• Our objective is to work on previous data and build a model to predict whether a person 
will be diabetic or not based on his past medical records.

• Our dataset contains three files:

A. Diabetes _ 012 _ health _ indicators _ BRFSS2015.csv:

In which target variable is Diabetes_012 which has three values 0,1,2.
0: No Diabetes (Or Diabetes only during Pregnancy)
1: Prediabetes
2: Diabetes

B. Diabetes _ binary _ 5050split _ health _ indicators _ BRFSS2015.csv 

In which target variable is Diabetes_binary which has values 0,1
0: No Diabetes
1: Diabetes

C. Diabetes _ binary _ health _ indicators _ BRFSS2015.csv which has values 0,1

0: No Diabetes
1: Diabetes

Based on this information we decided to build a model considering only values 0,1 i.e., for 
Diabetes and No Diabetes, we are not going to take the pregnancy into account, Therefore, we 
will work on two Dataset i.e., B and C for further analysis. 

We are going to name them df1 and df2.

df1 has 70692 rows and 22 columns.

df2 has 253680 rows and 22 columns.

We are going to combine these two and work on that.

df = df1+df2


# CONCLUSION OF THE PROJECT:

Diabetes is a slow killer with no known curable treatments. However, its complications can be 
reduced through proper awareness and timely treatment. So, if we use random forest by knowing 
the essential information of the patient, we can start its treatment much early.

Our analysis revealed that random forest model consistently outperformed other alternative 
models in terms of accuracy, F1 score, recall and precision. This indicates that random forest 
algorithm is well-suited for early detection of diabetes based on the available dataset.

Upon evaluation of our project with the random forest model in the test data, it is showing an 
accuracy of 93% indicating a high level of accuracy in identifying individuals with diabetes at an 
early stage. This could potentially aid in timely interventions and improve patient outcomes.
However, it is important to note that our model’s performance might vary when applied to a 
different dataset or population. Further validation and refinement of the model on external 
datasets is recommended to ensure its reliability.

Overall, this project underscores the effectiveness of the random forest method in the early 
detection of diabetes. This project has the potential to assist health care professionals in 
identifying high risk individuals, enabling early detection and improved patient care
