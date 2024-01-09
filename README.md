# No_show_appointmentss

Introduction-
Dataset Description-
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment.
A number of characteristics about the patient are included in each row:
-‘PatientId’   identify a unique number for each patient.
-‘AppointmentID’   indicates the id of the scheduled appointment reserved by the client.
-‘Gender’   the gender of the patient.
-‘ScheduledDay’   tells us on what day the patient set up their appointment.
-‘AppointmentDay’   the patient reservation appointment date .
-‘Age’   the patient age .
-‘Neighborhood’   indicates the location of the hospital.
-‘Scholarship’   indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
-‘Hipertension’   indicates whether or not the patient blood pressure is higher than normal.
-‘Alcoholism’   indicates whether or not the patient is continuing excessive or compulsive use of alcoholic drinks .
-‘Handcap’   indicates whether or not the patient having a physical or mental disability .
-‘SMS_received’   indicates whether or not the patient have received a sms .
-‘No-show’   indicates whether or not the patient have shown in his appointment (where "No" indicate that the patient has attended in his appointment and "Yes" indicate that he miss his appointment) .


*Question for Analysis-
In this analysis our goal is to answer one main big question: What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?

*Data Wrangling-
General Properties-
Exploring our dataset and see our columns names and 4 rows as example of our data filled inside each columns.
In the next step we will find if there is any missing data and the type of data in each column.
the 'PatientId' is shown as a float and it need to be as intger
'ScheduledDay ' and 'AppointmentDay' are shown as object and to do a better investigation it need to be date data type (day , month , year).
Our next step is to find a description of your data such as the min , the max , the standard diviation , the mean , the distribution of the data set (the 25% , 50% , 75% of the data ).
*Data Cleaning-
In our next steps we will clean our data and make it comfortable for using in our investigation ,
Dealing with the "Age" values
change the type of column "PatientId"
Modify column "ScheduledDay
Modify column "AppointmentDay"
check on the duplicate values in "AppointmentID "
Drop 'AppointmentID' & 'PatientId' columns
Change the column name of "No-show"
Creat two columns showing the show and miss appointments

*Exploratory Data Analysis-
Which age have the highest probability to shows in their appointments ?
Which Gender have the highest probability to shows in their appointments ?
Which Neighbourhood have the highest probability to shows in their appointments ?
Which month have the highest propabilty attending patients ?
Which day have the highest propabilty attending patients ?
Which Neighbourhood associated with Age have the highest propabilty attending patients ?

*Conclusions-
For summarizing our investigation, we can answer our main question "What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment? " with the results we get so far:
the ages from 45 to 55 years old and the ages below 10 years old have the hight chance to attend their appoimnets more than the the other ages
the gender dont matter in this data set beacuse they have the same propabilty in attending and missing appoimnets
the Neighbourhoods "ILHA DO BOI" have hight chance that pateints will show up more than missing the appointments
"June" have the hight prediction that the patients will commit to their scheduled appointment
"Thursday" is the day which we will have a commitment from patients to more show up than missing appointments
"MARIA ORTIZ" Neighbourhoods have the highest prediction for the "1" years old patients that they will attend the appointments
so now we have many factors can hepl us to find out the better prediction for show up patients












