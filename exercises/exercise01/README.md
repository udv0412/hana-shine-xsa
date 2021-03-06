Exercise 01: Getting an SAP Cloud Platform developer account and cloning SHINE code from Github
===============
## Estimated time

10 mins

## Objective
In Chapter you will create and account in SAP Cloud Platform and obtain an instance of Cloud Foundry environment


## Exercise Description
### 1. Signup for Cloud Foundry Instance
1. If you do not yet have a Cloud Foundry environment trial or enterprise account, signup for a Cloud Foundry environment trial account by following the documentation ["Get a Trial Space on the Cloud Foundry Instance"](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/76e79d62fa0149d5aa7b0698c9a33687.html)
When you are prompted to select a region select Europe(Frankfurt) AWS or US East(VA) AWS 
*Do not select US West(CA) Beta Azure as jobscheduler service required by SHINE application is not yet available in this region*
![Alt text](./images/Region.jpg "Region")

2. Once you have a Cloud Foundry instance created navigate to sub account trial 
3. Click on Spaces in the left navigation pane
4. Click on space dev 
5. Once applications are deployed it will be visible here

### 2. Clone SHINE code from Github
1.  Launch SAP Web IDE by launching URL [https://wdflbmt0749.wdf.sap.corp:53075/]( https://wdflbmt0749.wdf.sap.corp:53075/) in Google Chrome
2. Login with User: `CPL165` and Password: `Sap12345`.
![Alt text](./images/WebIDE_Login.jpg "Web IDE Login Page")
3. Launch in the URL [https://github.com/SAP/hana-shine-xsa](https://github.com/SAP/hana-shine-xsa) in a a new window. This is the GitHub Repository where you can find the code for SHINE application
4. Click on `Clone or download` button
![Alt text](./images/Github_Clone_Download.jpg "GitHub Clone Download")
5. Click on Copy Clip board icon
6. Go back to SAP Web IDE
7. Navigate to File -> Git - Clone Repository
8. In Clone Git Repository popup paste the GitHub url which was copied in step 5
9. Click on Clone button.
![Alt text](./images/Clone_Git.jpg "GitHub Clone")
10. If any error occurs during cloning skip steps below and go to Chapter 3 and follow steps to import code from zip file.
11. Click on Git Pane. 
![Alt text](./images/Git_Pane.jpg "GitHub Clone")
12. The master branch of this repository is checkout by default. TechEd exercise code is located in the branch shine-cf-teched. 
13. Click on + button 
14. A popup open  with title Create New Local branch opens
15. Select Source Branch as `origin/shine-cf-teched`.  
![Alt text](./images/Git_Change_Branch.jpg "Git Change Branch")
16. Click on Ok.
17. A pop up with title `Checkout Failed` appears
18. Click on button `Reset and Checkout`.  
![Alt text](./images/Checkout_Failed.jpg "Checkout Failed")
19. In the `Confirmation Needed ` popup click Ok button.
20. The checkout branch changes to shine-cf
![Alt text](./images/Change_Branch.jpg "Change Branch")

### 3. Import SHINE Code from zip (optional)
This step is optional and required only if Chapter 2 (Clone SHINE code from Github) fails
1.  In Web IDE navigate to File ->Import -> From File System
2. In the import popup click on Browse button.
3. Set the folder path as \\students.fair.sap.corp\Studentshare\CPL165
4. Select file shine-cf.zip
![Alt text](./images/Import_Zip_File.jpg "Import Zip File")
5. Click on Open button
6. Click on Ok button in the Import popup
7. The shine-cf zip file gets imported
![Alt text](./images/Imported_Zip.jpg "Imported Zip")

## Summary
In this exercise you have signed up for SAP Cloud Platform account, to access to Cloud Foundry Environment and downloaded/cloned the SHINE code.
