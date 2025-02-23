## hospital_analysis_EXCEL

#### About Dataset

**Context:**
* This synthetic healthcare dataset has been created to serve as a valuable resource for data science, machine learning, and data analysis enthusiasts.
* It is designed to mimic real-world healthcare data, enabling users to practice, develop, and showcase their data manipulation and analysis skills in the context of the healthcare industry.

-----------------
**Inspiration:**
* The inspiration behind this dataset is rooted in the need for practical and diverse healthcare data for educational and research purposes.
* Healthcare data is often sensitive and subject to privacy regulations, making it challenging to access for learning and experimentation.
* To address this gap, I have leveraged Python's Faker library to generate a dataset that mirrors the structure and attributes commonly found in healthcare records. By providing this synthetic data, I hope to foster innovation, learning, and knowledge sharing in the healthcare analytics domain.

*Dataset Information:*
* Each column provides specific information about the patient, their admission, and the healthcare services provided, making this dataset suitable for various data analysis and modeling tasks in the healthcare domain.
* Here's a brief explanation of each column in the dataset -
* Name: This column represents the name of the patient associated with the healthcare record.
* Age: The age of the patient at the time of admission, expressed in years.
* Gender: Indicates the gender of the patient, either "Male" or "Female."
* Blood Type: The patient's blood type, which can be one of the common blood types (e.g., "A+", "O-", etc.).
* Medical Condition: This column specifies the primary medical condition or diagnosis associated with the patient, such as "Diabetes," "Hypertension," "Asthma," and more.
* Date of Admission: The date on which the patient was admitted to the healthcare facility.
* Doctor: The name of the doctor responsible for the patient's care during their admission.
* Hospital: Identifies the healthcare facility or hospital where the patient was admitted.
* Insurance Provider: This column indicates the patient's insurance provider, which can be one of several options, including "Aetna," "Blue Cross," "Cigna," "UnitedHealthcare," and "Medicare."
* Billing Amount: The amount of money billed for the patient's healthcare services during their admission. This is expressed as a floating-point number.
* Room Number: The room number where the patient was accommodated during their admission.
* Admission Type: Specifies the type of admission, which can be "Emergency," "Elective," or "Urgent," reflecting the circumstances of the admission.
* Discharge Date: The date on which the patient was discharged from the healthcare facility, based on the admission date and a random number of days within a realistic range.
* Medication: Identifies a medication prescribed or administered to the patient during their admission. Examples include "Aspirin," "Ibuprofen," "Penicillin," "Paracetamol," and "Lipitor."
* Test Results: Describes the results of a medical test conducted during the patient's admission. Possible values include "Normal," "Abnormal," or "Inconclusive," indicating the outcome of the test.

**Usage Scenarios:**
*This dataset can be utilized for a wide range of purposes, including:*
* Developing and testing healthcare predictive models.
* Practicing data cleaning, transformation, and analysis techniques.
* Creating data visualizations to gain insights into healthcare trends.
* Learning and teaching data science and machine learning concepts in a healthcare context.
* You can treat it as a Multi-Class Classification Problem and solve it for Test Results which contains 3 categories(Normal, Abnormal, and Inconclusive).

-----------------------------------------------------

 **DATA GATHERING:**

* Our Data was sourced from Kaggle as stated in the project intro

**DATA CLEANING & TRANSFORMATION:**

* We had some inconsistencies
* Spelling of patient names , were incorrectly written , we must adjust them to remove incorrectness
* The Hospital names had also misplaced commas , we used power query to do advanced cleaning .
* We introduced new columns .
* Difference of admission date and discharge date to know efficiency of hospitals.
* Seasons from admission date to understand/predict admissions of patients.
* We utilized power query to clean and transform our data before we loaded it , to the data model and out of it we made pivot charts . 

-----------------------------------------------------

**DATA VISUALIZATION & ANALYSIS:**

* Based on our healthcare as it contains clinical data majority and a little of administrative.
* We are going to analyze our dataset based on these questions, draw our dashboards and come up with findings
	1. Common medical condition among age-generations and gender
	2. Hospital(s) with received no of patients
	3. No of admissions yearly/monthly to find rate over the years/period
	4. Identifying top insurance providers covering bills of  patients
	5. Pinpointing medical condition with bills over the years
	6. Identifying top hospitals with efficiency based on the difference between admission date & discharge date
	7. Classifying admission type based on the  no of patients
	8. Segmenting test-results according to age-generation and gender
	9. Segmenting patients on their blood type 
	10. Finding growth rate of doctors & admission of patients over the years/monthly
	11. Finding which season has most no of patients
	12. Classifying medications based on no of patients and billing amount
	
**This are going to guide us get insights and understand KPI's of our data**  

--------------------------------------------

#### RECOMMENDATIONS:

* From the test results findings, female tests return mostly abnormal test  while male tests return mostly normal results.
* But generally , 34% are abnormal while normal and inconclusive both 33%. By applying advanced lab instruments and qualitative analysis on patients , hospitals would come up with more improved test results.
* Majority of hospitals receive elective patients , urgent and emergency patients in that order . It facilitates hospitals to prepare in advance to do treatments saving time for other patient type like an unplanned emergency patients.
* Out of the medical conditions in our data, Baby boomers were appearing on top of the most affected patients, coming up with a structure that reduces this scenarios amongst the old would aid hospitals save on their resources
*  During summer, hospitals receive more patients than other seasons, being prepare would be advised and also advising their past patients to stay clean & reduce contamination may be helpful.
*   emale patients had more patients with O- blood type compared to the male , hence identifying these is crucial incase hospital would need blood donors .
*     The line chart of doctors is similar to that of billing of patients, which indicates peak times hospitals should  have a ready and fully functional team to admit patients.
* Cigna was the most coverer of bills in majority of hospitals, having a good relationship with insurance companies , would vital to keep the hospital staff on their jobs/make the hospital's cashflow healthy.
* Cost of diabetes, obesity and arithiris are top 3 medical conditions with high cost of bill, hospitals concentrating on them may save lives.


------------------------

*Acknowledgement:*

* I acknowledge the importance of healthcare data privacy and security and emphasize that this dataset is entirely synthetic. It does not contain any real patient information or violate any privacy regulations.
* I hope that this dataset contributes to the advancement of data science and healthcare analytics and inspires new ideas.
* Feel free to explore, analyze, and share your findings with the Kaggle community.

