# InterSystems-Reports-Samples

### Overview
This repository provides sample reports you can use to explore InterSystems Reports functionality. 

### Setup Instructions
1) Before you begin, make sure:
    * You have Logi Designer installed. To obtain a Logi license, contact your InterSystems account team. 
    * You have InterSystems IRIS installed, with the BI Sample data loaded. 
      Get the BI Sample data here: https://github.com/intersystems/Samples-BI
    
2) To download the files from this repository, click the green "Code" button, then "Download ZIP".
3) Unzip the folder InterSystems-Reports-Samples-Main.
4) Copy the subfolder BISamplesReports, and place it in your Logi Designer file structure under \Demo\Reports. 
<br /> Example: C:\LogiReport\Designer\Demo\Reports\BISamplesReports
5) Edit the file BISamplescat.xml and adjust JDBCConnection values to match your IRIS instance. The default values are:  
<br /> User:     SuperUser 
<br /> Password: SYS
<br /> URL:      jdbc:IRIS://localhost:51773/SAMPLES
  
      Specify a user with access to your Sample BI tables. 
<br />The URL is in the form:   jdbc:IRIS://&lt;server&gt;:&lt;Superserver port&gt;/&lt;Namespace&gt;
<br />If you change the URL, you may want to update the "Name" value for consistency. 
  
6) Try opening a report. Log on to Logi Designer, and choose "Open". In the Catalog box at the top of the pop-up, browse to the BISamplesReports folder. Then select the desired report. 


### More information

Want to learn some InterSystems Reports basics first? 
<br />Check our Learning Services website:  https://learning.intersystems.com/totara/dashboard/index.php
<br />Search for "InterSystems Reports".
