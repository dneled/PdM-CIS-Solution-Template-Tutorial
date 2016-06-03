Predictive Maintenance for Aerospace Solution Template ReadMe

The contents of this directory contain important components related to this Solution Template that you have replicated in your subscription.  


**** Sample Data Source ****

The directory DataGenerator contains the application that is used to populate the Azure Event Hub with sample data. Event hub is the entry point for data ingestion for the solution template. 

The application can be found at \DataGenerator\Generator.exe

The application has been pre-configured with the Azure Event Hub details at the deployment of the solution template to your subscription. 

To move data to the Azure Event Hub, launch the application and follow the menu selections to start (Press 0) the data ingestion process.

To stop data flowing to Event Hub use the menu option to stop the process (Press 1) or simply close the application. At any point of time you can check the status (Press 3) on the amount of data sent to Event Hub.

** NOTE: The generator will submit data to the Azure Event Hub, and hydrate the data pipeline, only when it is actively running. If the computer running the application shuts down or loses network connectivity the 
Generator.exe application will need to be restarted.


**** Power BI Desktop Template File ****

The directory Power BI Template contains the Power BI Designer file which will help you recreate the Power BI dashboard to visualize data from this solution template.      

The designer file can be found at \Power BI Template\PredictiveMaintenanceAerospace.pbix

Please read the instructions on this page http://go.microsoft.com/fwlink/?LinkId=699446&clcid=0x409 to recreate the Power BI dashboard.
