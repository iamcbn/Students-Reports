# Students’ Records

This project sets itself apart from other data analytics projects, showcasing the remarkable capabilities of Excel in data analysis.

![](Untitled%20design%20(4).png)


## Introduction

Let's embark on this data journey together through a story! So, I have this friend who's a teacher. He was quite stressed out because he had to manually calculate and write his students' scores for their report cards. After hearing his struggles, I suggested automating the process. Unfortunately, due to the school's limited budget, full automation seemed impossible. This sparked the idea of creating a completely automated report generation project. All you need to do is change the student's number.

## The Challenge

Dealing with the hassle of compiling scores and writing report cards by hand.

## Data Source

The dataset was created using Python's Faker library based on specific criteria I provided. You can take a look at the complete code I used by clicking [here](https://github.com/iamcbn/Students-Records/blob/main/Student%20Records.ipynb)!


 ![](Code%20Snippet.png)  
 
 ![](Excel%20Snippet.png)

## Tools Used/Concepts Applied

For this project, I utilized the following tools:
- Faker and Pandas Libraries (Python)
- Excel
Here are a few Excel functions I employed:
- XLOOKUP
- VLOOKUP (I used this to demonstrate success on a tight budget, as not everyone has access to Microsoft 365)
- Conditional Formatting
- Data Validation
- Excel security measures
- Concatenate, and more.

## Overview

The project consists of three worksheets. You can access the workbook by clicking [here](https://iamcbn1-my.sharepoint.com/:x:/g/personal/bruno_iamcbn1_onmicrosoft_com/EUhyNR86gOZLrY_7ei4biJ8BuLe4zZe72b-GwT4MEhPMtg?e=pFHx7e) On the **_Report Card_** worksheet, you can modify the **_Student Number_**. To make edits, a password is required, which is simply a **_full stop/dot (.)_**.

### Student Records

The first worksheet, Student Records, contains the raw data generated by Python. It includes student details like a unique student number, first name, last name, class, gender, and continuous assessment (CA) and examination scores for each subject.

### Student Scores

The second worksheet, Student Scores, includes student numbers, total percentages, and overall scores for each subject (CA + Exam Score). To achieve this, I nested the SUM function with VLOOKUP/XLOOKUP. This allowed me to fetch CA and exam scores, and then sum them up to determine the total scores.

### Report Card

The third sheet, Report Card, displays individual student information and results. To view a student's report card, you only need to change the student number. Additionally, I resolved the challenge of writing personalized comments for each student. Upon displaying a report card, you'll find a tailored principal's comment based on the student's classroom performance. To accomplish this, I employed XLOOKUP (note that VLOOKUP can also be used), conditional formatting, concatenate function, and others.


| 1 | 2
| --- | ---
| ![](Report%20snippet%201.png) | ![](Report%20snippet%202.png)

## Special Note

This project aims to demonstrate that even with limited resources and tools (such as lacking Microsoft 365 and other Power Platform apps), a school can automate the creation of students' report cards. Adding new students is a breeze as well. Just input a new student record, and the Report Card page will automatically generate a report (enter the new student's number to view their results). While this project can be expanded with Power Platform (Power Apps, Power Automate, and Power BI), I opted for Microsoft Excel due to simplicity and budget constraints.


![image](https://github.com/iamcbn/Hotel-Guests-Analysis/assets/132440348/bb514707-1966-433b-ae43-4d052197930b)
