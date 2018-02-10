# scp-ml-imageclassifier
Demo application to show SCP ML Image Classifier service

## How to use this demo

[Sign up for a free trial account on the SAP Cloud Platform.](https://account.hanatrial.ondemand.com/#/home/welcome)

Get your API key from [SAP API Business Hub](https://api.sap.com/shell/discover/contentpackage/SAPLeonardoMLFunctionalServices/api/image_classification_api).

Download a copy of [sapui5ml-api.destination](sapui5ml-api.destination) and import the destination to your [SCP Cockpit](https://account.hanatrial.ondemand.com/cockpit).

Clone this repo into your WebIDE.

Insert your API key into [scp_ml_api.json](webapp/model/scp_ml_api.json) in folder `webapp/model/`.

Run `index.html` from within WebIDE. Make sure that when running the application, the URL is `index.html` and not the `extended_runnable_file.html`. And if not replace `extended_runnable_file.html` by `index.html`.

Click the "Upload Picture" button at the bottom of the screen.

Choose your picture and wait for the service to classify it.

The image you uploaded is shown on the top of the page followed by a table which holds the results of image classifier service.

## Screenshot

![Application UI](https://i.imgur.com/g4vaF3F.png "Application screenshot")

---
Copyright © 2018 Nils Lutz