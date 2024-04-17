# Valid Opportunity Codes to Input on Reservation Form

## Summary
This runbook will highlight what opportunity codes are valid and what systems/portals we work with to validate an opportunity code when users are making a reservation from IBM Technology Zone.

_**IMPORTANT:** We sync new IBM Sales Cloud and Gainsite opportunity codes and relationship IDs every three hours. If you input an opportunity code or relationship ID that was just created in ISC or Gainsite, then please wait approximately 24 hours for our opportunity table to update with your newly create opportunity code._

## Table of Contents

- [What is a Valid Sales Opportunity number](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/valid-opportunity-codes.md#example-of-reservation-form-and-the-opportunity-code-field)
- [IBM Sales Cloud (ISC) Opportunity codes](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/valid-opportunity-codes.md#ibm-sales-cloud-isc-opportunity-codes)
- [Gainsite Relationship ID (Customer Success Managers CRM)](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/valid-opportunity-codes.md#gainsite-relationship-id-customer-success-managers-crm)
- [Technology Expert Labs Project Work ID](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/valid-opportunity-codes.md#technology-expert-labs-project-work-id)
- [BOSS ID](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/valid-opportunity-codes.md#boss-id)
- [Invalid Opportunity Code Errors with Actionable Next Steps](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/valid-opportunity-codes.md#invalid-opportunity-code-errors-with-actionable-next-steps)

## Example of Reservation form and the opportunity code field

Selecting one of the following purposes will require a valid opportunity code: Customer Demo, Proof of Concept, Proof of Technology.

![opportunity code field](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/updatedopportunitynumberform.png)

Providing a Valid Sales Opportunity number will prompt a new field (as of November 8th, 2022) named Sales Opportunity Product.

![valid opportunity product record](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/validoppproductfield.png)

- If the Sales Opportunity number has a Opportunity product associated, then it will appear in the drop-down list. (can be one or multiple)

- If there is only one Opportunity product associated to the Sales Opportunity number, then it will be pre-filled automatically. 

Selecting the appropriate Opportunity product, in 2023, will generate a IBM Sales Cloud Technical Sales Activity automatically for the user making the reservation on Technology Zone. Not providing the Sales Opportunity number and Opportunity product will not capture an automatic Sales Activity in IBM Sales Cloud. Learn more about ISC Opportunity products by referencing the [Seismic IBM Sales Cloud - Working with products documentation](https://ibm.seismic.com/app?ContentId=0612f17d-d710-46ed-bb06-6274fff2992a#/doccenter/5477419a-9474-4c51-94af-b442e9169fab/doc/%252Fddf1dbfee9-0f74-8b63-0adf-9bc88689151d%252Fdf48a6d366-1efd-415a-ad51-7e53d37ae0f4%252Fdf3a06671b-59d5-4d9c-a7bf-7a48bc8c489a%252Flf909cf97a-278a-48c4-9899-cbc77a05ca24/grid/?anchorId=334448a9-c480-4063-9d2e-e5100bd36fe4).

## What is a Valid Sales Opportunity number? 

- **Technical Sellers -** All IBM Sales Cloud opportunity codes that are not in a "won" or "lost" sales stage are considered valid opportunity codes.

- **Customer Success Managers using Gainsite -** Relationship IDs that are open and active are considered valid opportunity codes. 

_**Note:** The TechZone Opportunity number validation service updates records every three hours. If you have just created an opportunity number or updated a status of an opportunity number from an invalid sales stage, please allow 3 to 24 hours for the record to udpate. In the mean time, reserve the environment with a purpose of self-education or test. The reservation can be updated at a later time with your opportunity number._

## IBM Sales Cloud (ISC) Opportunity codes

Reference [ISC Knowledge base](https://ibm.seismic.com/Link/Content/DCH8lALRujMky5k13vpI6KCg) for additional information on Sales Cloud. 

![ISC Opp code](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/ISC%20Opportunity%20number.png)

### Opportunity Number:

In ISC the opportunity number is visible on the URL when you are on the Opportunity record.
The field "Opportunity Legacy ID" is visible on the 'All  Opportunities' view under the Opportunities tab. It contains the ISC  opportunity number except in the following cases:

* For opportunities migrated from other systems (e.g. Atlas ), you will see the original Opportunity Number on the Opportunity Legacy ID field. 
* For opportunities owned by BPs, you will see the BP Opportunity Number (BP xxx) on the Opportunity Legacy ID field.  

You can search by opportunity number using the Global Search bar at the top of the screen. See Finding an Opportunity. However, 

* For migrated opportunities, you will not find them by the new ISC number only by the original. 
* For opportunities owned by BPs, you  will not find them by the ISC number, only by the BP xxx number.

The ISC opportunity number consists of 18 characters but most down stream applications only use the first 15 characters.


## Gainsite Relationship ID (Customer Success Managers CRM)

IBMer ONLY - Reference [Gainsite Community](https://w3.ibm.com/w3publisher/gainsight-user-community/education/csm-enablement) for more information on Gainsite CRM.

You can now use the unique ID for any relationship to search, when trying to find a relationship to associate a draft email to, using the email to timeline feature.
There are two ways to find this unique ID.
  
1. Navigate to the dashboard Search: All Companies by Name. Using the dashboard search options, find the relationship you are looking for, and copy the value showing under GSID:

![gainsite search options](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/Gainsite%20search%20options.png)

 2. You can also take the unique ID from the end of the URL when you are on the relationship 360 page:
 
 ![relationship id example](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/relationship%20id%20example.png)
 
 3. You can now use this value to search and find your specific relationship.
 
![step 3 relationship id](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/step3relationship%20id.png)


## Technology Expert Labs Project - Work ID (Software)

IBMers in Technology Expert Labs Software Brand (Automation, Data & AI, Sustainability, and Security) can provide a valid Project Work ID through their Resource Deployment Manager as a validation code on an IBM Technology Zone reservation form. Similar to how Technical Sellers provide an IBM Sales Cloud opportunity code and Customer Success Managers provide a Gainsite Relationship ID, now we support those that work with Expert Labs team with Project Work IDs that are provided by Resource Deployment Managers (RDM) or in some cases by Delivery Managers. This Project Work ID RDMs provide correspond to the code IBMers use when claiming time against (billable) client project during delivery. 

### **What is a valid Project Work ID and where to find it?**

Project Work ID which you are using to register hours in TIME@IBM you can use to get an access to IBM Technology Zone.

1. Navigate to TIME @ IBM:  [https://time.ibm.com/week](https://time.ibm.com/week)

2. Find the Claim ID in TIME and use the code assigned to your project to reserve a TechZone environment. 

![technology-expert-labs](Images/technology-expert-labs.png)

**NOTE: Clients or client projects are not billed for the use of resources on IBM TechZone by Technology Expert Labs IBMers using a Project Work ID. Additionally, be aware that existing Project Work IDs are valid as well as using an ID they are no longer working on to prepare for another client.
**

### **Additional support guidance:**
- IBMer Announcement - Reference Technology Expert Labs Environments W3 page for more information on this integration.

- For support on how to identify a Project Work ID, contact the Technology Expert Labs Team for support and guidance: [#ww-technology-expertlabs](https://ibm-techzone.slack.com/archives/C04JH4G3DSL)


## Technology Expert Labs Project - BOSS ID (Systems)

BOSS is an internal application for IBM Systems Lab Services (now known as Systems Technology Expert Labs) that facilitates running the services-based business. The two major components of the application are Opportunity Management and Financial Management. So, when BOSS ID is being referred to, it is an opportunity ID inside BOSS.

_**Note:** Only accepted BOSS IDs are active green revenue engagements with a valid WBS code. Cost recovery engagement IDs are currently not included._
### **Who has access to these BOSS IDs?**

All Systems Technology Expert Labs should have access to the tool. But only certain consultants are assigned to the specific BOSS / Opportunity ID. BOSS URL is at [https://boss.limited-use.ibm.com/](https://boss.limited-use.ibm.com/). Login using your w3id credentials for access.

### **Where to find my BOSS ID?**

Search for the opportunities within BOSS at https://boss.limited-use.ibm.com/BossOpportunity/jsp/opportunity/opportunitySearch.faces.
Only the Opportunity Manager (OM) can assign the opportunity to the specific consultants.

### **Need help finding your BOSS ID or have general questions about creating a BOSS ID?**

Consultants do not create these IDs themselves, but your Opportunity manager can get this created for you.

For additional questions or support on BOSS IDs, email lstadmin@us.ibm.com or at Slack channel `#sls-tools-support`.

## Invalid Opportunity Code Errors with Actionable Next Steps

### 'Not Found' Error: 

- As mentioned above, our system pulls updated opportunity codes every three hours. If you recently created this opportunity code or if you recently updated the status from 'Lost' to another valid sales stage, then please wait three hours for the updates to occur to pull in the record updates. 

- Additionally, check directly in IBM Sales Cloud to ensure that you have copied the exact opportunity code as shown in IBM Sales Cloud. Our validation is run against actual IBM Sales Cloud opportunity code IDs and if the ID does not exist in ISC then it will not exist when our system goes to validate against it. Please ensure to provide the code as it is shown in ISC. 

![Not Found Error](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/NotFoundISC.png)

### 'Lost' Sales Stage Error:

- IBM Sales Cloud opportunity codes that are in a 'Lost' sales stage are considered invalid for a TechZone reservation. Please provide a new opportunity code that is in a valid sales stage or if this opportunity code needs to be updated as it is now active again, proceed with updating the record in IBM Sales Cloud directly and waiting approximately 3 hours for the updates to take place on the TechZone side. 

![Lost ISC code error](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/LostStageISC.png)

### 'Won' Sales Stage Error:

- IBM Sales Cloud opportunity codes that are in a 'Won' sales stage are considered invalid for a TechZone reservation. If you have a 'won' deal and are receiving this error, please attempt the following:


 1. Please provide a new opportunity code that is in a valid sales stage or if this opportunity code needs to be updated as it is now active again, proceed with updating the record in IBM Sales Cloud directly and waiting approximately 3 hours for the updates to take place on the TechZone side. 

 2. Please check the IBM Sales Cloud (ISC) code for the list of things that were sold as part of the deal. Expert Labs and Consulting should appear there and if so, please reach out to those relevant parties (involved in the deal) for their code(s). These are the codes that typically appear once the deal is considered "won."

 3. Also in ISC, please determine if the client is a 'Signature' or 'Select one' as they should be assigned CSM's (those dedicated to signature or selected clients). They can be contacted for their Gainsight plan ID.

![Won ISC code error](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/WonStageISC.png)


### 'Request out of policy scope (Invalid opportunity product)' Error:

- Step 1: This error can typically happen if the reservation form page has been open for a long duration. Try refreshing the page to start a fresh reservation. 

- Step 2: If previous refresh did not help resolve this error, try selecting the drop down menu option for this field and selecting a different opportunity product value in the list and then select then re-select the correct one. This error might be occuring because the value was not being sent in the payload. 

![opp product error](https://github.com/IBM/itz-support-public/blob/ae3cf8ec7eb6e60aa138495b4ac01f59b1cf24f4/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/oppproducterror.png)

