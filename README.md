# Project: IP Management Application <br />

There are many PC in the factory which makes the IP management difficult. So I made a small application to better manage the IP. The following paragraph will demonstrate the function of this application <br />


###  Fresh Start and Create DataBase


<p align="center">
<img src="/Image/1_Create.gif" height="80%" width="80%"> 
</p>  

<p align="center">
GIF 1. Fresh start and create database. 
</p>

1.	Start up screen: If this is the first time you use this application, there is the “First Time” button to set up the database connection. If you’ve set up the connection before, the application will malfunction this button. The application will detect the text file in your C drive (C:\\IPWizard\info\databaseInfo.txt) and make connection based on the information you provided previously. <br />

<p align="center">
<img src="/Image/ReadmeImage/1_Login.JPG" height="90%" width="90%">   
</p>

<p align="center">
Image 1. Log In Page
</p>

2.	First Time: Key in the IP address, login ID, password which database you want to connect with. If there is no database which store the ip data, then just simply click the “add new database” and new account ID and password for the new IP database. <br />

<p align="center">
<img src="/Image/ReadmeImage/2_Setup.JPG" height="90%" width="90%">   
</p>

<p align="center">
Image 2. Connect to server and use exist database and table.
</p>

<p align="center">
<img src="/Image/ReadmeImage/3_Setup.JPG" height="90%" width="90%">   
</p>

<p align="center">
Image 3. Connect to server and created database and table.
</p>


3.	Main Menu: After you login or set up the first time, you will enter a main menu which displaying all the information of each working station showing in image 5 or showing nothing in image 4 if you haven’t key in any information yet. <br />

<p align="center">
<img src="/Image/ReadmeImage/4_Main.JPG" height="90%" width="90%">   
</p>

<p align="center">
Image 4. Main menu with fresh start.
</p>

<p align="center">
<img src="/Image/ReadmeImage/5_Main.JPG" height="90%" width="90%">   
</p>

<p align="center">
Image 4. Main menu with exist database and table.
</p>

### Add Data to DataBase <br />

<p align="center">
<img src="/Image/2_AddEdit.gif" height="80%" width="80%"> 
</p>  

<p align="center">
GIF 2. Add some data to database. 
</p>

4.	Setting: In the setting button, you can add user or add department group. <br />

<p align="center">
<img src="/Image/ReadmeImage/6_Setting.JPG" height="90%" width="90%">   
</p>

<p align="center">
Image 5. Setup user or Department / Group.
</p>

5.	Add Department Group: You can add new department or group by clicking the Add button showing in image 7. You can also edit or delete certain department or group by clicking the row in the data table and click Edit or Delete button. The data will be automatically appears in the text box for you to edit. Simply click Confirm button to save the data. Only the department key in here can the main menu and edit menu find the department name. Department’s Flag will be assigned as “D”. 172’s Flag will be assigned G while 192’s Flag will be assigned F.  <br />

<p align="center">
<img src="/Image/ReadmeImage/7_DepartmentGroup.JPG" height="90%" width="90%">   
</p>

<p align="center">
Image 6. Setup Department or Group.
</p>

### Add PC and IP to Database <br />

<p align="center">
<img src="/Image/3_AddConflict.gif" height="80%" width="80%"> 
</p>  

<p align="center">
GIF 3. Add PC and IP data to table. 
</p>

6.	Add: You can add new PC by clicking the Add button in Main Menu (image 5). When you key in the IP, the application will automatically show Good sign if the IP address is not in the database or Used sign otherwise. You can click Ping button to Ping the address. Good sign means the ping is failed (no terminal under this IP address). You can click Get button to get an unused IP after entering the second and the third part of IP address and the application will fill in the fourth part of IP address for you. Some working station requires 2 IP address due to two networking cards. Usually, IT set the fourth part of IP the same in both 172 and 192, then you can simply click the “Similar” checkbox and then click “Get” button for 192. Some working station allows the used IP for 192 due to no connection to the Ethernet, so you can click the “Allow Duplicate” button to avoid application blockage for duplicate IP address appearing in the database.  Click “Confirm” to save the data. <br />

<p align="center">
<img src="/Image/ReadmeImage/8_Add.JPG" height="90%" width="90%">   
</p>

<p align="center">
Image 7. Add PC, IP and other information.
</p>


### Edit PC and IP to Database <br />

<p align="center">
<img src="/Image/4_EditConflict.gif" height="80%" width="80%"> 
</p>  

<p align="center">
GIF 4. Edit PC, IP and other data to in the selected row. 
</p>

7.	Edit: You can edit the pc information by clicking on the working station you want to modify and click Edit button in the main menu. The original data will show in the top of the screen and displaying in the text box for you to modify. Click “Confirm Edit” when you finish editing and save data.

<p align="center">
<img src="/Image/ReadmeImage/9_Edit.JPG" height="90%" width="90%">   
</p>

<p align="center">
Image 8. Edit PC, IP and other information.
</p>

