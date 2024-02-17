---
toc: true
comments: false
layout: post
title: Night At the Museum
courses: { csp: {week: 22} }
type: tangibles
----
***N@TM***

**Reflection**

- My team did not quailify for N@TM because of serveral reasons but in the end if we were on top of everything the second we learned about it I think we could of qualified.

- We had some trouble deciding which project was best but in the end we decided to make games and store info about users and be a very well rounded project with fun activties, tips to physical health and studying help.

- I wasnt able to attend N@TM but was able to look at friends projects in my period and other peroid.

**Glow**

- One glow my team had was minimal arguing, if someone wanted to do something they were passion about other would agree and adept to help others and make the overall experience better.

- Another glow was even though we got knew group I already knew two of my group memeber for a while and were able to connect with them easily and work better with them.

- One more glow was our determination, even though at some times we were working at the last second we would work to 3 am or later trying to fix something.

**Grow**

-I feel like when doing my project it was only me, Akshay and Andrew doing everything so I feel like we can grow by trying to get tanuj to his part so our project is better rounded.

- We could next time work on stuff ahead of time. My entire group are last minute type people which causes a lot of stress and late nights. This also leads to not our best work so I hope we can grow on that.

- This is more of a grow for just me but focusing more on backend. I am normally a frontend person and struggle on backend. Today I took I chance and ask friends to help me learn backend. After learning I was quick to grasp the ideas and was able to save my variables to each of my users. I am now able to do that quiet easily and can help my teammate with that if needed.

**Something that I saw and liked** 

Even though I didnt go to N@TM I was still able to see friends projects in my period and other periods. One of my favorite projects was Lincoln's about Clash Royale. Clash Royale is one of my favorite games and what there website does isnt done on any other website is isnt like the other projects that are just different verisons of big websites.

**Something I liked out side of CS**

One thing I liked outside of CS is how many friends I made in that class. That class is very team based and relying on each other so I feel like any friends I make in that class are deep friends that I have experienced "struggle" with. The amount of great friends I make that actually have friendships out of school is amazing and something I am very grateful for.

Team Reflection:
Throughout this project, our group has had a lot of problems whether it be communication or work management. However, despite all the problems our group had, we have now managed to create a working backend and frontend. It was a challenge for me to learn how to get the backend to sync with the frontend. After learning and debugging for the past week, I feel much more confident that I can help my teammates finish up their features. Based off of the feedback we’ve received from other groups and the teacher, we need to add more depth to our project. Right now everything is only synced on one game and the features we have out either too simple or not quite working. Over the break, we will work to add a wider variety of features to our game(Ishan is trying to add an educational feature) and fully sync up the leaderboard system.

CORS Issue: 
![Alt text](</student/images/Screenshot 2024-02-16 at 10.01.16 PM.png>)
I tried updating the cors __init__.py, main.py and the user.py but the cors does not work. I also tried changing the frontend cors but it still gives the same error.

Solution: 
JWT vs PYJWT and the Virtual Enviroment
{
"error": "Something went wrong",
"message": "module 'jwt' has no attribute 'encode'"
}
JWT did not have the attribute 'encode' for whatever reason. I downloaded PyJWT and then it started conflicting with the JWT. I made a virtual environment that did not have the JWT and it stopped conflicting. This solved the problem.
:D
