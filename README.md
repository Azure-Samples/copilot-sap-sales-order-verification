# Streamlining SAP Processes with Azure OpenAI, Copilot Studio, and Power Platform 
SAP systems have data related to business processes while the Microsoft Graph has data related to collaboration such as emails, chats, schedules etc. To use both these forms of data together with AI would transform the business processes of many organizations and make them more efficient.

Microsoft offers powerful AI and low code development tools that are easily connected to SAP systems to develop your own intelligent copilots and bots to enhance your business processes and workflows. 

To demonstrate how seamless and easy it is to utilize AI using Microsoft AI tools, we will explore a scenario that demonstrates how SAP data along with Copilot Studio, Azure OpenAI, Microsoft Teams, and the Microsoft Power Platform can be leveraged to streamline a business process.

## Scenario Overiew and steps

### 1. Customer Inquiry and Complaint
A customer contacts a salesperson with a complaint about a delayed order.

### 2. Order Investigation
The salesperson uses a chatbot deployed on Microsoft Teams to investigate the customer's orders by leveraging AI to gain summarized insights from Outlook Emails and Teams’ messages, combined with direct data from the SAP system.

### 3. Generated Report
After identifying the issue, the salesperson uses AI to generate a report summarizing the conversation and the cause of the delay, which is then sent to the customer via email through the chatbot interaction on Teams.

## Video Demonstration
 [![Alt text](https://github.com/Azure-Samples/copilot-sap-sales-order-verification/blob/main/youtubevideo.png.png)](https://www.youtube.com/watch?v=ccVmaZKv-ns)

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
Follow the detailed steps provided in the PDF to set up the scenario in Copilot Studio and customize it according to your business needs. The PDF is named "Steps to recreate the scenario.pdf" on this repo, make sure to download to PDF to access the links.

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
