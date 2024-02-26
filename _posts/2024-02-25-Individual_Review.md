---
toc: true
comments: false
layout: post
title: Individual Review
courses: { csp: {week: 23} }
type: tangibles
---

Project Overview:

Our project centers on a shared passion within our group: video games. This unanimous interest, which we all regularly indulge in, serves as the cornerstone of our initiative. Recognizing the importance of moderation, our project aims to balance gaming with educational pursuits and physical activity. By integrating gaming with access to educational resources and fitness activities, we seek to inspire our users to diversify their interests. The project includes functionalities that offer guidance on maintaining physical well-being, support in academic studies, and assessments of educational levels, all while providing a space for users to unwind with games.

What I did:


Frontend 
- I created the leaderboard for each game, and for the educational hub as well
- Helped with styling of cookie clicker and other games.
- Re-did the education hub frontend 
- Created a new skin item in cookie clicker, once you reach a certain amount of points, it allows you to buy and switch the skin.

Backend 
- Fixed 403 error/CORS errors. Fixing CORS error was crucial as it allowed for things to pass that were key in running our project.
- Created the whole backend for quizzes, and helped a bit for games
- My backend for my feature working on user, users and player to save the game score and  quiz results to each user, on the database

Others: Created a plan and made Database UML designs and Frontend UX Design

My Key Commits:

[Frontend](https://github.com/IshanCornick/Real-Estate-Frontend/commits/main/?author=AkshayNagesh)

[Backend](https://github.com/IshanCornick/RealEstatebackend/commits/main/?author=AkshayNagesh)

PS: Sent lost of code to andrew to put in for me while commits were broken such as linking leaderboard to backend and other important commits

Key commits in frontend were the leaderboard and gradelevel

Key Commits in backend were the changes in main.py, (fixed key terms in teh file), adding gradeLevel columns, and creating the main layout for it. 

My Feature: 

My main feature is the education hub, in which you take a small quiz that determines what grade you are in. Also made the leaderboard feature, when playing games and earning points, the points you earn are put on a leaderboard with other users.

### Component A: Program Code

| Collegeboard Requirements | Me |
|---------------------------|----|
| Instructions for input from one of the following: the user, a device, an online data stream, a file. | My feature takes in the information enetered in the quiz, and tells you what grade you are in. |
| Use of at least one list (or other collection type) to represent a collection of data that is stored and used to manage program complexity and help fulfill the users purpose. | An example of a list is for the questions asked in the quiz. After the quiz an example of collection of data is shown as the information is collect to give a response which is saved to the user. That response that is saved is then added to the data table. ![Alt text](</student/images/Screenshot 2024-02-25 at 5.33.23 PM.png>) |
| At least one procedure that contributed to the program’s intended purpose where you have defined: the name, return type, one or more parameters: | This procedure has a name(post), a return(response), and parameters(self): procedure  ![Alt text](</student/images/Screenshot 2024-02-25 at 5.51.28 PM.png>)|
| An algorithm that includes sequencing, selection, and iteration that is in the body of the selected procedure | This function shows the sequencing, selection, and iteration through the "grade": sequencing ![Alt text](</student/images/Screenshot 2024-02-25 at 5.54.39 PM.png>) |
|Calls to your student-developed procedure|Calling "grade": Calling ![Alt text](</student/images/Screenshot 2024-02-25 at 6.00.14 PM.png>)|
|Instructions for output (tactile, audible, visual, or ) based on input and program functionality| My feature outputs 2 things. First after you finish the quiz it outputs the grade you are in. Second after it saves to the user it outputs it and saves it in a datatable ![Alt text](</student/images/Screenshot 2024-02-25 at 6.05.43 PM.png>) |


### Component B: Video

My Video
<video height = 400 src="/student/Videos/IndividualReview.mp4" controls title="Title"></video>


| Collegeboard Requirements | My Video |
|---------------------------|----------|
| Input to program | Seen in video, login and quiz fillout |
| At least one aspect of the functionality of your program | The quiz working and saving it to user |
| Output produced by program: | The quiz giving grade level and saving to user and database  |
| My video does not have: | any distinguishing information, voice narration or "mouse wiggle" |
| My video is | a .mov, less than 1 minute in length, less than 30MB in file size. |
