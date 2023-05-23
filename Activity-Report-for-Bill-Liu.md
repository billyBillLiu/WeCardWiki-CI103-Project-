**May 14 - May 20, 2023**

Issues: None

Activity Report:

Sharing Cards - Display Saved Information on Edit Page - TO DO \
56 min \
I replaced the .add() method with a .set() method in the SaveInfo method in PageC.dart. I also made it so when a user is created on the register page, a new document is created in Firestore. The name for that document is used to name the document. I also created an array field for each user document that holds all the user's collected card ids. \
_May 19th, 2023, at: 12:01 AM moved to In Progress, 12:57 AM moved to Review._

Sharing Cards - Display Saved Info on Main Page - TO DO \
41 min \
I used a FutureBuilder to create a widget that uses data from the database on PageB.dart. The Futurebuilder awaits the getData method written at the top of the file. For each user id in the cardCollection array field, a MyCard widget is created with each field filled in with its corresponding string. I also added a logout button on the left screen for debugging. I also added the button that appends other user's ids to the current logged in user's cardCollection array. \
_May 19th, 2023, at: 12:57 AM moved to In Progress, 01:38 AM moved to Review._

Signed By: \
Bill Liu\
Zhixian Li\
Jiahao Wang_

---------------------------------------------------------------------------------------------------------

**May 7 - May 13, 2023**

Issues: NONE

Activity Report:

Sharing Cards - Initialize Firebase Database - TO DO \
72 min \
I initialized the firebase database. I created a project on firebase.google.com and initialized both the ios and android apps using the firebase CLI. Also installed all necessary dependencies using the CLI. These can be found in pubspec.yaml of carde2. (firebase_auth, firebase_core, and firestore). This is also the first task I did after soft resetting the project. I created a new flutter project called carde2 and put it into the repository. The project is mostly the same, but the files and code is a lot more organized.  \
_May 8, 2023, at: 9:26 PM moved to In Progress, 10:38 PM moved to Review._

Sharing Cards - Create login and register pages - TO DO \
46 min \
I created the login page and register pages. I created file for each named loginPage.dart and registerPage.dart. These are all located in the authentication folder. From the main dart file, it returns the login page. From the login page, the user can either switch to the register page or login and access the main page. \
_May 9, 2023, at: 4:43 PM moved to In Progress, 05:29 PM moved to Review._

Sharing Cards - Implement Login Functionality using Firebase Auth - TO DO \
62 min \
I used firebase auth to allow the user to create an account or login. I also added error messages for when the user inputs a wrong email or password. Once an account is created, it is stored in the database. The lines of code that allow the user to register or login using the databse are denoted by 'FirebaseAuth.instance.method()'. The main dart files leads to a main page which determines if the user is logged in. If the user is not logged in, the auth page is shown, which switches between the register and login page whenever the user presses the 'register' or 'login' text button.  \
_May 9, 2023, at: 6:23 PM moved to In Progress, 07:25 PM moved to Review._

Signed By: \
Bill Liu \
Zhixian Li \
Jiahao Wang_

---------------------------------------------------------------------------------------------------------

**April 30 - May 06, 2023**

Issues: none

Activity Report:

Sharing Cards - Create tables and variables for database. - TO DO \
70 min \
I made three new classes in files named "CardInfo.dart", "UserInfo.dart", and "CardCollection.dart". CardInfo will be displayed on the card. UserInfo will be the user's unique id and login information. CardCollection will contain a list of other user's cards the user has collected. I also created a table variable for each for the SQL database. I also created a field class for each table containing all the variables from each class. \
_May 5, 2023, at: 10:23 PM moved to In Progress, 11:33 PM moved to Review._

Sharing Cards - Create new SQL database - TO DO \
60 min \
I ran some commands in terminal to install the dependencies for SQFLite in pubspec.yaml. Other members should only need to git pull to get these dependencies. I then created a new file called "Database.dart" I initialized the database and wrote the code required to initialize the UserInfo and CardInfo tables in SQL. I also wrote the CRUD operations for CardInfo. The CRUD operations for the other two should be straight forward as copying the one from CardInfo, but I just left "TODO" comments for now. All the table class and database files are located inside a new folder called "database". \
_May 6, 2023, at: 1:20 PM moved to In Progress, 02:20 PM moved to Review._

