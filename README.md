# *Chatbot*
## The third task in the IoT and software development department is building an IBM Watson Assistant as follow:
- [X] Creating an IBM cloud account.
- [x] Adding Watson Assistant service.
- [x] Building a Chatbot virtual assistant.
- [x] Add the Watson Assistant to the previously built robot control panel interface.
## All of the previous Tasks are accomplished and here is a list of the previous task files which include Watson Assistant Chatbot.
|File|Description|
|----|-----------|
|`Connect.php`|Used in different files to Establish a connection with the robot_arm_control_panel database|
|`insert.php`|Insert user input values into the database depending on the used interface|
|`display.php`|Obtain recently added values into the database for both interfaces|
|`RobotBaseControlPanel-Task2.sql`|contains the database tables for the merged interfaces of the previous and current task|
|`index.html`|the main file that contains the merged interfaces structure without styling|
|`style1.css`|this file styles both the index and display files|
##
## new Notes:
- Only index.html file has been modified to include the embedded script for Watson Assistant.
- The Chatbot will provide customer services and general information about the company.
## old Notes:
- All files should be placed in the same directory including the images.
- If the 'index.html' file extenstion changed to '.php', then 'insert.php' file near the bottom line redirect header should be modified.
- The file 'hidePHP.htaccess' is used to enable writing PHP code within HTML file to retain the last submitted angle and status values which did not work.
- The file 'Jquery.js' is another attempt to insert the values into the database without refreshing using 'Jquery.ajax' also to keep range values after submition but it faild due to compiling errors.
- The new added table into the datbase name is direction with two columns for direction and timestamp that is important for retreiving recent values.
- I made sure that the interface is compatible and responsive for mobile web view through Microsoft Edge browser inspect property. 
