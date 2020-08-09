# Real-time-Manual-Control-Panel-for-Robots
This code stores the robot controller instructions in database and display it on another php file using XAMPP in localhost

* This repositery includes index.php file which contains the robot controller once a button is clicked it will be stored in a database
* The view.php will read from the database and display it 

to run this code :
1. install XAMPP and create a database called 'robot controller', and a table called 'directions' 
2. create user for the database with the following information : User name: robot, Host name: localhost, password: robot1234

![3](https://user-images.githubusercontent.com/67188835/86241684-3ccff800-bb58-11ea-8b46-538e11c8ef7b.PNG)


3. the table structure should be as defined below 

![1](https://user-images.githubusercontent.com/67188835/86241537-eb276d80-bb57-11ea-8972-5b66cd536f38.PNG)

![2](https://user-images.githubusercontent.com/67188835/86241598-0db98680-bb58-11ea-8264-5100e053905b.PNG)

4. put the files in 'xampp\htdocs'
5. run Apache and MySQL in XAMPP

![4](https://user-images.githubusercontent.com/67188835/86241747-5a9d5d00-bb58-11ea-88b6-2be91afe2156.PNG)

![5](https://user-images.githubusercontent.com/67188835/86241790-6db02d00-bb58-11ea-9605-b80f14694fa1.PNG)

