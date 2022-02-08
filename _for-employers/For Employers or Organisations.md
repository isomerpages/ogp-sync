---
title: For Employers or Organisations
permalink: /sync-for-organisations/employers
description: ""
---
At this phase, admins will receive reports in your email daily between 8-9AM. 

The email will contain 3 csv files :
* vaccination_status.csv
* art_results.csv
* pcr_results.csv

These CSV files will contain data of the HCWs **who have given consent** to share their data to you. It will contain test results up till **2 weeks** prior to the HCW giving the consent. 

All three CSV files will be sent in a password-protected folder. The password will be provided during onboarding.

If a HCW has not given you consent, please direct them to [go.gov.sg/sync](https://sync.covid.gov.sg/) to log in and share their data with you.

*You should share one company email address for the daily reports to be sent to.
*

### **What is in the .CSV file?**

**Data fields on [art_results.csv]:**

1.  UIN: **Unique Identification Number** (NRIC, FIN number)

2.  test_id: Each test result submitted will be tagged to a unique test_id. The test id only serves as a way to differentiate two different tests. 

*You may ignore this field if it is not needed.*

3.  administration_mode: This can either be **supervised or unsupervised**
* Supervised: taken at QTC or clinics.
* Unsupervised: self swabs taken at individual’s convenience.

4.  produced_at: Date when test is taken. 

5.  result: This can either be **positive or negative.**

6.  test_type: **ART** 

7.  brand: Supervised swabs: The brand of the test kit - **BD Veritor, SD Biosensor, Standard Q, Abbott Pandio Covid-19 AG.**

* Self-swabs: users submit the ART form with no test brand included. This field will be displayed as **Others**.

