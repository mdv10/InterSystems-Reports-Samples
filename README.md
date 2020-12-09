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
4) Copy the subfolder BISamplesReports, and place in your Logi Designer file structure under \Demo\Reports. 
      Example: C:\LogiReport\Designer\Demo\Reports\BISamplesReports
5) Edit the file BISamplescat.xml and adjust <JDBConnection> values to match your IRIS instance. The default values provided are:  
      <User>SuperUser</User>
      <Password>SYS</Password>
      <URL>jdbc:IRIS://localhost:51773/SAMPLES</URL>
  
      Specify a user with access to your Sample BI tables. 
      The URL is in the form: IRIS://<server>:<Superserver port>/<Namespace>. If you change the URL value, you may also want to edit the <Name> value for consistency. 
  
6) Try opening a report. Log on to Logi Designer, and choose "Open". In the Catalog box at the top of the pop-up, browse to your BISamplesReports folder. Then select the desired report. 


### More information

There are some quick introductory courses on InterSystems reports on the Learning Services website:
https://learning.intersystems.com/totara/coursecatalog/courses.ph
Search for "InterSystems Reports"
