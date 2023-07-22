# 01 Design Customer data platform (Cinema Business)
MADT 8103 Customer Analytics

Date 11 Jun 2023

:triangular_flag_on_post: **Objective**

             1.Convert new customer
 
             2.Maintain current customer

             3.Prevent customer lost

### Data Pipeline

![Cinema Pipeline](https://imgur.com/0V3VeuP)


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

#### :white_check_mark: Usecase : Acquire new customers through existing customer

[![](https://mermaid.ink/img/pako:eNpVkMtOwzAQRX_F8gqkFvZZIOXBsgKJrki6mNqTxsKPyB5TlST_jp0sKF6N79wzr4kLJ5EXvNfuKgbwxI5NZ1l6ZVt--ydS4guJjdGnbMAT2-9f5lrHQOiVvbDzjfUIFD3OrHp4965XGrMqNk943KpVGWT1VCfVGfWDgQkwI6iLvXMvm7leu7zZVLNpGwjD2YGXzDiryK1t_7EDWIv6dM8er25mr235XDHCQBnJeb7jBr0BJdPKUwY6TgMa7HiRQok9RE0d7-ySrBDJfdys4AX5iDseRwmEjYKLB8OLHnRI6gj207m_P8o85GE763rd5RdXE3mX?type=png)](https://mermaid.live/edit#pako:eNpVkMtOwzAQRX_F8gqkFvZZIOXBsgKJrki6mNqTxsKPyB5TlST_jp0sKF6N79wzr4kLJ5EXvNfuKgbwxI5NZ1l6ZVt--ydS4guJjdGnbMAT2-9f5lrHQOiVvbDzjfUIFD3OrHp4965XGrMqNk943KpVGWT1VCfVGfWDgQkwI6iLvXMvm7leu7zZVLNpGwjD2YGXzDiryK1t_7EDWIv6dM8er25mr235XDHCQBnJeb7jBr0BJdPKUwY6TgMa7HiRQok9RE0d7-ySrBDJfdys4AX5iDseRwmEjYKLB8OLHnRI6gj207m_P8o85GE763rd5RdXE3mX)





