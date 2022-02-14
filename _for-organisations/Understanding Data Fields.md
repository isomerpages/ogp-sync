---
title: Understanding Data Fields
permalink: /sync-for-employers/understanding-data-fields
description: ""
---
### **Understanding Data Fields**

#### **1. Data fields on: vaccination_status.csv**


* **uin:** Unique Identification Number (NRIC, FIN)

* **name**

* **vaccination status**
	* There are only two vaccination status:	
		* vaccinated
		* not_vaccinated
	* Vaccination status includes booster doses

* **expiry date**: Vaccination status expiry date.  The user’s vaccination status will turn not_vaccinated on this date.
		

#### **2. Data fields on: art_results.csv**

*   **uin**: Unique Identification Number (NRIC, FIN number)

* **name**

*   **test_id**
	*   Each test result submitted will be tagged to a unique test_id. The test id only serves as a way to differentiate two different tests. 
	*  Note: You may ignore this field if it is not needed.

*   **administration_mode**
	*   This can either be supervised or unsupervised
		* Supervised: taken at QTC or clinics.
		* Unsupervised: self swabs taken at individual’s convenience.

*   **produced_at**: Date when test is taken. 


*   **result**
	*   This can either be positive or negative


*  **test_type**: ART 


*   **brand**
	*   For supervised swabs:
		*   The brand of the test kit - 'BD Veritor', 'SD Biosensor', 'Standard Q', 'Abbott Pandio Covid-19 AG'.
	* For self-swabs:
		* Users submit the ART form with no test brand included. This field will be displayed as 'Others'.



#### **3. Data fields on: pcr_results.csv**

*   **uin:** Unique Identification Number (NRIC, FIN number)

*  **name**

*   **test_results**
	*   This can either be positive or negative


* **time_stamp**: Exact date and time of when this test was taken