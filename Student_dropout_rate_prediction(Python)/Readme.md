## Problem Statement

Student Dropout Rate Prediction

Educational institutions face challenges in identifying students at risk of dropping out. Early detection can help institutions provide timely interventions and improve academic success rates.

This project aims to perform Exploratory Data Analysis (EDA) and build a machine learning classification model to predict whether a student will:

-> Drop out

-> Likely to Graduate

## Dataset Description

Marital_status : Student’s marital status

Application_mode : Mode of application to the course

Application_order : Order of application preference

Course : Course attended by the student

Daytime_evening_attendance : Attendance schedule (Daytime/Evening)

Previous_qualification : Student’s previous qualification

Previous_qualification_grade : Grade obtained in previous qualification

Nationality : Student nationality

Mother_qualification : Mother’s education level

Father_qualification : Father’s education level

Mother_occupation : Mother’s occupation

Father_occupation : Father’s occupation

Admission_grade : Admission grade of the student

Displaced : Whether the student is displaced (Yes/No)

Educational_special_needs : Special educational needs (Yes/No)

Debtor : Whether the student has outstanding debts (Yes/No)

Tuition_fees_up_to_date : Tuition fees paid up to date (Yes/No)

Gender : Student gender

Scholarship_holder : Whether the student holds a scholarship (Yes/No)

Age_at_enrollment : Student age at the time of enrollment

International : Whether the student is an international student (Yes/No)

Curricular_units_1st_sem_credited : Credited units in 1st semester

Curricular_units_1st_sem_enrolled : Enrolled units in 1st semester

Curricular_units_1st_sem_evaluations : Evaluations in 1st semester

Curricular_units_1st_sem_approved : Approved units in 1st semester

Curricular_units_1st_sem_grade : Average grade in 1st semester

Curricular_units_1st_sem_without_evaluations : Units without evaluations in 1st semester

Curricular_units_2nd_sem_credited : Credited units in 2nd semester

Curricular_units_2nd_sem_enrolled : Enrolled units in 2nd semester

Curricular_units_2nd_sem_evaluations : Evaluations in 2nd semester

Curricular_units_2nd_sem_approved : Approved units in 2nd semester

Curricular_units_2nd_sem_grade : Average grade in 2nd semester

Curricular_units_2nd_sem_without_evaluations : Units without evaluations in 2nd semester

Unemployment_rate : Regional unemployment rate

Inflation_rate : Inflation rate

GDP : Gross Domestic Product

Target : Final student status (Dropout / Enrolled / Graduate)

## Dependent Variable

- Target

The Target variable indicates the final academic outcome of a student. The goal of this project is to develop a supervised machine learning model capable of accurately classifying students into one of the three categories: Dropout, Enrolled, or Graduate, using the available input features.

## Attribute Information

1. **Marital Status**

   
    1 – Single
    
    2 – Married
    
    3 – Widower
    
    4 – Divorced
    
    5 – Facto union
    
    6 – Legally separated

3. **Application Mode**

   
    1 – 1st phase - general contingent
    
    2 – Ordinance No. 612/93
    
    5 – 1st phase - special contingent (Azores Island)
    
    7 – Holders of other higher courses
    
    10 – Ordinance No. 854-B/99
    
    15 – International student (bachelor)
    
    16 – 1st phase - special contingent (Madeira Island)
    
    17 – 2nd phase - general contingent
    
    18 – 3rd phase - general contingent
    
    26 – Ordinance No. 533-A/99, item b2) (Different Plan)
    
    27 – Ordinance No. 533-A/99, item b3 (Other Institution)
    
    39 – Over 23 years old
    
    42 – Transfer
    
    43 – Change of course
    
    44 – Technological specialization diploma holders
    
    51 – Change of institution/course
    
    53 – Short cycle diploma holders
    
    57 – Change of institution/course (International)

5. **Application Order**

   
    0 to 9 – Ranking (0: first choice; 9: last choice)

7. **Course**

   
    33 – Biofuel Production Technologies
    
    171 – Animation and Multimedia Design
    
    8014 – Social Service (evening attendance)
    
    9003 – Agronomy
    
    9070 – Communication Design
    
    9085 – Veterinary Nursing
    
    9119 – Informatics Engineering
    
    9130 – Equinculture
    
    9147 – Management
    
    9238 – Social Service
    
    9254 – Tourism
    
    9500 – Nursing
    
    9556 – Oral Hygiene
    
    9670 – Advertising and Marketing Management
    
    9773 – Journalism and Communication
    
    9853 – Basic Education
    
    9991 – Management (evening attendance)

9. **Attendance**

    
    1 – Daytime
    
    0 – Evening

11. **Previous Qualification**

    
    1 – Secondary education
    
    2 – Higher education - bachelor's degree
    
    3 – Higher education - degree
    
    4 – Higher education - master's
    
    5 – Higher education - doctorate
    
    6 – Frequency of higher education
    
    9 – 12th year of schooling - not completed
    
    10 – 11th year of schooling - not completed
    
    12 – Other - 11th year of schooling
    
    14 – 10th year of schooling
    
    15 – 10th year of schooling - not completed
    
    19 – Basic education 3rd cycle (9th/10th/11th year) or equiv.
    
    38 – Basic education 2nd cycle (6th/7th/8th year) or equiv.
    
    39 – Technological specialization course
    
    40 – Higher education - degree (1st cycle)
    
    42 – Professional higher technical course
    
    43 – Higher education - master (2nd cycle)

13. **Previous Qualification (Grade)**

    
    0 to 200 – Numerical grade value

15. **Nationality**

    
    1 - Portuguese

    2 - German

    6 - Spanish

    11 - Italian

    13 - Dutch

    14 - English

    17 - Lithuanian

    21 - Angolan

    22 - Cape Verdean

    24 - Guinean

    25 - Mozambican

    26 - Santomean

    32 - Turkish

    41 - Brazilian

    62 - Romanian

    100 - Moldova

    101 - Mexican

    103 - Ukrainian

    105 - Russian

    108 - Cuban

    109 - Colombian

9 & 10. **Parent's Qualifications (Mother/Father)**

    1 – Secondary Education (12th Year)
    
    2 – Higher Education - Bachelor's
    
    3 – Higher Education - Degree
    
    4 – Higher Education - Master's
    
    5 – Higher Education - Doctorate
    
    6 – Frequency of Higher Education
    
    9 – 12th Year - Not Completed
    
    11 – 7th Year (Old)
    
    18 – General commerce course
    
    19 – Basic Education 3rd Cycle
    
    22 – Technical-professional course
    
    34 – Unknown
    
    35 – Can't read or write
    
    37 – Basic education 1st cycle (4th/5th year)
    
    38 – Basic Education 2nd Cycle (6th/7th/8th Year)
    
    43 – Higher Education - Master (2nd cycle)

11 & 12. **Parent's Occupation (Mother/Father)**

    0 – Student
    
    1 – Legislative/Executive Directors
    
    2 – Specialists in Intellectual/Scientific Activities
    
    3 – Intermediate Level Technicians
    
    4 – Administrative staff
    
    5 – Personal Services/Security/Sales
    
    6 – Farmers/Skilled Agricultural Workers
    
    7 – Skilled Workers (Industry/Construction)
    
    8 – Machine Operators/Assembly
    
    9 – Unskilled Workers
    
    10 – Armed Forces
    
    90 – Other
    
    122 – Health professionals
    
    123 – Teachers
    
    125 – ICT Specialists

13. **Gender**
    
    1 – Male
    
    0 – Female
