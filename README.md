# BizTalk Scheduled Task Adapter 

The BizTalk Scheduled Task Adapter is an in-process receive adapter that executes a prescribed task on a daily, weekly or monthly schedule. The adapter is configured entirely within BizTalk, all configurations is stored within the SSODB and can be exported and imported via binding files. 
 
The schedule capabilities are similar to those available with the Windows Scheduled Task Service.
 
Four simple tasks are included:
* **XmlStringStreamProvider** - generates a BizTalk message from a configured Xml string
* **FileStreamProvider** - generates a BizTalk message from the contents of a file
* **HttpDownload** - generates a BizTalk message from data downloaded from a web site
* **SQLStreamProvider** - generates a BizTalk message from the contents of a SQL Query (similar to the old SQL adapter) - Since version 3.0
 
Custom tasks can be created. Any .NET class that implements the appropriate interface can be scheduled.
