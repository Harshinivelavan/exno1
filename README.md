# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
READING AND DISPLAYING THE DATASET
<img width="1369" height="557" alt="Screenshot 2025-08-28 140740" src="https://github.com/user-attachments/assets/30f26cd8-797b-43a9-9a78-981879614e7d" />

CHECKING NULL VALUES
<img width="1274" height="522" alt="Screenshot 2025-08-28 140804" src="https://github.com/user-attachments/assets/bac53759-ff66-4872-acd5-5a861b00e899" />


SUM OF NULL VALUES IN EACH ROWS
<img width="1352" height="300" alt="Screenshot 2025-08-28 140823" src="https://github.com/user-attachments/assets/c2e192ef-f432-41fd-b043-8c4a90acb37f" />

DROP NULL VALUES
<img width="1347" height="675" alt="Screenshot 2025-08-28 140845" src="https://github.com/user-attachments/assets/4f35055a-8d7e-4591-a4ed-1d30376faec7" />

FILL NULL VALUES WITH "O"
<img width="1359" height="518" alt="Screenshot 2025-08-28 140902" src="https://github.com/user-attachments/assets/ca4aeee3-0e13-4bb1-8c6d-19fb5486ea53" />

FILL NULL VALUES WITH FFILL OR BFILL
<img width="1375" height="504" alt="Screenshot 2025-08-28 140920" src="https://github.com/user-attachments/assets/7d243f51-b9b0-46bd-aab6-1ed9e6fcee7d" />

CALCULATE MEAN VALUE OF A COLUMN AND FILL IT WITH NULL VALUES


<img width="404" height="108" alt="Screenshot 2025-08-28 140938" src="https://github.com/user-attachments/assets/33d2a3d5-3a6e-4224-8211-bcc2cc31ffb5" />


<img width="1302" height="321" alt="Screenshot 2025-08-28 140957" src="https://github.com/user-attachments/assets/ab380698-4df7-4d8a-a154-07e13f85c629" />

DROP NULL VALUES
<img width="1363" height="652" alt="Screenshot 2025-08-28 141015" src="https://github.com/user-attachments/assets/a46e81f4-a199-4403-a38f-86fdcc8ad7d8" />

<img width="477" height="81" alt="image" src="https://github.com/user-attachments/assets/9d228d9c-922f-49e6-aea8-2ed368cc4ade" />

BOXPLOT FUNCTION HERE TO DETECT OUTLIER
<img width="1324" height="280" alt="Screenshot 2025-09-02 083945" src="https://github.com/user-attachments/assets/b21bc7c2-cb3f-4eda-9d10-3f32cb4a5f7b" />

<img width="904" height="544" alt="Screenshot 2025-09-02 083953" src="https://github.com/user-attachments/assets/51ad7915-fe65-4f91-b67a-d4f94ab22927" />


PERFORM IQR METHOD AND DETECT OUTLIER VALUES ABD REMOVE REMOVE OUTLIER

<img width="1307" height="572" alt="Screenshot 2025-09-02 084219" src="https://github.com/user-attachments/assets/4c3d7118-7f7a-4088-be87-6974536ae80e" />
<img width="549" height="629" alt="Screenshot 2025-09-02 084231" src="https://github.com/user-attachments/assets/b67fb439-71cc-40c5-bcc9-8677f08c6ce7" />

BOXPLOT FUNCTION HERE TO CHECK OUTLIER IS REMOVED

<img width="968" height="542" alt="Screenshot 2025-09-02 084238" src="https://github.com/user-attachments/assets/f5e02fc3-eed7-492a-9b8f-285739b2696d" />

<img width="1048" height="122" alt="image" src="https://github.com/user-attachments/assets/758c8cb9-193e-4a62-acc0-2e688d7bef56" />

BOXPLOT FUNCTION HERE TO DETECT OUTLIER
<img width="1198" height="550" alt="Screenshot 2025-09-02 084340" src="https://github.com/user-attachments/assets/3ce96bc9-c105-4c6f-8bc7-129803926928" />
<img width="894" height="619" alt="Screenshot 2025-09-02 084348" src="https://github.com/user-attachments/assets/9b2947d9-576e-4ebf-b5af-66ce168d7921" />

PERFORM Z SCORE METHOD AND DETECT OUTLIER VALUES
<img width="766" height="566" alt="Screenshot 2025-09-02 084452" src="https://github.com/user-attachments/assets/e9f1b3d3-2c11-4280-8ce0-33454b29413a" />

REMOVE OUTLIERS
<img width="879" height="405" alt="Screenshot 2025-09-02 084555" src="https://github.com/user-attachments/assets/10d9448f-c739-4d12-a182-d8233d749fdc" />
<img width="441" height="712" alt="Screenshot 2025-09-02 084601" src="https://github.com/user-attachments/assets/fac91d44-ab75-4c5b-b7eb-59370b227844" />

USE BOXPLOT FUNCTION HERE TO CHECK OUTLIER IS REMOVED
<img width="785" height="542" alt="Screenshot 2025-09-02 084607" src="https://github.com/user-attachments/assets/54d781cc-935a-41a6-8fe7-bda8256af3c2" />

#SUMMARY


This script shows how to handle missing values and outliers in a dataset. It starts by reading a CSV file, checking for null values, and then handling them in different ways—either by dropping them, filling them with a constant value (“0”), using forward/backward fill, or replacing them with the mean of a column. Next, it works with an age dataset to detect and remove outliers using a boxplot and the IQR method. After removing outliers, it checks again with a boxplot to confirm. Finally, it uses another dataset to detect and remove outliers with the Z-score method, again using boxplots before and after to show the results. Overall, the script explains how to clean data by treating missing values and outliers.

# Result
          The given data has been read and performed data cleaning and saved the cleaned data to a file successfully
