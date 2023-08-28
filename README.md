Get Status of Azure V2 Vm
=========================

            

DESCRIPTION


This Graphical PowerShell runbook gets the PowerState status of a V2 VM.  The runbook returns either 'running' or 'stopped'.  You can run this runbook by itself or use it as part of another runbook.



REQUIRED


- VmName input parameter.  Specifiy the name of the V2 VM.


- ResourceGroupName input parameter.  Specify the name of the resource group for the VM.


- An Automation Account system assigned managed identity.  This is required only if LoginToAzure is $true.


OPTIONAL


- LoginToAzure input parameter.  Default is $true.  Set the value to $false to bypass the authentication.





NOTES


- This runbook can be used either by itself or called from another runbook.  The input parameter LoginToAzure allows the user to decide if authentication to azure is needed or not.  When this runbook is called from another runbook that has already authenticated with Azure, then this runbook does not need to repeat the work.


AUTHOR


Azure Automation Team 


LAST EDIT


2023-08-28


 


 ![Image](https://github.com/Bonnie-Chen95/get-status-of-azure-v2-vm/blob/master/GetAzureV2VmStatus_new.png)

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
