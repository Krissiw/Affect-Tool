# student-affect-tool
Student Affect Tool
Welcome To The Student Tool Setup.

***************************************************
* Database Setup                                  *
***************************************************

1) Inside the Config Directory, there is a file called connect.inc.php
2) Open the file and you will find: $host , $userMS ,  $passwordMS , $database
3) Please note this file will contains personal information to the Database, keep it safe on the server.
    Information required to be completed by user:
    $host -> The name of the database you are connecting to
    $userMS -> The username you use to log onto the database
    $passwordMS -> Password to the Database
    $database -> The database been used for the tool -> Please note: this must be manually created via phpmyadmin or the console.

***************************************************
* Students list                                   *
***************************************************

1) There is a Directory called uploads, this Directory is where files are uploaded too.
2) Location of Directory: Checkpoint_Tool/Staff/uploads
3) Populate the CSV file with your student list. 
4) CSV format should be: Student ID, name then surname -> example: 10000001,James,Bond

***************************************************
* Change Lab Password on the Checkpoint Tool       *
***************************************************

1) The File path is: Checkpoint_Tool/Student/
2) In the checkpointController.php on line 125 change the password, current password is a calculated value.
3) If you selected the attendance tab, in the attendanceController.php on line 126 change the password  

   
***************************************************
* Configuring the Admin of the Student Tool       *
***************************************************

1) In a browser, navigate to the Setup Directory __URL/Setup and follow the steps to set up the Course details and the Admin user of the tool.

***************************************************
* Login as Admin                                  *
***************************************************

1) This interface is located at __URL/checkpoint_Tool/Staff/
2) Through this interface, you can set up the number of labs you want to gather feedback for; this can be added to over time.
4)  This can be found on the Labs Tab.
5)  Additional users can also be added.
  


