
 ## Problem Statement  :
🚗 Car Insurance Claims – Fraud Detection


Insurance fraud is a significant challenge that causes massive financial losses and is difficult to detect through manual reviews alone. This project leverages Machine Learning to automate the identification process by analyzing complex patterns within policyholder demographics and accident reports.
    
The goal is to build a reliable predictive model that can accurately distinguish between fraudulent and legitimate claims.
    
This automated solution helps insurance providers reduce risk, improve operational efficiency, and ensure faster processing for honest customers.

## DataSet Description
months_as_customer : Number of months the lead has been a customer

age : Age of the policyholder

policy_number : Unique identifier for the insurance policy

policy_state : The state where the policy was issued

policy_deductable : The amount paid by the insured before insurance coverage kicks in

policy_annual_premium : The yearly premium paid by the customer

umbrella_limit : Additional liability insurance beyond standard limits

insured_sex : Gender of the policyholder

insured_education_level : Educational background of the insured

insured_occupation : Professional occupation of the policyholder

insured_hobbies : Hobbies or interests of the insured

incident_type : Category of the accident (e.g., Multi-vehicle Collision, Theft)

collision_type : Point of impact during the collision (Front, Rear, Side)

incident_severity : Level of damage caused by the incident (Major, Minor, Total Loss)

authorities_contacted : Type of authority notified at the scene

incident_hour_of_the_day : The specific hour when the accident occurred

number_of_vehicles_involved : Total count of vehicles involved in the accident

witnesses : Number of individuals who witnessed the incident

total_claim_amount : The total financial claim made by the insured

fraud_reported : Whether fraud was reported (Y/N)

## Goal :-

predicts if an insurance claim is fraudulent or not.

Dependent Variable (Target Variable):

fraud_reported is the target variable that indicates whether an insurance claim is fraudulent ('Y') or legitimate ('N'). It serves as the primary label that the model learns to predict based on the provided policy and incident details.
