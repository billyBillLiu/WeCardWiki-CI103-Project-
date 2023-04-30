**April 24 - April 30, 2023**

Issues: NONE

Activity Report:

Creating and Saving Cards - Fix the text-overflow issue in the edit page - TO DO \
37 min \
I removed unnecessary rows and columns in BlankCard.dart. The unnecessary row was causing the container to follow the text off of the screen. I then wrapped the text for "Name" and "Email" in BlankCard.dart with sized boxes. This prevents the text from going to the next line and ruining the formatting. I tried using FittedBox to have the text shrink, but it would break the app when I tried. \
_April 29, 2023, at: 11:23 PM moved to In Progress, 12:00 AM moved to Review._

Signed By: \

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