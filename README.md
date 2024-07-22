# Streamlining SAP Processes with Azure OpenAI, Copilot Studio, and Power Platform 
SAP systems have data related to business processes while the Microsoft Graph has data related to collaboration such as emails, chats, schedules etc. To use both these forms of data together with AI would transform the business processes of many organizations and make them more efficient.

Microsoft offers powerful AI and low code development tools that are easily connected to SAP systems to develop your own intelligent copilots and bots to enhance your business processes and workflows. 

To demonstrate how seamless and easy it is to utilize AI using Microsoft AI tools, we will explore a scenario that demonstrates how SAP data along with Copilot Studio, Azure OpenAI, Microsoft Teams, and the Microsoft Power Platform can be leveraged to streamline a business process.
There are two scenarios 1 being a basic one and 2 with enahnacements to the first one inlcuding Adaptive Cards and Principal Propagation.

## Scenario Overiew and steps for scenario 1

### 1. Customer Inquiry and Complaint.
A customer contacts a salesperson with a complaint about a delayed order.

### 2. Order Investigation.
The salesperson uses a chatbot deployed on Microsoft Teams to investigate the customer's orders by leveraging AI to gain summarized insights from Outlook Emails and Teams’ messages, combined with direct data from the SAP system.

### 3. Generated Report.
After identifying the issue, the salesperson uses AI to generate a report summarizing the conversation and the cause of the delay, which is then sent to the customer via email through the chatbot interaction on Teams.

## Video Demonstration of scenario 1:
 [![Alt text](https://github.com/Azure-Samples/copilot-sap-sales-order-verification/blob/main/youtubevideo.png.png)](https://www.youtube.com/watch?v=ccVmaZKv-ns)

 
 ##  Scenario Overiew and steps for scenario 2

### 1. Finidng Replacements.
The salesperson asks the Copilot to help her look through all the materials in the SAP system to find the best replacement.
### 2. Finding Material Stock Information.
The salesperson gets a suitable replacement suggestion from Copilot and tries to access material stock information for that material. However, the salesperson is not authorized to do so as she does not have the right authorization to do so in the SAP system.
The salesperson messages her colleague who does have the authorization to check material stock information for her. The colleague checks the stock information and informs the salesperson that the material is in stock.
### Updating the Sales Order.
The salesperson now decides to update the sales order with the new material and remove the old material from the sales order.

 ## Video Demonstration of scenario 2:
 [![Alt text](https://github.com/Azure-Samples/copilot-sap-sales-order-verification/blob/main/youtubevideo.png.png)](https://youtu.be/on33yMX4je4)

## Technologies in Play

  ![Alt text](https://github.com/Azure-Samples/copilot-sap-sales-order-verification/blob/main/scenariotechincalflow.png)
  
This scenario showcases the integration of various Microsoft technologies, including:
- Copilot Studio
- Azure OpenAI
- Microsoft Teams
- Microsoft Power Platform



## Repository Contents
This repository contains Power Automate flows and a detailed PDF with steps on how to build out this scenario using these flows in Copilot Studio. 

## Getting Started
Follow the detailed steps provided in the PDF to set up the scenario in Copilot Studio and customize it according to your business needs. The PDF is named "Steps to recreate the scenario.pdf" for scenario 1 on this repo, make sure to download to PDF to access the links.
For scenario 2, the instructions are in the PDF "Steps to recrate scenario -2 . pdf" and the flows and JSONs (for the adaptive card) have a commit description of "Scenario 2 flows".


## Steps to import the Power Automate Flow in your own environment
1) Go to my flows in Power Automate and Click on import, under import click on "Import Package".

 ![Alt text](https://github.com/Azure-Samples/copilot-sap-sales-order-verification/blob/main/PowerAutomateImport.png)

 
 

2) Upload the Zip folder

 ![Alt text](https://github.com/Azure-Samples/copilot-sap-sales-order-verification/blob/main/PowerAutomateImport1.png)

 

3) Once the upload is complete, create the own respective connections and add them to the flows by clicking on "Select during import" and once that is done click on 'Import' at the bottom.


![Alt text](https://github.com/Azure-Samples/copilot-sap-sales-order-verification/blob/main/PowerAutomate2.png)

4) Since the SAP server information has not been entered in the flow, the flow wont be ready to use and you will see the image, click on 'save as new flow' and edit the information in the flow editor.

![Alt text](https://github.com/Azure-Samples/copilot-sap-sales-order-verification/blob/main/PowerautomateImport4.png)


Note : 
Once you import the Power Automate flows, you will be prompted on the Power Platform to make an SAP ERP connection.Therefore, when you attempt to recreate this flow, complete the prerequisite steps highlighted in the PDF before you try to import the flow.(The PDF is called 'Steps to recreate scenario.pdf' on this repo.) 
Each flow is named after the flow mentioned in the PDF and are the .zip folders on this repo.

## Suggestions/Contributions:
If you face issues while replicating the scenarios or have suggestions on new features/flows you would like to see, you could use [GitHub Issues](https://github.com/Azure-Samples/copilot-sap-sales-order-verification/issues) to report errors or request new features. 
