# Fitting Neural Net on Cleveland Heart Disease Dataset
## Dataset Factors: 
<pre>
The dataset consists of 303 individuals data. There are 14 columns in the dataset, which are described below. <br/>
1 . Age: displays the age of the individual.  <br/>
2.  Sex: displays the gender of the individual using the following format :  <br/>
     1 = male  <br/>
     0 = female  <br/>
3. Chest-pain type: displays the type of chest-pain experienced by the individual using the following format :  <br/>
   1 = typical angina  <br/>
   2 = atypical angina  <br/>
   3 = non — anginal pain  <br/>
   4 = asymptotic  <br/>
4. Resting Blood Pressure: displays the resting blood pressure value of an individual in mmHg (unit) <br/>
5. Serum Cholestrol: displays the serum cholesterol in mg/dl (unit)  <br/>
6. Fasting Blood Sugar: compares the fasting blood sugar value of an individual with 120mg/dl.  <br/>
   If fasting blood sugar > 120mg/dl then : 1 (true)  <br/>
   else : 0 (false)  <br/>
7. Resting ECG : displays resting electrocardiographic results  <br/>
   0 = normal  <br/>
   1 = having ST-T wave abnormality  <br/>
   2 = left ventricular hyperthrophy  <br/>
8. Max heart rate achieved : displays the max heart rate achieved by an individual.  <br/>
9. Exercise induced angina :  <br/>
   1 = yes  <br/>
   0 = no  <br/>
10. ST depression induced by exercise relative to rest: displays the value which is an integer or float.  <br/>
    Peak exercise ST segment :  <br/>
    1 = upsloping  <br/>
    2 = flat  <br/>
    3 = downsloping  <br/>
11. Number of major vessels (0–3) colored by flourosopy : displays the value as integer or float.  <br/>
    Thal : displays the thalassemia :  <br/>
    3 = normal  <br/>
    6 = fixed defect  <br/>
    7 = reversible defect  <br/>
14. Diagnosis of heart disease : Displays whether the individual is suffering from heart disease or not :  <br/>
    0 = absence  <br/>
    1, 2, 3, 4 = present.  <br/>
</pre>


## Libraries: 
-- ISLR <br/>
-- corrplot <br/>
-- MASS <br/>
-- klaR <br/>
-- leaps <br/>
-- lattice <br/>
-- ggplot2 <br/>
-- corrplot <br/>
-- car <br/>
-- caret <br/>
-- class <br/>
-- plotly <br/>
-- neuralnet <br/>
-- fastDummies <br/>

## Neural Net: 
A neural network is a network or circuit of neurons composed of artificial neurons or nodes. In R, we can use package neuralnet() for computing neural network.
Before giving the test data to the network, I converted all the variables into integer because neuralnet() does not work on categorical variables.

#### Hidden Layer 1: 
![nn1](https://user-images.githubusercontent.com/46763031/148012441-e3fb5d26-3c55-4c2b-94e7-5e16ca5fd399.png)

#### Hidden Layer 2: 

![nn2](https://user-images.githubusercontent.com/46763031/148012485-6e82684b-10b8-4b95-aff0-89bcf866af2c.png)

#### Hidden Layer 3:

![nn3](https://user-images.githubusercontent.com/46763031/148012513-26846a35-e5f5-4bd0-a4ae-0e912aec4345.png)

#### Hidden Layer 4:

![nn4](https://user-images.githubusercontent.com/46763031/148012530-524399d9-1515-4c66-8dff-16e0ec228f13.png)

#### Hidden Layer 5: 

![nn5](https://user-images.githubusercontent.com/46763031/148012559-c0462aba-bb28-4678-9d2d-db3445d32bb2.png)

## Result: 

Test Error : <br/>
Hidden Layer 1 : 40.6% <br/>
Hidden Layer 2 : 40.6% <br/>
Hidden Layer 3 : 23.7% <br/>
Hidden Layer 4 : 20.3% <br/>
Hidden Layer 5 : 23.7% <br/>






