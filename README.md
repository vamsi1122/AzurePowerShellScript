# AzurePowerShellScript To Find Admins in AzureAd Tenant
We will set couple variables to print all the Admins in AzureAD using PowerShell.

In the first variable($Roles). I will be returning back all the roles with admin rights.
In the Second variable ($UserRoles). I will use this variable to go in to each roles to print each member displaying Username, UsersEMailaddress and role.

Errors: I had hard time using Windows PowerShell, I have used Azure Portal PowerShell to execute the variables. PLease also use Offline packages to install the modules incase if you would like to use the WindowsPowerShell.


I initally started from the below link and Used the scipt in here to have more granualar results.

https://blogs.msdn.microsoft.com/friis/2018/04/20/how-to-find-the-global-admin-for-your-azure-ad-tenant/
