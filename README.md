## Title: No-show Appointments Data Analysis

### Purpose: To give insight to the probable cause of patients missing their medical appointments in Brazil over four month's data in 2016.

### Dataset Description
The No-show appointment data set is a collection of a 100, 000 medical appointments in Brazil. It aims to determine whether or not patients do show up for their medical appointments and suggest factors that may affect the patient's response. The factors that may be used to determine why patients attend or miss their medical appointments were captured as columns of the data frames. In this data set, we have only 1 table, with 14 columns. The columns are as listed below:

> Columns descriptions:
PatientId - Identification of a patient
AppointmentID - Identification of each appointment
Gender - Male or Female
ScheduledDay - The day of the actual appointment, when they have to visit the doctor
AppointmentDay - The day the appointment was registered
Age - How old is the patient.
Neighbourhood - Where the appointment takes place
Scholarship - True of False
Hipertension - True of False
Diabetes - True of False
Alcoholism - True of False
Handcap - True of False
SMS_received - True of False
No-show - True of False

### Questions for Analysis
By what Factors can we closely predict that a patient would attend their medical appointment?

Do older people have more no_show appointments?

Was scholarship a reason why patients missed their appointments?

Do the gender of patients account for no-show appointments?

### Note: 
- The **no_show** column says **no** when the patient made the appointment and **yes** when they missed it

### References
The data set was gottenfrom kaggle through this link: (Kaggle page)[https://www.kaggle.com/joniarroba/noshowappointments]