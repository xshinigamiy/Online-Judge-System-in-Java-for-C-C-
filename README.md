# Online-Judge-System-in-Java-for-C/C++


Install mysql on your system and then follow the instructions given below

Create a database and name it as "userlogin" without quotes
then inside this database that you have created just , create a table and name it as "user" without quotes
This table will have two fields 

1. username -- varchar type 
2. password -- varchar type

Then create another database and name it as "problemset" without quotes.
Now create a table inside this database that you have just created , and name it as "problems" without quotes.
this table will have three fields

1. problem_id -- unsigned int
2. problem_code -- varchar type
3. problem_statement -- TEXT type


problemset database will store the problems and related information.

you will have to connect this database to the jdbc-connector to use the databases from the java code. for that you can search online how to use jdbc-connector.


create a file in this directory "/home/ajaykumar/" (replace ajaykumar with your username)and name it as "main.cpp" without quotes.

all the files(Frame.java,Frame3.java,Frame4.java,Frame5.java,Frame6.java,....etc) in this project should be contained in the project named "jdbcdemo" without quotes.

once the "main.cpp" file has been created , then create a text file and name it as "input.txt" in the directory "/home/ajaykumar/" .after creating "input.txt" , open this text file and input the test caese so that you can check whether the code is correct or not.


Create another text file and name it as "output.txt" in the directory "/home/ajaykumar/" , open it and put all the correct answers for each test that you entered in the "input.txt" file.


Once all these steps are finished ,You are ready to use this online judge system .


Run file Frame.java ---
a window will showup and it will ask for username as well as password.

then press submit---

select a problem that you want to solve, press submit.

Problem will appear on the screen , read problem and press submit code to solve this problem.

put your code and press submit ----

and finally you will have your result on the display.



















