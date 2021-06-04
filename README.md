# MySQL database scripts for FDM IRC Pod

<br/>

<div align="center">
  <img src="https://blogs.kent.ac.uk/soc-employability/files/2018/08/fdm-logos.png"/>
</div>

## Related front-end GitLab Project
https://git.fdmgroup.com/irc-sfrt/trading_data_generator_frontend

## Related back-end GitLab Project
https://git.fdmgroup.com/irc-sfrt/trading_data-generator-backend

## Current state (stable - unrefactored)
Creates and inserts data into Margin Lending tables and data tables

## Useful resources
* How to set up MySQL (Server and Workbench)
  - https://www.youtube.com/watch?v=u96rVINbAUI
* MySQL introduction
  - https://www.tutorialspoint.com/mysql/mysql-introduction.htm

<br/>

## Setup
<b> To get the database running locally: </b>

<b> Windows Installation Using MySQL Installer: </b>
* The MySQL Installer application can install, upgrade, and manage most MySQL products, including MySQL Workbench.
  The general MySQL Installer download is available at 
  - https://dev.mysql.com/downloads/windows/installer/. 

<b> Installation Using the Windows MSI Installer Package: </b>
* The standalone download is available at: 
  - https://dev.mysql.com/downloads/workbench/.

<b> To install MySQL Workbench, Windows: </b>

* From an account with Administrator or Power User privileges, right-click the MSI file and select the Install 
  item from the pop-up menu, or double-click the file.

* In the Setup Type window you may choose a Complete or Custom installation. 
  To use all features of MySQL Workbench choose the Complete option.

* Unless you choose otherwise, MySQL Workbench is installed in C:\%PROGRAMFILES%\MySQL\MySQL Workbench 8.0 edition_type\, 
  where %PROGRAMFILES% is the default directory for programs for your locale. The %PROGRAMFILES% directory is defined as C:\Program Files\ on most systems.

<b> To install MySQL Workbench, Mac</b>

* To install MySQL Workbench on macOS, download the file. Double-click the downloaded file. 
  You will be presented with the installation window shown in the figure that follows.

* Downloads are available at: 
  - https://dev.mysql.com/downloads/workbench/.


## Connecting to a database

* Open MySQL Workbench.

* Click New Connection towards the bottom left of MySQL Workbench.

* In the “Set up a New Connection Dialogue” box, Type your Database connection credentials. The credentials will be like the following:
	Connection Name: You can name this whatever you like.
	Connection Method: Standard (TCP/IP).
	Hostname: You can use your domain our your cPanel IP address.
	Port: 3306
	Username: Your cPanel username or the user you created for the database.
	Password: cPanel password or the password for the database user that was created.
	Default Schema: This can be left blank.

* Click Test Connection.

* Type your password and click the “Save Password in Vault” check box.

* Click Ok.

* MySQL Workbench should say “Connection parameters are correct“. Click Ok.

* Click Ok again to accept the connection settings.

* Now under the SQL Development section you will see your connection listed in the Open Connection to Start Querying box. Click your newly created account.

* Now you will see the databases list in the area on the left.


## Debugging

<b> When gathering information for error-debugging analysis: </b>

* After clicking the yellow lighing symbol to run:
* Check the output at the bottom of the screen.
* An error message will show with a red x advising of what may have gone wrong.
* Use the error code provided to search online for additional information.


