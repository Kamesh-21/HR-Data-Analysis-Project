# HR-Data-Analysis-Project
 
# Project Overview
I designed a Power BI dashboard with actionable insights to support the Atliq HR team in enhancing decision-making. 
The dashboard tracks key metrics such as employee data, attendance, sick leave, and work-from-home trends,
thereby automating data analysis and saving time .

## Create Visuals:

* Utilize cards to display Presence %, Work From Home %, and Sick Leave %.
* Create table visualizations for Attendance Matrix Overview, Daily Attendance Overview, and Presence %, WFH %, SL % by weekdays.
* Generate an Area Chart for the day-wise visualization of Presence %, WFH %, and Sick Leave %

## Measures
* Office Working Days =  
VAR totaldays = [count]  
VAR nonworkingday = CALCULATE([count], Final[Value] IN {"WO", "HO"})  
RETURN  
totaldays - nonworkingday  

* Present Days = CALCULATE([count], Final[Value] IN {"P", "WFH"})  

* Attendance % = DIVIDE([Present Days], [Office Working Days])  

* WFH Count = SUM(Final[WFH Count])  

* WFH % = DIVIDE([WFH Count], [Office Working Days])  

* SL Count = SUM(Final[SL Count])  

* SL % = DIVIDE([SL Count], [Office Working Days])  

* Count = COUNT(Final[Value])  

* HFWH Count = CALCULATE([Count], Final[Value] = "HWFH")  


## Dashboard Overview
![Dashboard](


