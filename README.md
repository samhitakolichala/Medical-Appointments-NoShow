**Medical Appointments NoShow**

This project aims to predict whether a patient will show up for their scheduled medical appointment or not. The dataset used in this project is provided by Kaggle and contains information on over 110527 medical appointments in Brazil, including the patient's age, gender, medical history, and more.

**Getting Started**

To run this project, you will need Python and the following packages installed:

pandas
numpy
matplotlib
seaborn
scikit-learn

**Dataset Description**

**Medical Appointment No Shows**

The dataset includes the following features: Medical Appointment No Shows

PatientId: Identification of a patient
AppointmentID: Identification of each appointment
Gender: Male or Female
ScheduledDay: The day someone called or registered the appointment
AppointmentDay: The day of the actual appointment
Age: How old is the patient
Neighbourhood: Where the appointment takes place
Scholarship: True or False. Whether or not the patient is enrolled in Brasilian welfare program Bolsa Família
Hipertension: True or False
Diabetes: True or False
Alcoholism: True or False
Handcap: True or False
SMS_received: 1 or more messages sent to the patient
No-show: Yes or No

**Model**

The model used in this project is a logistic regression classifier,random forest classifier ,extra tree classifier,gradient boost classifier,XGB boost classifier. The model is trained on the training set and evaluated on the test set. The evaluation metrics used in this project are accuracy, precision, recall, and F1 score.
Amonst all these models Gradient Boost classifier performed well.

**Results**

Amongst all these models Gradient Boost classifier performed well with 68%  training accuracy , 67 is testing accuracy , with precision of 75 means that out of all the patients that the model predicted as no-shows, 75% of them actually did not show up for their appointments, a recall of 55 means that the model correctly identified 55% of all the patients who did not show up for their appointments , an F1 score of 63 means that the model has achieved a reasonable balance between precision and recall.

**Conclusion**
In conclusion, this project demonstrated that it is possible to predict whether a patient will show up for their scheduled medical appointment or not with reasonable accuracy using gradient boost regression. The model can be used by healthcare providers to identify patients who are at risk of not showing up for their appointments and take appropriate measures to ensure that they attend their appointments.

<img width="364" alt="image" src="https://user-images.githubusercontent.com/119112861/234960377-b26d62b0-f0a4-4bf8-b684-fcef22819006.png">


**Quick Glance**

<img width="348" alt="image" src="https://user-images.githubusercontent.com/119112861/234960158-db1863fa-dd2b-4f00-87ee-49d611a02abc.png">
