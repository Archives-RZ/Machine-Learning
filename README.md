# Machine-Learning
## Archives of some projects for the machine learning
### Medical_Centre:
Bay clinic is a medical centre in Houston that operates with a unique mission of blending research and education 
with clinical and hospital care. The medical center has a huge head force of 25,000 employees, and as a result of the 
combined effort of those employees, the medical center has been able to handle approximately 3 million visits so 
far. In recent times, the hospital was incurring losses despite having the finest doctors available and not lacking 
scheduled appointments. To investigate the reason for the anomaly, a sample data dump of appointments
*MedicalCentre.csv* is hereby presented. The collected data provides information on the patient’s age, gender, 
appointment date, various diseases, etc.

At the beginning of this part of the code, a function is defined to convert the dataset in xlsx format to csv format. Therefore, it is also possible to run the code by only downloading the dataset in xlsx format. If you choose to run the code directly with the dataset in csv format, run only the last line in code block [1].

I personally think there is still a problem in this code. Since there is a feature that is *Neighbourhood*, it does not exist in the form of numbers, so it is necessary to convert the data of string type to data of number type. I used binary code for conversion, maybe it would be better to use one-hot encoding.

### Heart:
Today, heart disease is one of the biggest causes of morbidity and mortality. The ability to predict cardiovascular 
disease has become an important subject area for clinical data analysis. The process of identifying the presence of a 
heart disease can be difficult due to several contributing factors, e.g., cholesterol, pulse rate, blood pressure, etc. 
Machine learning is now extensively used for early diagnosis to increase the chances of survival. You are hereby 
presented with a sample of heart disease dataset containing a collection of demographic and clinical characteristics 
from 303 patients.

In this part of the code, the imported dataset is *heart.csv*. And in this part of the code, choose to use one-hot encoding to process character data.

### Artificial Intelligence for wearables:
This part of the code mainly studies the main factors affecting calorie consumption and predicts calorie consumption through machine learning. The code consists of two parts: data analysis and machine learning. The main work of data analysis is to collect, analyze and process the health monitoring data of multiple users. The main work of machine learning is to establish, evaluate, select and optimize models.

This code contains three datasets: *dailyActivity_merged.csv*, *sleepDay_merged.csv*, *fitbit_df.csv*. The last dataset is obtained after processing and merging the first two datasets.

I personally think that there is a problem with this part of the code. After obtaining the optimal machine learning model in the last step, it should be placed on a larger dataset or on this dataset for verification, which is more convincing.
