# Bruce4.1
Chicken Vs Beef (battle of the (2) meats )

Yea, I'm really late for this and 4.3 (which I'm still working on, just having a major brainfart)


The idea for my project is simple, create a database with 2 tables
Table names are users and Survey (yes, I with a capital S... I will fix that in future projects, there's just too many Survey's im my current project to fix and I commited to it)
I used the SQL commands to join the two tables

SELECT *
FROM users
INNER JOIN Survey ON users.userID = Survey.userID;

A couple of things that my project is SUPPOSED TO DO + hurdles.

1) Made a registration page where it's linked to the database and SUPPOSED to shove in data to the users table, but something from the Javascript is messing with how the data is being inserted where only userID and password was getting inserted. I figured that the scripts were messing with data insertion by removing javascript using chrome options and it started inserting data properly. Still can't figure out what it is yet... it may or may not be the check_email.js file... it initially just blew up the functionality of my register, but it's supposed to just check if there's a unique email in that database so that other people can't register under that email.

2) Login page is supposed to pull data from said table and check for credentials then start session > link to the main index.html (survey/comment section).

3) survey comment section, is simply supposed to store the comments linked to userID and remember the choice the userID made.


Challenges and lessons learned.

Some clear challenges is debugging stuff, time management; this stuff clearly takes time to do, especially when you hit a block and just need a time out.

While these are challenges, they're good learning points to keep in mind for the future. 
0ther learning points: 

-is for bigger projects like this, why it's important to have an outline IE wireframe/moodboard/pseudo code, so you have a "roadmap" to get stuff done more efficiently and more clearly. 
-
-Having a "checkpoint" of sorts whenever I feel like I'm at a "good point" to stop IE: backups, or closing vscode so I can crtl+z back.
-
-Design wise, make interactables/ website functionalities N O T I C E A B L E, whether it be making it thicc or flashy, but try not to take away too much from other stuff.
-
