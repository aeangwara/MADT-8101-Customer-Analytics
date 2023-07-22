# 01 Design Customer data platform (Cinema Business)
MADT 8103 Customer Analytics

Date 11 Jun 2023

:triangular_flag_on_post: **Objective**

             1.Convert new customer
 
             2.Maintain current customer

             3.Prevent customer lost

### Data Pipeline



Below is example to design customer single view

#### CSV for create new profile  

| Golden_ID | Member_I | Member_Date | Customer_Name | Telephone_Number | Line_ID | Email | Register_Channel | DOB | Sex | Occupation | CAC |
|---|---|---|---|---|---|---|---|---|---|---|---|

#### CSV for activate personalize campaign via application

| Golden_ID 	| Last_active 	| NO. of Visit_(Past 3 months) 	| APRU 	| NO.Visit_seat type 	| NO.Visit_Drink&Snack 	| Kind of movies visit in 3 months 	| Spending_index 	| Avg. of ticket purchase 	| Mean time between pur. 	| CLTV 	| Disc. score 	|
|-----------	|-------------	|------------------------------	|------	|--------------------	|----------------------	|----------------------------------	|----------------	|-------------------------	|------------------------	|------	|-------------	|

#### CSV for Gamification

| Golden_ID 	| Churn_Scoring 	| CLTV 	| Balance_score 	| Score_movement & ARP 	| Redemption_items 	|
|-----------	|---------------	|------	|---------------	|----------------------	|------------------	|



