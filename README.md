# Project: No-show appointments

## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
<li><a href="#conclusions">Conclusions</a></li>
</ul>

<a id='intro'></a>
## Introduction

### Dataset Description 
 
This dataset collects information from 100k medical appointments in Brazil and is focussed on the question of whether or not patients show up for their appointment. This No-show dataset has 14 columns with the description below:
- *'PatientId'* - Identification of a patient
- *'AppointmentID'* - Identifies each appointment
- *'Gender'* - Male or Female
- *'ScheduledDay'* - The actual day of the appointment
- *'AppointmentDay'* - The day someone registered the appointment
- *'Age'* - How old the patient is
- *'Neighbourhood'* - Where the appointment takes place
- *'Scholarship'* - True or False (whether the patient has Government sponsirship or no)
- *'Hipertension'* - True or False (whether the patient has the Hipertension or no)
- *'Diabetes'* - True or False (whether the patient is diabetic or no)
- *'Alcoholism'* - True of False(whether the patient is an alcoholic or no)
- *'Handcap'* - True of False(whether the patient is an Hancapped or no)
- *'SMS_recieved'* - 1 or more messages sent to the patient
- *'No-show'* - True or False (whether the patient showed up for the appointment or no)


### Question(s) for Analysis

#### 1.What is the relationship between Gender and No-show?
#### 2.Is SMS_received likely to have an influence on No-show?
 
 
 <a id='conclusions'></a>
## Conclusions

 ### Results:
 Our data suggests that: 
  1. There is a higher proportion of females than males who showed up for the appointment
  2. There is a higher number of people that showed up and did not receive an sms when compared to patients who received an sms and did show up.
  
### Limitations:
There are a number of limitations with our data: 
 1. Most of our variables are categorical which does not allow for a high level of statistical method that can be used to provide correlations
 2. We do not have a lot of details for certain factors to draw conclusions . For instance, the sms_received, the data shows that no_showers are likely to recieve an SMS. This may seem counter intutive, but we do not have information on the conditions of when the sms is sent. For example, they may target no_showers with SMS, or they may send the SMS once the patient has not checked in 30 minutes prior to thier appointment. 

## Acknoledgement

A very special appreciation to ALX Africa scholarship program without which i would not have been able to participate in this program. In addition i'm very grateful to Udacity for their well packaged and sound curriculum. More power to your elbows. Finally, thanks to my parents, teachers,mentors,friends,colleagues and all who have helped me to be who i am today. God Bless!
