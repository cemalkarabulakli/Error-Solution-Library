# Error And Solution Repo 

https://stackoverflow.com/questions/32254439/nuget-packages-are-missing
  
BEWARE - this updates packages for the entire solution not just the project.

If you have one more missing nuget package that giving your error while building your solution use following command using Nuget Command Console from Tools > Nuget Package Manager > Package Manager Console. It will reinstall your all current packages.

Update-Package –reinstall

Update:

You can pass specific project name as a parameter.

Update-Package –reinstall -ProjectName SampleApp

**********************************************************************************************************************************************************************************************************************************************************************
http://emraharal.com/2019/04/01/maxreceivedmessagesize-and-maxbuffersize-in-app-and-web-config/

The maximum message size quota for incoming messages (XXXX) has been exceeded.
To increase the quota, use the MaxReceivedMessageSize property on the appropriate binding element.
**********************************************************************************************************************************************************************************************************************************************************************
