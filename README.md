# No-show Appointments Data Analysis
Generate insights into the probable cause of patients missing their medical appointments in Brazil from a dataset collected over four months in 2016.
## Description
- The No-show appointment data set is a collection of 100, 000 medical appointments in Brazil.
- It aims to determine whether or not patients do show up for their medical appointments and suggest factors that may affect the patient's response.
## Dataset
The features considered were captured as columns of the tables (data frames). There are 14 columns on the table in the dataset. The columns and descriptions are as listed below:
> #### Columns and descriptions:
- PatientId - Identification of a patient
- AppointmentID - Identification of each appointment
- Gender - Male or Female
- ScheduledDay - The day of the actual appointment, when they have to visit the doctor
- AppointmentDay - The day the appointment was registered
- Age - How old the patient is
- Neighbourhood - Where the appointment takes place
- Scholarship - True or False
- Hipertension - True or False
- Diabetes - True or False
- Alcoholism - True or False
- Handcap - True or False
- SMS_received - True or False
- No-show - True or False
> Note that a value of `Yes` in the `No-show` column indicates that the patient missed the appointment
- The **No_show** column says **No** when the patients made the appointment and **Yes** when they missed it
## Requirements
The following libraries and their installation syntax were used in this analysis:
```
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline
```
> The `%matplotlib inline` magic command was to enable the notebook display visualizations after the respective code cells inline
## Questions for Analysis
1. By what Factors can we closely predict that a patient would attend their medical appointment?
2. Do older people have more no_show appointments?
3. Was scholarship a reason why patients missed their appointments?
4. Do the gender of patients account for no-show appointments?

## Key Insights
The analysis revealed that the **age** of the patients had an impact on whether they made their appointments or not.

> Younger patients had more scholarships than the older ones, but still had a poorer attendance rate in comparison. Further analysis and information about factors that may influence how scholarship holders visit medical centers would be needed for a less speculative conclusion.

> Patient's gender had little influence on how they attended medical appointments. The proportion of female and male no-show appointments was really close, showing that their gender didn't really influence attendance.

> There was a decline in attendance rates toward the weekends and **Saturdays** had the least of all days, while there wasn't any data for sundays in the dataset.

> A limitation to this analysis is that no machine learning tool was used to confirm conclusions, thus making every conclusion tentative. Also, more analysis (and/ or details) may be needed to understand why younger patients have more no-show appointments despite having scholarships.

## References
The data set was obtained from Kaggle through this link: [Kaggle page](https://www.kaggle.com/joniarroba/noshowappointments).
