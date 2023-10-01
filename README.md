YourFinance
Video Demo: https://youtu.be/iGg8wL-c5js
Description:
> Hello World! I am Aditya Kadam and I am from Pune, India.

> This was my final project of CS50x.

> I have built this project using technologies like HTML, CSS Javascript, MySql and PHP.
Reason for choosing this idea for final project:
YourFinance is a simple web app with a single usecase and that is to track your finance which includes your day to day transactions (both income and expenses).This idea is a solution to problem which i have faced in my day to day life where keeping track of my transactions is difficult for me.In this digital age of fast transactions i often loose track of amount of money I am spending lol. If anything I have learned from CS50 then it is that we can use our knowledge and skills to solve real world problems. Technology is a simply a beautiful tool with which we can build something useful.
Features:
1. Login and Registration Page.

2. Track your Finance Page. (where you can track your transactions)
Walkthrough of my project:
To get a visual walkthrough you can the youtube video (the link is above).
YourFinance is basically a web app to track your finance.

1. Once the user opens the webapp user will see the registration page.

2. User can enter the details like his name, mail and password.

3. IF the name or mail already exist then user will get the message that username already taken.

4. ELSE the user will be redirected to the login page.

5. At login page user have to do login using the same name and password that the user used for the registration.

6. User will be redirected to the yourFinance page.

7. User can see his available balance.

8. User can see the income and expense amount.

9. User can see the histort of transactions below the income and expense amount.

10. User can add a new transaction by simply adding the name of income or expense.
    a) if income use +ve (+) before adding the value.
    b) if expense use -ve (-) before adding the value.

11. based on the value the balance will be recorded.

12. After using the webapp user can logout and user will be redirected to login page.

13. Whenever user wants to see his previous transactions or if ever needed to add another transaction user can login using the name username and password that he used for registration.
Project Structure:
1. Registration Page:
    a) User can register himself to the webapp via this page and the data will be recorder in the database.

    b) User some other user try to register with name or email that is already being used the message will pop that the 'username already exist'.

2. Login Page:
    a) User will be redirected to this page after registering and via this page user can go to the main YourFinance page.

    b) User have to enter the the same name and password that the user used for registration.

3. YourFinance Page:
    a) This is the main page of my project.

    b) Simplicity of this page makes it more sophisticated.

    c) The main purpose behind the design was to keep things simple and easy for users to understand.

    d) At the top you can see your balance available with you.

    e) Below that is where you can see your income and expense amount i.e the amount that is being credited and the amount that is being debited.

    f) Below that you can see the overall history of transactions.

    g) Below that you can add the transactions.

    h) you have to add the amount in (+ve for income and -ve for expense).

    i) After using the webapp you can simply logout.

    j) You can log back in whenever you want to see your past transactions or record a new transaction.

4. Registration.php:
    a) This is where the registration done by the users are being recorded.

    b) They are stored in database created in phpmyadmin.

5. Validation.php:
    a) This is similar to registration.php.

    b) certain changes that it contains are those that redirects the user to different page.

6. Databse:
    a) userregistration table is created which consist of 3 columns and those are name, mail and password.

    b) name is of type VARCHAR with value 50 and it is the PRIMARY KEY.

    c) mail is of type of VARCHAR with value 50.

    d) password is of type VARCHAR with value 50.

    e) Everytime different user does the registration the entry is being recorded in the table.
Usecase of different files:
1. login.php is a file where I have designed the login and registration page

2. Styling of login.php file is done in style1.css.

3. YourFinance.php is where I have build the main Finance tracker page and its necessary javascript code is in script.js.

4. Styling of YourFinance.php is done in style.css.

2. Registration.php is where the database of users registering is handeled.

3. A table named userregistration is created in PHPmyadmin where there are 3 columns "name, mail and password".

4. I have used WAMP to host this web app. validation.php used the same logic as registration.php only difference is in redirects to different part of the webapp.

5. logout.php is use to destroy the session and it redirects you to login page.

6. This was all. It was fun building this and I learned a lot.
Final Note:
Doing CS50x was one of the best decisions of 2022. It taught me lot more than just programming languages. I 
