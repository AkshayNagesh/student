---
comments: True
layout: post
title: Create User
description: cooking
courses: { csp: {week: 20} }
type: hacks
permalink: /lmc-createUser
---
<style>

</style>
<!-- 
A simple HTML login form with a Login action when button is pressed.  

The form triggers the login_user function defined in the JavaScript below when the Login button is pressed.
-->
<link rel="stylesheet" href="/lmc-frontend/LMC/JS/SCSS/lmcLogin.css">
<div id="titleContainer">
    <h1 id="title">Let-M-Cook</h1>
</div>

<div class="background">

</div>

<div class="container">
    <form id="username" action="javascript:login_user()">
        <label>
            Name:
            <input class="userInput" type="text" name="name" id="name" required>
        </label>
        </p>
        <p><label>
            User ID:
            <input class="userInput" type="text" name="uid" id="uid" required>
        </label></p>
        <p ><label>
            Password:
            <input class="userInput" type="password" name="password" id="password" required>
        </label></p>
        <p><label>
            Date of Birth:
            <input class="userInput" type="text" id="dob" required>
        </label></p>
		<p><label>
			Favorite Food:
			<input class="userInput" type="text" id="food" required>
		</label></p>
        <p>
            <button onclick="login_user()">Submit</button>
        </p>
    </form>
</div>

