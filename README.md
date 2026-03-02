# Getting Goodnights Sleep

Your client, SleepProject, has shared anonymized sleep data from their hot new sleep tracking app SeetaSleep. As their data science consultant, your mission is to analyze the lifestyle survey data with Python to discover relationships between exercise, gender, occupation, and sleep quality. See if you can identify patterns leading to insights on sleep quality.

## 💾 The data: sleep_health_data.csv

SleepProject has provided you with an anonymized dataset of sleep and lifestyle metrics for 374 individuals. This dataset contains average values for each person calculated over the past six months. The data is saved as `sleep_health_data.csv`.

The dataset includes 13 columns covering sleep duration, quality, disorders, exercise, stress, diet, demographics, and other factors related to sleep health. 

Use the Data to answer the following questions

- Which occupation has the lowest average sleep duration? Save this in a string variable called lowest_sleep_occ.

- Which occupation has the lowest average sleep quality? Save this in a string variable called lowest_sleep_quality_occ. Did the occupation with the lowest sleep duration also have the lowest sleep quality? If so assign a boolean value to variable same_occ variable, True if it is the same occupation, and False if it isn't.

- Let's explore how BMI Category can affect sleep disorder rates. Start by finding what ratio of app users in each BMI Category have been diagnosed with Insomnia. Create a dictionary named: bmi_insomnia_ratios. The key should be the BMI Category as a string, while the value should be the ratio of people in this category with insomnia as a float rounded to two decimal places. Here is an example:

bmi_insomnia dictionary

Please note the keys are case-sensitive, and should be formatted as shown in the example dictionary.
