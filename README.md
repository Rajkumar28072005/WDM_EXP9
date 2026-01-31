### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 31.01.2025
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
<img width="1001" height="223" alt="Screenshot 2026-01-31 101203" src="https://github.com/user-attachments/assets/da6bc26c-4263-4ba1-85d7-aea515b69a3f" />
<img width="986" height="480" alt="Screenshot 2026-01-31 101147" src="https://github.com/user-attachments/assets/8b18f456-c505-418d-9cbe-2edbd6d39d19" />
<img width="1174" height="624" alt="Screenshot 2026-01-31 100732" src="https://github.com/user-attachments/assets/4d8d8296-96c3-4d22-bf21-f62ee29aa177" />

### Result:

Thus preprocessing techniques is implemented on twitter data using rapidminer.
