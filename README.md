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
http://www.cihanozhan.com/asp-net-web-api-hatasi-message-an-error-has-occurred/

İf you get message like this below and want to see detailed error message visit the link.
<b>*Web Api Error: "Message": "An error has occurred."</b> 
***********************************************************************************************************************************************
<b>*Xml Parser in Sql Server</b><br/>
https://www.mshowto.org/t-sql-ile-xml-parse-islemi-nasil-yapilir.html
***********************************************************************************************************************************************
<b>*When you get error to find  file in angular V11, check below solution.</b><br/>
"../node_modules/jquery/dist/jquery.js",
 
to

"./node_modules/jquery/dist/jquery.js", 
***************************************************************
<b>Error: Server was unable to process request. ---> An unsecured or incorrectly secured fault was received from the other party. See the inner FaultException for the fault code and detail. ---> An error occurred when verifying security for the message. </b>
 
Solution: This is a very obscure fault that WCF services throw. The issue is that WCF is unable to verify the security of the message that was passed to the service.

This is almost always because of a server time skew. The remote server and the client's system time must be within (typically) 10 minutes of each other. If they are not, security validation will fail.

I'd call eloqua.com and find out what their server time is, and compare that to your server time.
https://stackoverflow.com/questions/1484601/wcf-gives-an-unsecured-or-incorrectly-secured-fault-error/2031487

