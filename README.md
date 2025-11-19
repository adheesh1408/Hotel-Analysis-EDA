# Hotel Booking Analysis - Story Driven Insights 

## Executive Summary
This analysis examines 119K hotel bookings across City Hotel and Resort Hotel to understand the factors shaping guest demand, revenue, and cancellations.  
The goal was simple: identify when guests book, who brings the most value, who cancels, and which signals help the business forecast with confidence.

<img width="1261" height="628" alt="image" src="https://github.com/user-attachments/assets/c8913b4e-8589-408a-a8d0-21b2ecc526d1" />


---

## Key Questions
The analysis was guided by four core business questions:

1. When is demand strongest and how does it differ between hotel types  
2. Which customer segments generate stable revenue versus volatility  
3. Which behaviors predict cancellations  
4. What operational actions can reduce uncertainty and improve revenue  

---

## Insights Summary

### 1. Demand is seasonal and predictable  
Bookings peak in July and August. Winter months soften.  
City Hotels carry year-round volume. Resort Hotels rely heavily on summer travel.

Business interpretation: staffing, pricing and promotions require separate strategies by hotel type.

<img width="1276" height="639" alt="image" src="https://github.com/user-attachments/assets/59e80945-d8e7-4a12-b31e-48be43e05697" />


---

### 2. Customer segments behave very differently  
Online Travel Agencies drive the highest volume but also significant cancellation risk.  
Direct bookings maintain strong ADR and show far lower cancellations.

Business interpretation: volume is not enough. Growth in direct bookings would materially improve revenue stability.

<img width="544" height="327" alt="image" src="https://github.com/user-attachments/assets/d7eec8c2-da0b-4eed-b3b6-26ce52abe140" />


---

### 3. Families are the most valuable guests  
Families stay the longest at 3.9 nights and pay the highest ADR at 154+.  
They also cancel less frequently than couples.

Business interpretation: targeted packages for families would lift revenue with minimal volatility.



---

### 4. Cancellations follow a clear structure  
The overall cancellation rate is 37 percent. Risk increases sharply with lead time.  
Short lead times cancel at 9 percent. Long lead times cancel at more than 55 percent.  
Group bookings and certain OTA channels show heavy volatility.

Business interpretation: long term reservations require deposits or stronger policy controls to protect revenue.

<img width="1262" height="855" alt="image" src="https://github.com/user-attachments/assets/206bf822-1849-4ff5-a2fe-36bba865e6da" />

---

### 5. Guest commitment signals are highly predictive  
Several behaviors show extremely strong commitment:

- Guests with 3 to 5 special requests cancel at very low rates  
- Guests who require parking do not cancel in this dataset  
- Repeated guests cancel at 14 percent  
- Bookings with room upgrades or mismatches cancel at only 5 percent  

Business interpretation: these signals can guide overbooking decisions, upgrade prioritization and forecasting accuracy.

<img width="581" height="246" alt="image" src="https://github.com/user-attachments/assets/fe2ca1a2-244e-433e-97f8-74b2b22f9f1a" />
<img width="1244" height="629" alt="image" src="https://github.com/user-attachments/assets/fb32c41a-5da9-42e4-b139-83b0e0550ed7" />


---

## Recommendations

### 1. Grow the direct booking channel  
The cancellation rate of direct bookings is two and a half times lower than OTA channels.  
Loyalty benefits, member pricing or direct-only perks would support this.

### 2. Apply lead-time based policy rules  
Bookings made far in advance cancel at extremely high rates.  
Partial deposits or flexible but structured terms would reduce risk.

### 3. Prioritize family-focused offerings  
This segment demonstrates high ADR, long stays and stronger reliability.

### 4. Use commitment indicators operationally  
Special requests, parking and previous stay history can be used to inform upgrades, forecasting and overbooking decisions.

### 5. Investigate the non-refund deposit pipeline  
A cancellation rate of 99 percent signals a data issue or broken business rule.

---

## Tech Stack
- Python  
- Pandas and NumPy  
- Seaborn and Matplotlib  
- Jupyter Notebook  

---

## Skills Demonstrated
- Data cleaning and preprocessing  
- Feature engineering  
- Exploratory data analysis  
- Behavioral pattern identification  
- KPI analysis by segment  
- Business storytelling and insight communication  
- Revenue and operations-focused interpretation  

---

## Future Extensions
- Cancellation prediction model  
- Dynamic ADR optimization by segment and season  
- Guest lifetime value modeling  
- Demand forecasting for staffing and inventory planning


## Note
[Dataset Link](https://www.kaggle.com/datasets/ahmedsafwatgb20/hotel-bookingscsv)


By Adheesh G.

