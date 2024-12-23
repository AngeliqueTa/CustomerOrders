## Application Details
|               |
| ------------- |
|**Generation Date and Time**<br>Tue Dec 17 2024 13:50:52 GMT+0000 (Coordinated Universal Time)|
|**App Generator**<br>@sap/generator-fiori-elements|
|**App Generator Version**<br>1.15.7|
|**Generation Platform**<br>SAP Business Application Studio|
|**Template Used**<br>List Report Page V2|
|**Service Type**<br>README_LABEL_DATASOURCE_TYPE_businessHub|
|**Service URL**<br>https://sandbox.api.sap.com/sap/c4c/odata/v1/c4codataapi|
|**Module Name**<br>customerorders|
|**Application Title**<br>Customer Orders|
|**Namespace**<br>customerorders|
|**UI5 Theme**<br>sap_horizon|
|**UI5 Version**<br>1.131.1|
|**Enable Code Assist Libraries**<br>False|
|**Enable TypeScript**<br>False|
|**Add Eslint configuration**<br>False|
|**Main Entity**<br>CustomerOrderCollection|
|**Navigation Entity**<br>CustomerOrderItem|

## customerorders

Sales Orders for Customers Collection App. You will need to link this app with the Business Accelarator Hub. 
The API key needs to change in the .env file with a new API key. 
Find the Odata v2 SalesOrders API in the BA Hub and copy that key. 

Deployment are spesific to either Workplace, or other repository that is not defined. 

### Starting the generated app

-   This app has been generated using the SAP Fiori tools - App Generator, as part of the SAP Fiori tools suite.  In order to launch the generated app, simply run the following from the generated app root folder:

```
    npm start
```

- It is always a good idea to build the app. This will notify you whether any files are corrupted:

```
    npm run build
```

- It is also possible to run the application using mock data that reflects the OData Service URL supplied during application generation.  In order to run the application with Mock Data, run the following from the generated app root folder:

```
    npm run start-mock
```

#### Pre-requisites:

1. Active NodeJS LTS (Long Term Support) version and associated supported NPM version.  (See https://nodejs.org)
2. SAP Fiori Tools Extensions installed
3. SAP Fiori environment set up in your development environment
