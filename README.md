# osTicket-Installation-and-Configuration

<h3> Environments and Applications used </h3>


  - _Windows 10_
  - _Azure virtual machine_
  - _Remote Desktop_
  - _Internet Information Services_



<h3> Installation Steps </h3> 


1. Created a Resource Group and Virtual Machine in Azure
2. Enabled and added World Wide Services and Enable CGI.
     - _Enabling these features will let me to create the web server for the ticketing software in later steps_.

4. Installed PHP Manager
5. Installed Rewrite Module (rewrite_amd64_en-US.msi
6. Created a file for PHP in "C".  
7. Downloaded PHP and unzip the contents into the newly created C:/PHP folder
8. Downloaded and install VC_redist.x86exe.
9. Downloaded and Installed MySQL Server
10. Registered PHP within IIS


    - _Stop and restart the server to save the changes_. 


10. Install osTicket


      - _Enabled Extentions in IIS to osTicket install requirements_.
      - _Renamed ost'config.php file_
      - _Assigned Permissions_ 
      - Continued to setup osTicket in browser_
      - Stop and restarted the server to save the changes

11. Installed HeidiSQL


      - _Created new session_
      - _Created a new data base and configured in browser_


 &ensp;  &ensp;

                       ----Images with these steps are listed in the link below ----- :
