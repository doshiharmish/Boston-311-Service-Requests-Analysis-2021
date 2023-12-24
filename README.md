# Boston 311 Service Requests Analysis (2021)
## Introduction
The 3-1-1 service is a pivotal system adopted by numerous communities across the United States of America and Canada, serving as a dedicated channel for non-emergency municipal assistance. It offers residents access to essential services while diverting general inquiries and non-urgent issues away from the emergency hotline, 9-1-1.<br><br>
This comprehensive report delves into the extensive statistics of 3-1-1 service requests made by Boston residents in 2021. The primary focus lies in analyzing prevalent complaint categories, geographical distribution, and the government's handling of these requests.<br><br>
Each entry in the dataset corresponds to a service request initiated by a resident or staff member via various modes of communication. With 29 distinct parameters, including creation date, status, subject, department, location, and source, the dataset encapsulates multifaceted details for each request. An observation reveals a centralized pool where requests congregate before being directed to department-specific queues, predicated on request types and their respective locations.

## Objective
The main objectives pursued in this analysis:
- Identify the most prevalent source of service requests.
- Determine the daily influx of requests in Boston and categorize them.
- Assess the department receiving the highest requests and analyze their response times.
- Uncover the most frequent request types and their commonly reported locations.

## Data Collection
### 311 Service Requests Dataset:
Origin: <a href = 'https://data.boston.gov/dataset/311-service-requests/resource/f53ebccd-bc61-49f9-83db-625f209c95f5'> Analyse Boston </a><br>
Size: 125 MB<br>
Rows: 273,951, Columns: 29<br>
### Boston Neighborhood Geographical Data:
Rows: 26, Columns: 7

## Data Cleaning and Preprocessing
- Removed unnecessary columns to optimize memory usage.
- Corrected data types and handled NULL values.
- Converted all data to lowercase for uniformity.
- Introduced new columns to facilitate date and time analysis.

## Data Analysis

### **1. Preferred Mode of Request:**
Citizen Connect App (BOS:311 App) emerged as the most-used channel for non-emergency requests.

![image](https://github.com/doshiharmish/311-ServiceRequest-Boston-2021-/assets/16878994/5fef5a09-cc6a-45c3-9941-ef468c0d8a1b)


### **2. Total Requests in 2021:**
A total of 2,73,951 requests were received, with 89.3% successfully closed and 2.7% overdue, indicating an active response from the city council.

![image](https://github.com/doshiharmish/311-ServiceRequest-Boston-2021-/assets/16878994/45533771-9e73-4ea2-abfb-7259e6d0149c)


### **3. Monthly Requests Analysis:**
A steady rise in requests throughout the year, peaking in September, followed by a decline starting in October.


![image](https://github.com/doshiharmish/311-ServiceRequest-Boston-2021-/assets/16878994/d1ab844c-4d84-48e7-a8ad-68225f571268)


### **4. Department-wise Requests Inflow:**
The department receiving the most requests is Public Works, handling 127,636 requests. Their services encompass fundamental community needs, resulting in high demand. Conversely, the Boston Housing Authority had the fewest requests, totaling only 223.

![image](https://github.com/doshiharmish/311-ServiceRequest-Boston-2021-/assets/16878994/a0a9c1a8-99f4-4b6a-9939-9fa5e99ee760)


<image/table to be added>

### **5. Average Turnaround Time of Requests:**
The average turnaround time for addressing requests is 7 days and 13 hours. Due to fewer requests, the Department of Animal Control exhibits the shortest turnaround time, requiring approximately 1 day and 6 hours. In contrast, Property Management experiences the longest turnaround time, averaging 54 days and 21 hours. The Public Works Department, despite handling the most requests, maintains a relatively swift turnaround of 3 days and 2 hours.

![image](https://github.com/doshiharmish/311-ServiceRequest-Boston-2021-/assets/16878994/1748a753-1750-42d0-b338-5d0894ae3f2f)

### **6. Top Service Request Reasons**:
This dataset reports a diverse range of 45 reasons for service requests. The pie chart below highlights the top 5 reasons for service requests. Enforcement and Abandoned Vehicles: Represent the most common reason, accounting for 26% of the total service requests.

![image](https://github.com/doshiharmish/311-ServiceRequest-Boston-2021-/assets/16878994/3e3f0cc1-8d51-4799-98a9-7580a787d037)


### **7. In-depth Analysis of Top Request - Traffic Violation**:
Traffic violations emerge as the most commonly reported type of request. The breakdown reveals two categories:

![image](https://github.com/doshiharmish/311-ServiceRequest-Boston-2021-/assets/16878994/75ddb7f2-5290-405a-9b0d-298cd8c6df1a)


#### **7.1 Parking Enforcement** 
Constituting 92% of violations, encompassing ticket issuance for parking rule violations. A specific neighborhood-wise breakdown shows South Boston as the district with the highest violations due to its large, bustling establishments such as restaurants, bars, and hotels.

![image](https://github.com/doshiharmish/311-ServiceRequest-Boston-2021-/assets/16878994/0902b3bc-5aee-4e3c-b429-1f8ca989c0c4)

#### **7.2 Abandoned Vehicles** 
Comprising 8% of violations, the city has the legal authority to seize vehicles left unattended on roadways for more than 72 hours. Dorchester recorded 1,228 reports of abandoned vehicles, generating $1.2 million in revenue for Boston.

![image](https://github.com/doshiharmish/311-ServiceRequest-Boston-2021-/assets/16878994/859909bf-010d-4f89-a4b0-e630edb56eff)

## Conclusion
This analysis unraveled significant insights into Boston's 311 service requests. Key revelations include the most reported request types, preferred modes of request, and department-wise response times.
