---
toc: true
comments: false
layout: post
title: Night At the Museum
courses: { csp: {week: 22} }
type: tangibles
----


Team Reflection:
Throughout this project, our group has had a lot of problems whether it be communication or work management. However, despite all the problems our group had, we have now managed to create a working backend and frontend. It was a challenge for me to learn how to get the backend to sync with the frontend. After learning and debugging for the past week, I feel much more confident that I can help my teammates finish up their features. Based off of the feedback we’ve received from other groups and the teacher, we need to add more depth to our project. Right now everything is only synced on one game and the features we have out either too simple or not quite working. Over the break, we will work to add a wider variety of features to our game(Ishan is trying to add an educational feature) and fully sync up the leaderboard system.

CORS Issue: 
![Alt text](</student/images/Screenshot 2024-02-16 at 9.52.29 PM.png>)
I tried updating the cors __init__.py, main.py and the user.py but the cors does not work. I also tried changing the frontend cors but it still gives the same error.

Solution: 
JWT vs PYJWT and the Virtual Enviroments
{
"error": "Something went wrong",
"message": "module 'jwt' has no attribute 'encode'"
}
JWT did not have the attribute 'encode' for whatever reason. I downloaded PyJWT and then it started conflicting with the JWT. I made a virtual environment that did not have the JWT and it stopped conflicting. This solved the problem.
:D
