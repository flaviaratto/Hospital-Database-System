# Hospital-Database-System
A Database Application developed using Java and MySQL.


## Entity Relationship Diagram - ##
<img src="https://github.com/flaviaratto/Hospital-Database-System/blob/main/ER_Diagram_Final.png" width=100%>


## Steps to run the application - ##
There are two parts to be followed in order to run the application

**A) Steps to set up the database -**
  1. The database for my application is created on phpMyAdmin in XAMPP https://www.apachefriends.org/index.html
  2. After installation of XAMPP, launch the XAMPP control panel. Click start next to Apache and MySQL both.
  3. Once they both turn green, click on Admin. You will then be navigated to a localhost on your browser where you can create the database.
  4. Create a new user by clicking on the User Accounts tab. 
        ```
        User Name - admin
        Host Name - Select local from the dropdown
        Password - admin
        ```     
      In Global Privileges, click the check box next to Check all  
      Click go
  5. Navigate to the home screen and click on the Import tab.
  6. Choose the **hospital_db_final.sql** file import
  7. Once the import is done successfully, you will see a database named hospital_db created.


**B) Steps to run the Java application -**

  1. The application is compiled using JDK7. Please ensure you have **JDK 7 or higher** installed. You need Java to run the application. Install according to your system if it is not already installed.  
  https://www.oracle.com/java/technologies/javase-downloads.html

  2. Double click on the **HospitalDatabaseSystemProject.jar** file present in the folder "Executable_File" to run the appication.  
    If double clicking does not work, you can run the program in command line by typing in the command -     
          ```
          java -jar "HospitalDatabaseSystemProject.jar".
          ```
    Please make sure you are in the directory where the .jar file is located.  
    If both the above methods don't work, make sure the environment variables have been set correctly for Java  

  3. The Login Page will be displayed. You will need the credentials provided below.  
      In order to login as a **Receptionist**:  
        ```
        Username - amy  
        Password - amy  
        UserType - Receptionist  
        ```

      In order to login as a **Doctor**:  
        ```
        Username - john  
        Password - john  
        UserType - Doctor  
        ```

  4. After logging in, you will be able to access the application according to the usertype.  


**Note:** If you want to view the source code and run that, the source code is present in Complete_Project_Source_Code.zip 
Login.java is the main file
