## Patient No Show Predictions


### Overview
Now more than ever it is imperitive that our hospitals and medical facilities are running more effecient than ever. To aid this we set out to predict the ammount of patients that will miss their appointment on a given day. In doing so we will be able to overbook our appointments by a certain percentage in order to not waste facility time and resources.

Goals:
  - Explore how features influence weather a person will or will not show up to their appointment. 
  - develop machine learning models that can help the hospital/medical facility to predict the ammount of patients that will no show their appointment on a given day.
  - Provide the hospital/medical facility with an accurate predicted percentage of patients who will not show up to their appointment that day so that they will be able to overbook a percentage of appointments without risk of having to many patients and not enough doctors.
  
### The Approach
  - Find and clean a dataset (https://www.kaggle.com/joniarroba/noshowappointments?select=KaggleV2-May-2016.csv)
  - Engineer  features to give model deeper insight
  - Perform Exploratory Data Analysis on the data and create visualizations.
  - Build and test multiple prediction models (KNN, Random Forest, XG Boost)
  - After expirimenting with different models XB Boost gave us the highest accuracy score so that is what we went with for our predictions.

### Conclusions
 - We found that patients who recieve an SMS Messages show up almost 15% less often than those who recieve no text. If this is an automated SMS sent when the patient makes their appointment that could show how it does not lead to an increased percentage of patients showing up.
 - The neighborhood of Jardim Da Penha has one of the worst no show rates of any other neighborhood in the dataset.
 - We predicted that Monday and Tuesday will have the highest ammount of no show patients at around 5%.
 - We also found that patients with ailments like diabetes or Hypertension tend to show up at a slighty higher rate for their appointments. This could be because they are in more of a routine, constantly speaking with doctors about their ongoing conditions.
 
 ![](https://github.com/mdetiberiis01/Photos/blob/master/diabetes1.png)![](https://github.com/mdetiberiis01/Photos/blob/master/hypertension1.png)

### Business Insight
- We should adjust the SMS message system to message patients reminding them about their appointment instead of messaging them about the appointment they just made. This should lead to an added number of patients showing up to their appointments.

![](https://github.com/mdetiberiis01/Photos/blob/master/SMS_recieved.png)
- We predict Monday will have 4.94% of the daily patients not show up to their appointment. Because of this we reccomend you overbook 2.5% of patients for Monday for standby appointments so they will see the doctor when a person misses their appointment.
- Similarly Tuesday we predict 5.01% of patients not showing up for their appointments so we suggest you book 2.5% more patients on standby appointments.

![](https://github.com/mdetiberiis01/Photos/blob/master/DOW_show.png)

## Future Work
 - In the future we would like to take a deeper look to understand what it is that makes patients from the neighborhood of Jardim Da Penha has one of the worst show up rates of any neighborhood in the data.
 - Similarly we would like to explore the reason that people on governmeant Scholarship show up to their appointments at a less frequent rate.
  - To do this we would like to gather some more socio-ecinomic data from the region to perform more data exploration.
  
