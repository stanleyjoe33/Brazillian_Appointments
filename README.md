# Brazillian Medical Appointments
## Introduction

### Dataset Description 

In this project patients' appointment schedule records would be analyzed  to show how certain recorded patient information like Age, Alcholic habits, Gender among a few others did or did not have significant relationships with  patients actually showing up for their appointments.  
This particular dataset consists of information of over 100,000 medical appointments in Brazil. The main focus of the dataset is whether the patients showed up for their appointments or not. The dataset consists of 14 columns:
### Questions for Analysis
Q1. Can gender or age be associated with showups or misses?

Q2. Did wait period (time between schedule and appointment day) affect showing up?

Q3.  what were the showup characteristics across the various days of the week?

Q4. Did patient physiological factors (hypertension, diabetes, if they were handicapped or alcoholics) affect showing up?

## Conclusions
1. From the analysis it can deduced that the most percentage of misses was in the teens age group(26.1%) followed by the adult age group(21.0%) which was closely followed by the children age group (20.50%) then the least showup percentage was in the senoir citizens category(15%).Also the showups and misses by gender; misses ==> male=19.96% female=20.31%,showups ==>male=80.03 female = 79.68%  were almost identical for both genders. So it can be said that showups to an extent can be associated with Age but is almost gender Neutral.

2. From the analysis it was discovered that there was a very significant decrease in mean show ups across our wait time distributions. Having a peak at the 0 days group(0.95) and the lowest mean was in the >31 days group(0.67). This is indicative of the fact that appointments that were scheduled to hold on the very days the schedules were made had very high showup ratio and the longer the interval between the schedule day and the appointment the lower the level of showup.

3. From the visual above it cann be inferred that the mean showups across the week days are fairly constant at 0.8 (+-0.05). therefore it can be concluded that there was no significant change in mean showups across weekdays.
However, cosidering the number of appointments scheduled on the various days it was discovered that Wednesday with an appointment count of 25,866 had the most schedules, closely followed by Tuesday(25,638) then Monday (22,713) which was then followed by Friday(19,019) and Thursday(17,246) then finally Saturday with just 39 appointments which presumably may be because these were emergency schedules or some sort of exception.

**Limitations**
1.There were different numbers of rows for each category in columns like the number of Females were greater than the number of males and also number of data for specific days were greater than others. These were handled by taking proportions and use of mean(in cases where the columns were 0 and 1 digit indicators).

2.There was no time given for the appointment day, which could have been a big plus to boosting our analysis by creating insights to what time of the day had more or less misses or showups.

3.There were some rows where the date of the appointment was before the schedule date and one negatiove age column.

**References**
1.https://stackoverflow.com/

2.https://www.geeksforgeeks.org/

3.https://www.mathworks.com/

4.https://matplotlib.org/stable/index.html

5.https://pandas.pydata.org/docs/

