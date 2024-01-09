# **ITSM - ML**

---------
## **Business Case-Study**

ABC Tech is an mid-size organisation operation in IT-enabled business
segment over a decade. On an average ABC Tech receives 22-25k IT
incidents/tickets , which were handled to best practice ITIL framework
with incident management , problem management, change management
and configuration management processes. These ITIL practices attained
matured process level and a recent audit confirmed that further
improvement initiatives may not yield return of investment.
ABC Tech management is looking for ways to improve the incident
management process as recent customer survey results shows that
incident management is rated as poor.

Machine learning looks prospective to improve ITSM processes through
prediction and automation. They came up with key areas, where ML can
help ITSM process in ABC Tech.

**1)** Predicting High Priority Tickets so that they can take preventive measures or fix the problem before it surfaces.

**2)** Forecast the incident volume monthwise and quarterwise. So that they can be better prepared with resources and technology planning.

**3)** Auto tag the tickets with right priorities and right departments so
that reassigning and related delay can be reduced.

--------
## **Dataset Description**

This Dataset contain Total of 24 features and 1 Target(Priority)

1) CI_Name: Represents the Configuration Item (CI) Name, which is an element of
the IT infrastructure that is managed in the context of IT Service Management.

2) CI_Cat: Denotes the category of the Configuration Item.

3) CI_Subcat: Specifies the subcategory of the Configuration Item. It provides more detailed information about the type of CI.

4) WBS: Stands for Work Breakdown Structure. It is a project management tool that represents a hierarchical decomposition of the total scope of work to be carried out by the project team.

5) Incident_ID: Unique identifier for each incident. It is a reference number or code assigned to each reported incident.

6) Status: Represents the current status of the incident.

7) Impact: Indicates the impact of the incident on the business or IT services.

8) Urgency: Reflects the urgency of addressing the incident.

9) Priority: Represents the overall priority assigned to the incident, which is often a combination of impact and urgency.

10) number_cnt: It's not explicitly described, but it may be a numerical count  associated with something in the dataset.

11) Category: Denotes the category of the incident, providing additional classification information.

12) KB_number: May refer to a Knowledge Base (KB) article number. Knowledge base articles are often used for documenting solutions to common issues.

13) Alert_Status: Represents the status of any alerts associated with the incident.

14) No_of_Reassignments: Indicates the number of times the incident has been reassigned or transferred to different support personnel or groups.

15) Open_Time: Represents the timestamp when the incident was initially reported or opened.

16) Reopen_Time: Timestamp indicating when the incident was reopened, if applicable.

17) Resolved_Time: Timestamp indicating when the incident was resolved or fixed.

18) Close_Time: Timestamp indicating when the incident was closed or marked as completed.

19) Handle_Time_hrs: Represents the time taken to handle or resolve the incident, often measured in hours.

20) Closure_Code: Denotes the code or reason for closing the incident.

21) No_of_Related_Interactions: Indicates the number of related interactions associated with the incident.

22) Related_Interaction: Information about the related interactions associated with the incident.

23) No_of_Related_Incidents: Represents the number of incidents related to the current incident.

24) No_of_Related_Changes: Indicates the number of related changes associated   with the incident.

25) Related_Change: Information about the related changes associated with the incident.


----------
### Features with respect to Priority

![image](https://github.com/TrushalPatel0/ITSM_ML/assets/144200919/eeb0e061-7a52-45c4-9ba6-e1e9031f0abb)

![image](https://github.com/TrushalPatel0/ITSM_ML/assets/144200919/b26179f0-a33e-4672-8fbf-ed6e4ac28b5a)

![image](https://github.com/TrushalPatel0/ITSM_ML/assets/144200919/bdbe81fe-dd52-4ea8-9602-25c1515e9e88)

![image](https://github.com/TrushalPatel0/ITSM_ML/assets/144200919/147666ec-6b94-49cf-8937-4850096099ef)

------
## **Model Creation**

**1) Decision Tree**

**2) Random Forest**

**3) Gradient Boosting**

-------
## **Model Comparison Report (Predicting High Priority Tickets)**

<img width="548" alt="image" src="https://github.com/TrushalPatel0/ITSM_ML/assets/144200919/e7c86621-d3bb-4835-bfba-993cb447dc5b">

--------

![image](https://github.com/TrushalPatel0/ITSM_ML/assets/144200919/8baf8610-27fc-48dc-bb03-c3dd05e4b872)

-------


