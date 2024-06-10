# Streamlining SAP Processes with Azure OpenAI, Copilot Studio, and Power Platform 
SAP systems have all the data related to business processes while the Microsoft Graph has all the data related to collaboration such as emails, chats, schedules etc. To use both these forms of data together  with AI would transform the business processes of many organizations and make them more efficient.

Microsoft offers powerful AI and low code development tools that are easily connected to SAP systems to develop your own intelligent copilots and bots to enhance your business processes and workflows. 

To demonstrate how seamless and easy it is to utilize AI using Microsoft AI tools, we will explore a scenario that demonstrates how SAP data along with Copilot Studio, Azure OpenAI, Microsoft Teams, and the Microsoft Power Platform can be leveraged to streamline a business process.

## Scenario Overiew and steps

### 1. Customer Inquiry and Complaint
A customer contacts a salesperson with a complaint about a delayed order.

### 2. Order Investigation
The salesperson uses a chatbot deployed on Microsoft Teams to investigate the customer's orders by leveraging AI to gain summarized insights from Outlook Emails and Teams’ messages, combined with direct data from the SAP system.

### 3. Generated Report
After identifying the issue, the salesperson uses AI to generate a report summarizing the conversation and the cause of the delay, which is then sent to the customer via email through the chatbot interaction.

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
Follow the detailed steps provided in the PDF to set up the scenario in Copilot Studio and customize it according to your business needs.

## Steps to import the Power Automate Flow in your own environment
1) Go to my flows in Power Automate and Click on import, under import click on "Import Package

 ![Alt text](https://github.com/Azure-Samples/copilot-sap-sales-order-verification/blob/main/PowerAutomateImport.png)

 
 

2) Upload the Zip folder

 ![Alt text](https://github.com/Azure-Samples/copilot-sap-sales-order-verification/blob/main/PowerAutomateImport1.png)

 

3) Once the upload is complete, create the own respective connections and add them to the flows by clicking on "Select during import".


![Alt text](https://github.com/Azure-Samples/copilot-sap-sales-order-verification/blob/main/PowerAutomate2.png)





Note : 
Once you import the power automate flows, you will be prompted on the Power Platform to make an SAP ERP connection.
Therefore, efore you attempt to recreate this flow, complete the prerequisite steps highlighted in the PDF.





