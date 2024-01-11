---
toc: True
comments: True
layout: post
title: Key Assets and Project
description: Key assets and project
type: tangibles
courses: { 'csa': {'week': 20} }
---

# Trimester 1

## Project 1: Blog Overhaul

This first project of the year was committing the parts of my blog and adding some important tools such as the theme, the scrolling page, design, as well as organizational tools in order to make it clear for myself.

### Key Commits:


## Important Asset: [Individual Review](https://github.com/nVarap/CSABlog/issues/2#issue-1980166071)

This is a review of all of the blogs from trimester 1. 

## Important Asset: [FRQ Review](https://nvarap.github.io/CSABlog/2023/09/20/CrossoverReviewNotes.html)

FRQ Cross Review with another group during trimester 1

## Project 2: Trimester 1 Lesson - Abridged
This was our teaching for trimester 1. In this project, I completed a majority of the Boolean lesson, even creating a study guide that could be used in the [future](https://nvarap.github.io/CSABlog/2023/09/06/BooleanStudyGuide.html)

Here is the boolean lesson

### Key Commits
[Adding Answers for Binary Logic](https://github.com/The-Code-Monkeys/Monkeys38/commit/5c5a7553af07e789396da0817de458610229f08b#diff-5b1d304608ce2e168650436bd8ace95189f444181c09ba756fe4d3ab6496f9b1)





## Project 3: Trimester 1 Project - Abridged
As you may know, we already created a robot that implemented java in order to move. However we were severely behind, either because of our own fault or the supply chain. My key contributions were to actually building the robot, and understanding how its built and contributing to some of the drive train code. I also completed some preliminary code in python to assist in the moc-ups of the robot. 


### Key Commits
[Massive frontend changes](https://github.com/The-Code-Monkeys/monkeyFE2/commit/309bc187a8464fe794ef79ad35f8ea8147b016b5#diff-01099f575968f825499780687eaf6dfeeadf5bfd0971dbe198dddd49d18203b1)

[Massive Backend Commits - Redoing Socket.io.js](https://github.com/The-Code-Monkeys/monkeyFE2/commit/0fab385ac666427021d125660a4b5cc7ab997eb9#diff-6d2246fe7e2f17199de3d7568aa9bb61e53373f91721c4f58a5c67fe2b3bdf38)

[Helping with Queuing]()https://github.com/The-Code-Monkeys/SpringPortfolio/commit/8c071dc6fbfa9e3d0403303d243751f150f25091#diff-92514a0d49db704a5f66e81dcf358bf0ffa98f20e7ba42aad699af1aa0bebd5c

[Old Client Side Frontend](https://github.com/The-Code-Monkeys/MonkeysFrontend/commit/96a16b1f58d0b7c7ff1acd778d50e4ec7bc1be0f)

# Trimester 2

## Project 1 - Trimester 2 Project
My primary contributions to the trimester 1 project were a creation of the Fibonacci spiral (that was incomplete, it was supposed to be ideated and added upon), the creation of the bogosort and insertion sort algorithms on our backend, along with the backend-frontend connection between the frontend and backend. Below are each of these **projects**, each of which has evidence of contribution and completion.



### Sub-Project 1: Completing the Algorithms
My first project was to complete the Algorithms that I was assigned, bogo sort and insertion sort. In order to complete this, I also set up a majority of the backend architecture that was necessary to complete it, including the `abstract` classes that incorporated inheritance 

#### Step 1: Parent Classes

After this, I completed the insertion sort and bogo sort algorithms. Adding parent classes controller [commit](https://github.com/PaarasPurohit/duclick-backend/commit/9658b59ebb3c18e0ec7b4c4bd2577329a998c26c). 


#### Step 2: Bogo Sort

[Key Commit](https://github.com/PaarasPurohit/duclick-backend/commit/19a93ab91eb99b6b998963023ede685878b9ec49). Bogosort + sorting.java that everything else extends.


#### Step 3: Insertion Sort

[Key Commit](https://github.com/PaarasPurohit/duclick-backend/commit/74fc0df39217a65dcb229cd711a9a83fe62ef61b)

This was the first major contribution to the project, committing a majority of the framework my partners would build off of.

### Sub-Project 2: Connecting Frontend and Backend
I also completed the connection between the frontend, making a simple connection to call each function and send an accurate time that we could read. I also incorporated some garbage cleaning to ensure that it didn't simply return 0, instead noting that the algorithms were so fast and that the sample size the people needed to input needed to be larger

#### Step 1: Frontend Connection
[Key Commit](https://github.com/nVarap/CSA_Tri2_Project1/commit/554aa08559137b3cfcdaeada4c7da810c469ddc8)

#### Step 2: Frontend Display 

[Key Commit: Frontend Display connection](https://github.com/nVarap/CSA_Tri2_Project1/commits/main/)

This project was simple, and done because the rest of my team has completed a majority of their project.


### Sub-Project 3: Fibonacci Spiral

This project was completed in one night and really didn't include a lot if any java, or much of a use of a backend. This was all planned to occur, but we ran out of time before we could improve it in any significant way to make it a substantial part of our project.

#### Project 3: Implementing Fibonacci Spiral
[Created Fibo Commit](https://github.com/nVarap/CSA_Tri2_Project1/commit/58219b2784aadf408549aef94b68f49e3b2ad8cb)

```html
<html lang="en">
 <head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Fibonacci Animation</title>
 </head>
 <html lang="en">
 <head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <style>
     body {
     display: flex;
     justify-content: center;
     align-items: center;
     height: 100vh;
     margin: 0;
     font-family: 'Arial', sans-serif;
   }

   .fibonacci-container {
     display: flex;
     flex-direction: column;
     align-items: center;
   }

   .fibonacci-number {
     font-size: 24px;
     margin: 5px;
     opacity: 0;
     transition: opacity 0.5s, transform 0.5s;
     position: absolute;
   } 
   </style>
   <title>Fibonacci Spiral Animation</title>
 </head>
 <body>
   <div class="fibonacci-container" id="fibonacci-container">
     <div class="fibonacci-number" id="fibonacci-number">0</div>
   </div>
   <script src="script.js"></script>
 </body>
 </html>

 <body>
   <div class="fibonacci-container" id="fibonacci-container">
     <div class="fibonacci-number" id="fibonacci-number">0</div>
   </div>
   <script src="script.js"></script>
 </body>
 </html>


 <script>
     const fibonacciContainer = document.getElementById('fibonacci-container');
 const fibonacciNumber = document.getElementById('fibonacci-number');

 let a = 0;
 let b = 1;
 let angle = 0;

 function displayNextFibonacci() {
   const nextFibonacci = a + b;
   fibonacciNumber.textContent = nextFibonacci;

   // Calculate polar coordinates
   offset = 0;
   const radius = Math.sqrt(nextFibonacci) * 10;
   const x = radius * Math.cos(angle);
   const y = radius * Math.sin(angle);

   // Add a new Fibonacci number element to the container
   const newNumberElement = document.createElement('div');
   newNumberElement.classList.add('fibonacci-number');
   newNumberElement.textContent = nextFibonacci;

   // Apply position based on polar coordinates
   newNumberElement.style.transform = `translate(${x}px, ${y}px)`;

   // Update angle for the next iteration
   angle += 30
   offset += 1000;

   fibonacciContainer.appendChild(newNumberElement);

   // Trigger reflow to apply styles before animation
   newNumberElement.offsetWidth;

   // Apply animation to the new number element
   newNumberElement.style.opacity = 1;

   a = b;
   b = nextFibonacci;
 }

 // Display the first Fibonacci number
 displayNextFibonacci();

 // Set an interval to display the next Fibonacci number every second
 setInterval(displayNextFibonacci, 1000);
```

[**Project**](https://github.com/users/nVarap/projects/2)


## Project 2 - Trimester 2 Teaching

[Evidence through issues](https://github.com/nighthawkcoders/teacher_portfolio/issues/93#issuecomment-1883685251)

Key changes through doc: [doc](https://docs.google.com/document/d/1v-nPfhmdz6fDoRWnXTFECgTKZ_bGDKeMR-btSXDfoik/edit)

[Hacks Changes](https://github.com/The-Zesty-Rachits/CatalinaWarden/commit/81756143019848a9460abd1918968eb33aa59199)

This was my teaching throughout Tri 2.






