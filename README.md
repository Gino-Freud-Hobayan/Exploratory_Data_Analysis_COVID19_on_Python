# Exploratory Data Analysis(EDA) on Python

<img width="450" alt="Capstone FINAL EDA - revised by Gino" src="https://github.com/Gino-Freud-Hobayan/Exploratory_Data_Analysis_COVID19_on_Python/assets/117270964/d5ca65be-6b73-4637-9209-496cac7e9d0c">







<br>

### EDA on Python about COVID-19 Cases in the City of Manila from 2020-2023

<br>
<br>


### Link to the Google Drive
### - Slideshow/Presentation: [https://docs.google.com/presentation/d/14flA5fAz6sI6FoIZjT0i-NIM9b48pMiJRTlnwcdTRK8/edit?usp=sharing  ](https://drive.google.com/file/d/1bDyJTsF0UFhrhkldfWvFMxq_NXGu3VD3/view?usp=sharing)

### - covid2020-2023.csv: https://drive.google.com/drive/folders/1LRZy4zms4wMs-iYtKuLsUbMuhy6gyuwB?usp=sharing

<br><br>

We used COVID-19 data from the Dept. of Health for this Capstone Project.

We were able to practice dealing with an extremely large dataset (around 4.1 million rows)

We performed the following:

<br>


## **1. ROCCC for the Reliability of the Dataset**

The dataset follows the ROCCC Analysis as described below:
- Reliable - yes, not biased
- Original - yes, can locate the original public data
- Comprehensive - yes, not missing important information
- Current - yes, updated monthly
- Cited - yes

<br><br>



## **2. Data Cleaning**

<img width="377" alt="Data cleaning pic" src="https://github.com/Gino-Freud-Hobayan/Exploratory_Data_Analysis_COVID19_on_Python/assets/117270964/f540d704-b3ea-4e65-9b85-aa0667b15642">


We dealt with 5 batches containing around 4.1 million rows of data in total.

After filtering it, we now only had 168,000 + rows of data to work with.

<br>

## **Data Cleaning steps:**

- Filtered the dataset to only include data from the “City of Manila”
- Checked for Duplicates
- Checked for Missing/Null Values
- Dropped Unnecessary Columns
- Replaced the null values with appropriate data like “Not Recorded”
- Merged the five cleaned datasets into one 

I posted a Jupyter notebook of one of the batches (**"batch_4_covid_manilaupdated3.ipynb"**) that shows how we did our Data Cleaning.

<br>

One of our groupmates Erwin did the Majority of the Data Cleaning 

I learned a lot from him and became more confident and competent in my Data Cleaning skills in Python.

<br>
<br>


## **3. Exploratory Data Analysis**

<img width="376" alt="EDA pic1" src="https://github.com/Gino-Freud-Hobayan/Exploratory_Data_Analysis_COVID19_on_Python/assets/117270964/7277fb63-1921-4e30-aa8e-ec7d3b7a73b5">



We performed multiple Data Visualizations on our merged and cleaned Datasets

I posted the Jupyter Notebook that covers all of it including my revised Data Visualizations

(**"EDA_covid_manila_FINAL_Gino.ipynb"**)

<br>
<br>
<br>


## **4. Key Findings:**

1. Age group **25-29** has the Highest number of cases, followed shortly by **30-34** and **20-24**, most likely these are the F2F and Healthcare workers who are in contact with a large number of people daily.

2. Most of the deaths occurred for Ages 50 and up. One of the reasons might be comorbidities that come with older age and a weaker immune system.
3. We have seen earlier that **the age group of 25 to 29 had the highest number of cases yet they had one of the least number of deaths.**
4. Several counts of death in children and adolescents were observed. These deaths are uncommon, and their deaths might also be linked to some underlying conditions. Additionally, for infants, a possible reason may be that their immune system is not yet well developed.


5. A huge spike in the number of cases occurred from 2020-2021.

6. Administration of COVID-19 vaccines helped reduce the number of cases


7. The dataset contains **ages ranging from 2 to 80 yrs old (spread)**, with a **median age of 32 years.**


8. **The majority of individuals fall between ages 27 and 47**, as indicated by the interquartile range (IQR) of 20. 

    This indicates that **the data might be slightly positively skewed**. This means that the distribution may have a longer tail on the right (higher) side.


9. **The presence of an 80-year-old individual may be considered an outlier**, indicating an unusual or extreme age compared to the rest of the dataset. 

<br>

### Overall, the data exhibits a diverse age distribution, with a notable concentration of cases in the middle age range.

    
<br><br>

     
## **Limitations:**
    
1. The analysis is based on the available dataset from DOH. 

    Data for 2023 is currently inconclusive and is still being updated by DOH. 

    Additionally, the dataset contains a lot of null values thus affecting the accuracy of the analysis.
    
    <br> 




<br>
<br>

## **5. Conclusion and Recommendations**

<img width="451" alt="actions taken early vs later" src="https://github.com/Gino-Freud-Hobayan/Exploratory_Data_Analysis_COVID19_on_Python/assets/117270964/b726b0b2-e760-42c5-9f88-1697cb1d1d46">



### 1. We recommend that people get vaccinated and take the booster shots, as the data clearly shows a large drop in cases once the vaccines started rolling out.

<br><br>

### 2. It is recommended that the elderly and senior citizens have minimal contact with many people since they have the highest fatality rate out of all the Age Groups that contracted the virus in this dataset.

<br><br>

### 3. As they say: “an ounce of prevention is worth a pound of cure”
Neighbors such as Singapore, Taiwan, and Vietnam swiftly implemented preventive measures.
- large-scale public health campaigns 
- calibrated restrictions on public events and gatherings
- proactive contact tracing to prevent intra-community transmission 
- Regular and transparent communication between top officials and the citizenry.

<br><br>

### 4. Don’t be Complacent 
- There was a huge spike in cases back in January 2022, most likely due to Holiday gatherings, complacency, and the presence of the Omicron variant

http://www.cnnphilippines.com/news/2022/1/1/PH-COVID-19-cases-New-Year-s-Day-.html

https://www.reuters.com/business/healthcare-pharmaceuticals/philippines-confirms-community-transmission-omicron-cases-hit-record-2022-01-15/

<br><br>

### 5. Quarantine protocols are effective. 
If a person tests positive for COVID, they should immediately take action.

Summary:
- Number of people who survived: 17,968
- Number of people who died: 252
- Percentage of people who survived: 98.61%
- Percentage of people who died: 1.39%

This analysis shows that **the majority of people who were quarantined (98.61%) survived, while a small percentage (1.39%) unfortunately died.** 
The data suggests that the quarantine protocols had a relatively high effectiveness in preventing fatalities during the quarantine period.

<br><br>


### 6. We should learn from our neighboring Countries and the Government should act swiftly in times like these. 

If the travel ban on airports was implemented earlier, it could have lessened the spread of the virus.

Imagine the number of lives you can save.

In a situation where **actions taken early** can have a much bigger impact than actions taken later, time is a crucial factor.

<br>
<br>

<img width="534" alt="Save one life EDA" src="https://github.com/Gino-Freud-Hobayan/Exploratory_Data_Analysis_COVID19_on_Python/assets/117270964/625129fe-c56d-4aae-9ca1-7eb3f839407c">

<br>
<br>
<br>
<br>


![Thank you wordcloud1](https://github.com/Gino-Freud-Hobayan/Exploratory_Data_Analysis_COVID19_on_Python/assets/117270964/014fff25-dd93-47dc-a37e-189110787894)
