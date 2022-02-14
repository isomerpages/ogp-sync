---
title: Understanding Daily Reports
permalink: /sync-for-employers/understanding-data-fields
description: ""
---

### **Understanding Daily Reports**

#### **1. Vaccination Status report**

This will contain individuals':

* **UIN:** Unique Identification Number (NRIC, FIN)

* **Name**

* **Vaccination Status:** This will be either:
		* vaccinated
		* not_vaccinated
Note: Vaccination status includes booster doses

* **Expiry Date**: Vaccination status expiry date. The individual’s vaccination status will change to not_vaccinated on this date. **Individuals who have taken a booster dose will not have a vaccination status expiry date.**
		

#### **2. ART Results report**
This will contain individuals':

* **UIN:** Unique Identification Number (NRIC, FIN)

* **Name**

*   **Test_ID:** Each test result submitted will have a unique test_id, to help identify different tests taken by the same individual. 

*   **Administration_Mode:** This will be either:
		* Supervised: Tests taken at QTCs or clinics.
		* Unsupervised: Self-swabs done by the individual themselves.


*   **Produced_At**: Date when the test was taken. 

*   **Result:** This will be either be **Positive** or **Negative**.

*  **Test_Type**: This column will always show 'ART' 

*   **Brand:** For supervised swabs, the brand of the test kit will be one of:
		'BD Veritor', 'SD Biosensor', 'Standard Q', 'Abbott Panbio Covid-19 AG'
	For self-swab tests submitted on Sync, the brand name is not recorded, and will show as 'Others'.



#### **3. PCR Results report**
This will contain individuals':

* **UIN:** Unique Identification Number (NRIC, FIN)

* **Name**

*   **Test_Results:**
	This will be either **Positive** or **Negative**.

* **Time_Stamp**: Exact date and time of when the test was taken.