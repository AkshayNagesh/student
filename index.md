---
layout: default
title: Student Blog
---


## Akshay Nagesh's Page
Go to my [github account](https://github.com/AkshayNagesh)

## About Me
Hi, my name is Akshay Nagesh. I am 15 years old. I am a hard working person who loves to code. A little about me is I am a huge fan of soccer, and my favorite soccer team is Manchester City. My favorite soccer player is Christiano Ronaldo. Not only I a soccer fan, but I also love to play soccer, I play competetive for a team called Force. I also enjoy cooking, tennis, ping pong, and haning out with family and friends. I am really excited to be taking AP CSP this year. 
Blogging in GitHub pages is a way to learn and code at the same time. 

### My Interests 
![ChristianoRonaldo](https://c4.wallpaperflare.com/wallpaper/139/444/1000/cristiano-ronaldo-wallpaper-preview.jpg)
![ManchesterCity](https://e1.pxfuel.com/desktop-wallpaper/619/64/desktop-wallpaper-manchester-city-man-city-aesthetic-thumbnail.jpg)
![GOAT](https://e0.pxfuel.com/wallpapers/736/844/desktop-wallpaper-best-soccer-players-cool-football-player.jpg)
![Nike](https://www.pixelstalk.net/wp-content/uploads/images6/Cool-Nike-Wallpaper-Blue-Color.jpg)
## About Me Freeform Picture
![Freeform](IMG_2439-2.jpg)

### Favorite Ronaldo Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/2uG-YOiewwo?si=5Hhwfpl4Df6s7_x0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Man City vs. Inter: Extended Highlights | UCL Final | CBS Sports Golazo
<iframe width="560" height="315" src="https://www.youtube.com/embed/CDL_487D5Ms?si=QDPUgY-fpdOykm-9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Cristiano Ronaldo - Juventus vs Real Madrid - bicycle kick goal
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZC_XihZGPEg?si=nVni6KiWRbfAZlto" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<div id="game-container">
  <h2>Guess the Number Game</h2>
  <p>Try to guess the secret number between 1 and 100!</p>
  <input type="number" id="user-input" placeholder="Enter your guess">
  <button id="submit-button">Submit Guess</button>
  <p id="message"></p>
</div>

<script>
  const secretNumber = Math.floor(Math.random() * 100) + 1;
  const userInput = document.getElementById('user-input');
  const submitButton = document.getElementById('submit-button');
  const message = document.getElementById('message');

  submitButton.addEventListener('click', () => {
    const userGuess = parseInt(userInput.value);
    
    if (isNaN(userGuess)) {
      message.textContent = "Please enter a valid number.";
    } else if (userGuess < secretNumber) {
      message.textContent = "Try a higher number!";
    } else if (userGuess > secretNumber) {
      message.textContent = "Try a lower number!";
    } else {
      message.textContent = `Congratulations! You guessed the number ${secretNumber}!`;
      submitButton.disabled = true;
    }
  });
</script>
## Overview of Hacks, Study, and tangibles
Blogging in GitHub pages is a way to learn and code at the same time. 
- Plans, Lists, [Scrum Boards](https://clickup.com/blog/scrum-board/) help you to track key events, show progress and record time.  Effort is a big part of your class grade.  Show plans and time spent!
- [Hacks(Todo)](https://levelup.gitconnected.com/six-ultimate-daily-hacks-for-every-programmer-60f5f10feae) enable you to stay in focus with key requirements of the class.  Each Hack will produce Tangibles.
- Tangibles or [Tangible Artifacts](https://en.wikipedia.org/wiki/Artifact_(software_development)) are things you accumulate as a learner and coder. 

**Contanct Info**
- Email: akshayn1219@gmail.com
- School Email: akshayn42301@stu.powayusd.com