Signed By: \
Bill Liu \
Zhixian Li 

---------------------------------------------------------------------------------------------------------

**April 24 - April 30, 2023**

Issues: NONE

Activity Report:

Creating and Saving Cards - Fix the text-overflow issue in the edit page - TO DO \
37 min \
I removed unnecessary rows and columns in BlankCard.dart. The unnecessary row was causing the container to follow the text off of the screen. I then wrapped the text for "Name" and "Email" in BlankCard.dart with sized boxes. This prevents the text from going to the next line and ruining the formatting. I tried using FittedBox to have the text shrink, but it would break the app when I tried. \
_April 29, 2023, at: 11:23 PM moved to In Progress, 12:00 AM moved to Review._

Creating and Saving Cards - Replace editing Textfields with direct tap to edit - To Do\
50 min \
I spent a good amount of time researching and trying different methods to replace the text fields with a tap-to-edit feature. I could not find the time to completely finish the task, but made progress. I made a new class in the elements folder called "EditCard.dart". This file contains a derived class that uses BlankCard as a base class. Will implement gesture detection and the rest of the features next week.
_April 29, 2023, at: 12:02 AM moved to In Progress, 12:52 AM moved to To Do.


Creating and Saving Cards - 

Signed By: \
_Jiahao Wang\
Bill Liu_ \

---------------------------------------------------------------------------------------------------------

**April 17 - April 23, 2023**

Issues: NONE

Activity Report:

Creating and Saving Cards - Implementing Class into Edit Page - TO DO \
40 min \
I deleted the separate class I made last week. I used the already existing card widget (Card()) as the class instead. This is located in BlackCard.dart. I renamed it to BlankCard() and changed it to a stateless widget. I pasted the methods from the old class over. I then initialized an object in editPage using that class and used that object to build the display on the edit page. \
_April 17, 2023, at: 8:43 PM moved to In Progress, 09:23 PM moved to Review._

Creating and Saving Cards - Validation for edit name method - TO DO \
20 min \
I created form keys for name, number, and email in editCard.dart. I then added a validation parameter in the "Name" text field that only takes letters, periods, apostrophes, commas, and dashes. \
_April 19, 2023, at: 10:00 PM moved to In Progress, 10:20 PM moved to Review._

Creating and Saving Cards - Validation for edit number method - TO DO \
40 min \
In editCard.dart, I added a validation parameter to the "number" text field that only takes numbers. I also capped the length of the text field 11 digits. If the length is less than 10, a red message will appear below the text field. \
_April 19, 2023, at: 10:21 PM moved to In Progress, 11:01 PM moved to Review._

Creating and Saving Cards - Validation for edit email method - TO DO \
15 min \
In editCard.dart, I added a validation parameter to the "email" text field. The format that is accepted by this validation is email@address.domain. \
_April 19, 2023, at: 11:01 PM moved to In Progress, 11:16 PM moved to Review._

Signed By: \
Bill Liu \
Zhixian Li \
Jiahao Wang_

---------------------------------------------------------------------------------------------------------

**April 10th - April 16, 2023**

Issues: None

Activity Report: 

Creating and saving Cards - Creating Class for the Card - To Do \
43 min\
Created a simple class with no methods. Wrote a constructor with the parameters name, number, email, and other. I also gave all parameters the String property. Majority of the time was spent researching how classes work in Dart.\
April 12th, 2023, at: 8:21 pm moved to In Progress, 9:04 pm moved to Review

Creating and saving Cards - Initialize and create the attributes for the card class - To Do \
15 min\
Created the string attributes name, number, email, and other. The code for this is inside the constructor for the class ("this.name = name;")\
April 12th, 2023, at: 8:49 pm moved to In Progress, 9:04 pm moved to Review

Creating and saving Cards - Create edit email method - To Do\
5min \
Created setter for editing email string\
April 13th, 2023, at: 1:23 pm moved to In Progress, 1:28 pm moved to Review

Creating and saving Cards - Create edit other info method - To Do\
5min \
Created setter for editing description string\
April 13th, 2023, at: 1:23 pm moved to In Progress, 1:28 pm moved to Review


Signed by \
Bill Liu \
Zhixian Li \
Jiahao Wang

---------------------------------------------------------------------------------------------------------

**April 3th - April 9, 2023** (Week 1 Spring Quarter)

Issues: None

