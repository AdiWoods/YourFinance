#YourFinance

Video Demo: https://youtu.be/iGg8wL-c5js

##Description:
> Hello World! I am Aditya Kadam.

> This was my final project for CS50x.

> I have built this project using technologies like HTML, CSS Javascript, MySql and PHP.

##Reason for choosing this idea for the final project:
YourFinance is a simple web app with a single use-case and that is to track your finances which includes your day-to-day transactions (both income and expenses). This idea is a solution to a problem which I have faced in my day-to-day life where keeping track of my transactions is difficult for me. In this digital age of fast transactions, I often lose track of the amount of money I am spending lol. If anything I have learned from CS50 then it is that we can use our knowledge and skills to solve real-world problems. Technology is simply a beautiful tool with which we can build something useful.

##Features:
1. Login and Registration Page.

2. Track your Finance Page. (where you can track your transactions)

##Walkthrough of my project:
To get a visual walkthrough you can the YouTube video (the link is above).
YourFinance is basically a web app to track your finances.

1. Once the user opens the web app user will see the registration page.

2. The user can enter the details like his name, mail and password.

3. IF the name or mail already exists then the user will get the message that the username has already been taken.

4. ELSE the user will be redirected to the login page.

5. At the login page user has to log login using the same name and password that the user used for the registration.

6. The user will be redirected to the yourFinance page.

7. The user can see his available balance.

8. The user can see the income and expense amount.

9. The user can see the history of transactions below the income and expense amount.

10. The user can add a new transaction by simply adding the name of income or expense.
    a) if income use +ve (+) before adding the value.
    b) if expense use -ve (-) before adding the value.

11. based on the value the balance will be recorded.

12. After using the web app user can log out and the user will be redirected to the login page.

13. Whenever a user wants to see his previous transactions or if ever needs to add another transaction user can log in using the name username and password that he used for registration.

##Project Structure :
1. Registration Page:
    a) The user can register himself to the web app via this page and the data will be recorded in the database.

    b) User some other user tries to register with a name or email that is already being used the message will pop up that the 'username already exists'.

2. Login Page:
    a) The user will be redirected to this page after registering and via this page user can go to the main YourFinance page.

    b) The user has to enter the same name and password that the user used for registration.

3. YourFinance Page:
    a) This is the main page of my project.

    b) The simplicity of this page makes it more sophisticated.

    c) The main purpose behind the design was to keep things simple and easy for users to understand.

    d) At the top you can see your balance available with you.

    e) Below that is where you can see your income and expense amount i.e. the amount that is being credited and the amount that is being debited.

    f) Below that you can see the overall history of transactions.

    g) Below that you can add the transactions.

    h) you have to add the amount in (+ve for income and -ve for expense).

    i) After using the web app you can simply log in.

    j) You can log back in whenever you want to see your past transactions or record a new transaction.

4. Registration.php:
    a) This is where the registration done by the users is being recorded.

    b) They are stored in a database created in phpmyadmin.

5. Validation.php:
    a) This is similar to registration.php.

    b) certain changes that it contains are those that redirect the user to a different page.

6. Database:
    a) The user-registration table is created which consists of 3 columns and those are name, mail and password.

    b) name is of type VARCHAR with value 50 and it is the PRIMARY KEY.

    c) mail is of type of VARCHAR with value 50.

    d) password is of type VARCHAR with value 50.

    e) every time a different user does the registration the entry is recorded in the table.

##Usecases of different files:
1. login.php is a file where I have designed the login and registration page

2. Styling of the login.php file is done in style1.css.

3. YourFinance.php is where I have built the main Finance tracker page and its necessary javascript code is in script.js.

4. Styling of YourFinance.php is done in style.css.

2. Registration.php is where the database of users registering is handled.

3. A table named userregistration is created in PHPmyadmin where there are 3 columns "name, mail and password".

4. I have used WAMP to host this web app. validation.php used the same logic as registration.php only difference is in redirects to different parts of the web app.

5. logout.php is used to destroy the session and it redirects you to the login page.

6. This was all. It was fun building this and I learned a lot.

##Final Note:
Doing CS50x was one of the best decisions of 2022. It taught me a lot more than just programming languages. I am thankful to all the staff and especially to David Malan. He is probably the most enthusiastic and dedicated teacher I have ever seen in my life. It was a great experience and fun to learn and grow.
