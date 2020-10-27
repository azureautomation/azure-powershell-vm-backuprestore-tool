Azure PowerShell VM Backup/Restore Tool
=======================================

            

 


 


 

 

 


 


Related Articles on LinkedIn


Disaster Recovery


 


.EXAMPLE.\AZRM-VMBackup.ps1 -csvimport -csvfile C:\temp\backupservers.csv.


EXAMPLE.\AZRM-VMBackup.ps1 -action createpolicy -vaultname myvault -vaultrg myres -policyname mypolicy


.EXAMPLE.\AZRM-VMBackup.ps1 -action createvault -vaultname myvault - myres


.EXAMPLE.\AZRM-VMBackup.ps1 -action addvmcreatevault -backupvmname myvm -backupvmrg myres -vaultname myvault -vaultrg myres


.EXAMPLE.\AZRM-VMBackup.ps1 -action restorevm -createvmname myvm -createvmrg myres -vaultrg backuprg -vaultname myvaultname


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
