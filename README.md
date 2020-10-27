Sync (Component Build) Files to Azure File Share (updated July 2019)
====================================================================

            

This script does the following:


1) Connects to an Azure Storage Account, using a Service Principal or User account that is currently logged in


2) Using a local Directory it will look at that directory, then will check the Files and Directories in a specified component build directory

E.g. *Builds/<ComponentName>/<BuildName>** *** *





3) It will create the **Component **Directory on your Azure File Share



4) It will create the Component **Build **Directory on your Azure File Share** *** *

5) It will create all Directories within the Build directory

6) It will copy all of the Files to the directories/subdirectories


7) It will Compare all new Directories created on the File Share 


8) It will Compare all new Files created on the File Share


9) It will delete any Files on the File share that are not in sync with the new version of the Build Files


10) It will delete any Directories on the File share that are not in sync with the new version of the Build Files


** **In summary it syncs a file share location to Azure File Shares. . without using SMB.


 


** **

 

 


** *** *


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
