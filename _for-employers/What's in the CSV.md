---
title: What's in the CSV
permalink: /for-employers/whatsinthecsv
description: ""
---
### **What is in the .CSV file?**

#### **1. Data fields on: vaccination_status.csv**


* UIN: **Unique Identification Number** (NRIC, FIN number)


* Vaccination status: There are only two vaccination status:	
	* vaccinated
	* not_vaccinated



#### **2. Data fields on: art_results.csv**

*   UIN: **Unique Identification Number** (NRIC, FIN number)


*   test_id: Each test result submitted will be tagged to a unique test_id. The test id only serves as a way to differentiate two different tests. 

*You may ignore this field if it is not needed.*

*   administration_mode: This can either be **supervised or unsupervised**
	* Supervised: taken at QTC or clinics.
	* Unsupervised: self swabs taken at individual’s convenience.

*   produced_at: Date when test is taken. 


*   result: This can either be **positive or negative.**


*   test_type: **ART** 


*   brand: Supervised swabs: The brand of the test kit - **BD Veritor, SD Biosensor, Standard Q, Abbott Pandio Covid-19 AG.**
	* Self-swabs: users submit the ART form with no test brand included. This field will be displayed as **Others**.



#### **3. Data fields on: pcr_results.csv**

*   UIN: **Unique Identification Number** (NRIC, FIN number)


*   test_results: Either **positive or negative**


* time_stamp: Exact **date and time** of when this test was taken