Activity Report: 

Nothing done this week

Signed by \
Zhixian Li \
Jiahao Wang \
Bill Liu

---------------------------------------------------------------------------------------------------------

**March 12th - March 18th, 2023**

Issues: None

Activity Report 

Interactability – Create Placeholder Text – To Do \
20 min\
I created a row that contains a column and a container. The row contains a column of text. Three text options: Name, Email, Number.
March 6th, 2023, at: 4:38 pm moved to In Progress, 4:58 pm moved to Review

Interactability – Create Placeholder Image Box – To Do \
10 min\
I created a row that contains a column and a container. The container on the right is formatted to look like an image box.
March 6th, 2023, at: 4:58 pm moved to In Progress, 5:08 pm moved to Review

Signed by \
Bill Liu\
Zhixian\
Jiahao\

---------------------------------------------------------------------------------------------------------

**March 5th - March 11th, 2023**

Issues: We need to complete our minimum viable product finished by the end of the week.

Activity Report 

Interactability – Create Placeholder Cards – To Do \
50 min\
I created the general template for the placeholder cards. I copied the code and put them in a separate folder named "Elements". The function for this card can be called using TheCard(). \
February 6, 2023, at: 8:58 pm moved to In Progress, 9:48 pm moved to Review

Intractability - Create Scroll Function - To Do \
50 min\
I wrapped the placeholder cards in a function called PageView(). I then changed some of the ratio values to have the card better fit the screen. I added several placeholder cards to the PageView() list for now. A function should be added later that allows the user to add cards on their own. \
February 9, 2023, at: 12:58 am moved to In Progress, 1:43 am moved to Review


Signed by \
Bill Liu\
Zhixian\
Jiahao\

---------------------------------------------------------------------------------------------------------


**February 27th - March 5th, 2023**

Issues: We need to complete our minimum viable product finished by the end of the week.

Activity Report 

Design – Create Homescreen – To Do \
30 min \
I created a home screen with a background with the general shape of the card in the middle.\
February 20, 2023 & at; 3:48 am moved to Review

Signed by \
Jiahao Wang \
_Zhixian Li \
Bill Liu_

---------------------------------------------------------------------------------------------------------

**February 20th - February 26th, 2023**

Issues: none

Activity Report 

Design – Create Homescreen – To Do \
30 min \
I created a home screen with a background with the general shape of the card in the middle.\
February 20, 2023 & at; 3:48 am moved to Review

Signed by \
Bill Liu \
Jiahao Wang\
_Zhixian Li_

---------------------------------------------------------------------------------------------------------

**February 13th - February 19th, 2023**

Issues: I spent most of this week figuring out the technicalities of downloading and installing flutter. I successfully set up flutter on my laptop. I pushed the base flutter project template to GitLab. We might switch to flutter as our coding tool instead of swift. Another option is to develop in both swift and flutter simultaneously, but this might not be easy to keep up with. If we want to switch to flutter, I might have to guide you guys through the steps of setting it up in VS Code and installing the emulator since it was quite challenging.

Activity Report

Design - Create Home Screen - To Do \
1 min \
I created and opened the task.
February 19, 2023 & at; 10:36pm added to To Do

Design - Create Swipe Left and Right Functions - To DO \
I created and opened the task. \
February 19, 2023 & at; 10:38 pm added to To Do

Signed by \
_Bill Liu \
Zhixian Li \
Jiahao Wang_

---------------------------------------------------------------------------------------------------------

**February 6th - February 12th, 2023**

Issues: Swift is difficult to install on windows and will not have the same features.

Activity Report 

Design – Sketch a design for the UI – To Do \
30 min \
I sketched a detailed concept of the app. It includes all the UI displays and functions ideas. It can be used to visualize and create the concept flow chart for the app. I moved the task to the review tab. \
_February 9, 2023 & at; 1:40 pm moved to Review_

Signed by \
_Bill Liu \
Zhixian Li \
Jiahao Wang_

---------------------------------------------------------------------------------------------------------

**January 30th - February 5th, 2023**

Issues: There are no issues to report.

Activity Report 

Design – Create Placeholder Cards – ToDo \
50 min \
I created one placeholder card in the middle of the main page. This will be the general card template for all cards made by the program. The font style and information on the card are currently hardcoded. This will be changed later.



Signed by \
_Bill Liu \_