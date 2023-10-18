<h1 align="center">Requesting TechXchange Lab Migrations to TechZone</h1>


## Getting Started

You own an environment that was used at a TechXchange event and you would like to have migrated so others can make a reservation directly on TechZone. 


1. You need to have a Collection in order to migrate your environment. 
    -  - If you already have a existing collection on TechZone, proceed to step 2. 
       - If you don't already have one, use the following instructions. To create your own collection, see ["How to Create a Collection"](https://github.com/IBM/itz-support-public/blob/main/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/techzone-content.md#how-to-create-a-collection). Have the new Collection reviewed by mbawa@us.ibm.com before proceeding to step 2.
     
2. Reach out to TechZone support team by [opening a case](https://ibmsf.force.com/ibminternalproducts/s/createrecord/NewCase?language=en_US) or by email [techzone.help@ibm.com](techzone.help@ibm.com) to request your lab to be migrated to TechZone. Provide the following details in your request: 
    -  -  The Collection name and direct URL link to the collection.
       -  The Session ID.

3. The TechZone support team will respond back with a text file and a link to Onboarding Environment to a Collection (next section) for you to take next steps for onboarding your environment onto TechZone.


## Onboard the Environment to a Collection

The text file the TechZone support team will provide you is the following: 

> Terraform Variables Overriding
> ------------------------------
> vm_template_id
> 
> vm_template_folder
> 
> vm_map_string
> 
> vm_subnet
> 
> vm_router_ip
> 
> vm_domain
> 
Follow guidance below to ensure that you copy and paste this information correctly into the environment entry. 

1. Navigate to your collection and select edit: https://techzone.ibm.com/my/collections?StatusFilter=%5B%22Active%22%2C%22Draft%22%2C%22Pending+Approval%22%5D

    - - Scroll down the collection edit form and locate the environment section

      - Select 'Add an environment' button

![xchange-add-an-environment](/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/xchange-add-an-environment.png)

2. Provide a title for the environment and select IBM Cloud from the Infrastructure drop down list

   -  - Provide a description for the environment for users to identify what they are reserving 

      - Select 'vmware-template' from the GitOps Pattern drop down list

**NOTE: vmware-template is for VMware only**

![xchange-create-details](/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/xchange-create-details.png)

3. Under the Settings section, follow the below steps to setup this section:

    - - Select 'itzvmware; from the dropdown menu under the Account Pool field 

      - Select 'itzvmware' from the dropdown menu under the the Cloud Account field

      - Select 'Any(preferred)' from the dropdown menu under the Geo field

      - Select 'Any(preferred)' from the dropdown menu the Region field

      - Select 'Any(preferred)' from the dropdown menu the Data Center field

**NOTE: Ensure that you press the "add" button, otherwise your inputted values will not be saved!**

![xchange-add-button](/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/xchange-add-button.png)

![xchange-added](/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/xchange-added.png)

4. Under the Terraform Variables Overriding section, follow the below steps to ensure each variable is setup correctly

    -  - Adding the VMWare template ID variable:

       - Name field, select from the drop-down menu list 'vmware_template_id'

![xchange-template-id](/IBM-Technology-Zone/IBM-Technology-Zone-Runbooks/Images/xchange-template-id.png)

-  - Adding the VMWare Template Folder variable:

        - Select vm_template_folder add the New value and Click on the + icon

        - Select vm_map_string from pulldown and add the New value and Click on the + icon

        - Select vm_subnet from pulldown and add the New value and Click on the + icon

        - Select vm_router_ip from pulldown and add the New value and Click on the + icon

        - Select vm_domain  from pulldown and add the New value and Click on the + icon
-   - Click the bottom blue Save button" to save the "Terraform Variables Overriding" for the Collection