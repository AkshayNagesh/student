---
toc: false
comments: false
layout: post
title: Night At The Museum
description: Coding night
courses: {csp: {week: 22}}
type: hacks
---
***N@TM***

**Reflection**

Our team tried to get into N@TM but didn't make it. We think we could have done better if we started working on things right away. At first, we couldn't decide what to work on. We ended up making a game platform that has fun stuff, health tips, and help with studying. Due to mandatory practices, I unfortunately couldn't make it

**Good Stuff**:

We didn't fight much. If someone wanted to do something, we all helped out. This made things better for everyone.
I already knew two people in my group, which made working together easier.
We were determined. Sometimes, we stayed up until 3 am to fix problems.

**Need to Get Better**:

Most of the work was done by me, Ishan, and Andrew. We need to get everyone, like Tanuj, to do their part.
We do things last minute, which is stressful and doesn't lead to our best work. We want to start earlier next time.
I usually do the look of the projects but tried doing the behind-the-scenes stuff this time. I learned a lot and can do it better now.

**Cool Things I Saw**:

Even though I missed N@TM, I liked a project about real estate, it was cool, what I liked about it was their AI Bot feature, when you ask the AI a question based on houses, it accurately gives you an answer back. 

**Outside Class**:

I made a lot of friends in this class. We all worked together and overcame tough times, which made us closer, leading to my growth. Also viewing my other friends' success had fired me up, wanting to be just like them as well

Looking Back:

We had some issues like not talking enough or managing our work well. But we made something that works both on the front and the back. Learning how to connect these was tough but cool. We got feedback that we need more stuff in our project. So, we plan to add more features and make it better.
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

