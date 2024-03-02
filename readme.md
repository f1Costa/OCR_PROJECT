# OCR Laboratory with Azure Cognitive Services
This repository contains the resources and source code for a practical Optical Character Recognition (OCR) laboratory using Azure Cognitive Services. OCR is a powerful technique for extracting text from images or scanned documents, and Azure Cognitive Services provide a robust and scalable solution for implementing this functionality in your applications.

__Objective__

The objective of this laboratory is to demonstrate how to use Azure Cognitive Services to perform OCR on images and extract the corresponding text. By following this guide, you will learn how to set up a development environment, integrate Microsoft's cognitive services into your application, and efficiently perform OCR on images.

__Prerequisites__

Active Microsoft Azure account
Access to the Azure portal
Basic knowledge of application development
Environment Setup
Create a Cognitive Service Instance: In the Azure portal, create a Cognitive Service instance. Select the service type as "Vision" to enable OCR capabilities.

Get Key and URL: After creating the Cognitive Service instance, obtain the key and endpoint URL. These will be needed to authenticate and access the services.

__Install Dependencies:__ 

Make sure you have the necessary dependencies installed in your development environment. You may need to install specific libraries or SDKs depending on the programming language you are using.

__Running the Laboratory__

Integrate the SDK: Use the SDK provided by Microsoft to integrate Azure Cognitive Services into your application. Import the necessary libraries and configure authentication using the key and endpoint URL obtained earlier.

Send Images for OCR: Send the images you want to process to the OCR service. Make sure to choose the appropriate method for sending the image data, whether via URL or file upload.

Process Results: After sending the image, the service will return the extracted text. Handle these results as necessary in your application.

Manage Errors and Exceptions: Implement proper error handling to deal with situations such as connection failures, low-quality images, or authentication issues.

__Additional Resources__

Azure Cognitive Services Documentation:

https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/concept-ocr


![alt text](OUTPUT_IM_1.png)

![alt text](image.png)
