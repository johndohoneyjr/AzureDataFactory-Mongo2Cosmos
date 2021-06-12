# AzureDataFactory-Mongo2Cosmos
Azure Data Factory: ![Alt][1]

[1]: /ADF.jpg

This is an ADF Pipeline to copy data out of MongoDB Atlas to Azure Cosmos

# Steps
This repo is ready to run from Powershell or the Azure CLI.  To create this 
* Create a Data Factory
* Select "Author and Monitor"
* Create your "Linked Services" -- this is the actual connection, 
  in this case to MongoDB and Cosmos DB (Briefcase Icon with a Wrench on it)
* Two Data sets need to be created, one for Source and another for Sink
* Finally, the Pipeline itself -- Select "Move Data".  There you add the 
  Linked Services for connecting and the Data Sets for Persistence
    
 For the purposes of learning, I triggered the run with the "Debug" option.  You
 can watch the progress in the Debug pane, or Click the Monitor Icon and see all
 triggered or Debug runs
 
 # Summmary
 Azure Data Factory is a power tool to move data around, whether inside of Azure or
 to and from Azure.  Many fine tutorial exist, but most of this is rather intuitive, and
 it is more fun to figure it out.
