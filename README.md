# Machine-Learning
## Archives of some projects for the machine learning
### Medical_Centre:
Bay clinic is a medical centre in Houston that operates with a unique mission of blending research and education 
with clinical and hospital care. The medical center has a huge head force of 25,000 employees, and as a result of the 
combined effort of those employees, the medical center has been able to handle approximately 3 million visits so 
far. In recent times, the hospital was incurring losses despite having the finest doctors available and not lacking 
scheduled appointments. To investigate the reason for the anomaly, a sample data dump of appointments
medicalcentre.csv is hereby presented. The collected data provides information on the patient’s age, gender, 
appointment date, various diseases, etc.

At the beginning of this part of the code, a function is defined to convert the dataset in xlsx format to csv format. Therefore, it is also possible to run the code by only downloading the dataset in xlsx format. If you choose to run the code directly with the dataset in csv format, run only the last line in code block [1].

I personally think there is still a problem in this code. Since there is a feature that is *Neighbourhood*, it does not exist in the form of numbers, so it is necessary to convert the data of string type to data of number type. I used binary code for conversion, maybe it would be better to use one-hot encoding.
