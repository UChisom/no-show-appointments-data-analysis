## Title 
## No-show Appointments Data Analysis

### Purpose: To give insight to the probable cause of patients missing their medical appointments in Brazil for a dataset collected over four month in 2016.

### Dataset Description
The No-show appointment data set is a collection of a 100, 000 medical appointments in Brazil. It aims to determine whether or not patients do show up for their medical appointments and suggest factors that may affect the patient's response. 

The factors that may be used to determine why patients attend or miss their medical appointments were captured as columns of the data frames. The dataset has 1 table and 14 columns. The columns are as listed below:

> #### Columns and descriptions:
- PatientId - Identification of a patient
- AppointmentID - Identification of each appointment
- Gender - Male or Female
- ScheduledDay - The day of the actual appointment, when they have to visit the doctor
- AppointmentDay - The day the appointment was registered
- Age - How old is the patient.
- Neighbourhood - Where the appointment takes place
- Scholarship - True of False
- Hipertension - True of False 
- Diabetes - True of False
- Alcoholism - True of False
- Handcap - True of False
- SMS_received - True of False
- No-show - True of False

> Note that a value of `Yes` in the `No-show` column indicates that the patient missed the appointment
- The **No_show** column says **No** when the patients made the appointment and **Yes** when they missed it

### Requirements
The following libraries and their installation syntax were used in this analysis:

```
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

%matplotlib inline
```
The `%matplotlib inline` magic command was to enable the notbook display visualisations after the respective code cells inline

### Questions for Analysis
By what Factors can we closely predict that a patient would attend their medical appointment?

Do older people have more no_show appointments?

Was scholarship a reason why patients missed their appointments?

Do the gender of patients account for no-show appointments?

### Key Insights
From the analysis performed on the different independent featured of the **no-show** dataset to find out factor ifluencing no-show appointments, it can be observed that the **age** of the patients had an impact on whether they made their appointments or not.
>Although this is not inferencial nor absolutely conclusive, it is tentative to suggest that the age differences among the patients was partly responsible for how they attended medical appointmnets.

>Other features analysed were the scholarship and gender. Despite younger patients having more scholarships than the older ones, they still had a poorer attendance rate in camparison. Further analysis and information about factors that may influence how scholarship holders visit medical centres would be needed for a less speculative conclusion.

>In addition, the patients gender proved to have a little influence on how they attended medicap appointments. The proportion of female and male no-show appointment were really close, showing that their gender didnt really influence attendance.

>Finally, an analysis on the days of week that recorded more attedance than others showed a staggerring fall on **Saturdays**. Overall, there seemed to be an increase in the amount of no-show appointments toward the end of the week than during the start. This is indicative that there may be other factors reponsible for patients not madking their appointment during the weekend which my analysis did not cover.

>A limitation to this analyisis is that o machine learning was used to make conclusions, thus making every conclusion tentative, also, more analysis (and/ or details) may be need to understand why younger patients have more no shwo appointments despite having scholarships.

### References
The data set was gotten from kaggle through this link: (Kaggle page)[https://www.kaggle.com/joniarroba/noshowappointments]
