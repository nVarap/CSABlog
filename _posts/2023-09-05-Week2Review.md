---
toc: True
comments: True
layout: post
title: Week Two Review Ticket
description: Week 2 Review Ticket
type: tangibles
courses: { 'csa': {'week': 2} }
---

[Week 2 Review Ticket Issue](https://github.com/nVarap/Emarlu/issues/1#issue-1878830580)

# Emarlu
Emaad and Varalu's API World

# Purpose of the program: 
- Create a dating app that actually works this time
- Be able to allow people to set up accounts
- Allow people with accounts to match with others
- Build our OWN API endpoint using flask in order to CRUDify our program

# THREE MAIN FUNCTIONALITIES
- Input information and *login*
- Set up and *match* with people
- *Look* at another person's profile

# Handling and using Input to Affect output:
- The input of this code is the user inputting or changing parts of their own user profile to better match with those around them
- They also can set parameters for their choice, as a result affecting the output
- It will pull from a database of people, allowing people to select their favorite choice
- Should be able to see another person's profile


# Stretch Goals:
- Build a chat environment between the two people
- Be able to change preferences when looking for people (filters)c

FRONTEND
- [x] Create a login page for the users (using HTML or something similar like PHP)
- [x] Allow users to create accounts 
- [x] Allow users to input their age, gender, interests, etc. that will help in picking their match
- [ ] Create a matching page
- [x] Create a profile page that is dynamic for each person based off name and UUID


BACKEND
- [x] Create a database of multiple users
  - [x] Can use old flask template from last year to do this
  - [x] Model folder and API for users on our dating site can follow the same format as the existing APIs for users, covid, etc.  
 - [ ] Input dynamic data via an API we build that updates through sign-ups
- [x] Make attributes that we will base the person's match on (i.e. interests, age, gender, etc.)
- [x] If necessary, use Postman from CSP to make sure that data can be created, removed, updated, and/or deleted without any issues
- [x] Check the database locally to make sure that it works   

LINKING FRONTEND AND BACKEND
- [ ] Create matching page
- [ ] Allow users to search for (?) and look at other peoples' profiles
- [ ] Based on what the user inputs, the website will provide them with a list of people with similar interests, age groups, etc. (which will come from the data set in the backend component of this project) 

STRETCH GOALS (BOTH FRONTEND AND BACKEND)
- [ ] Create a chat environment between the user and their match
- [ ] Allow users (before they input anything) to filter out who they want in their results (using the same attributes created in the backend portion of this project) 
- [ ] Allow users to edit their various statistics, likes, etc.


## Progress:

Currently, we've set up the majority of our data and API, and we've also set up the general frontend. We've been in the process of connecting frontend to backend. We've been having some issues related to CORS and Access-Control-Allow-Origin header issues. These a probably related to permissions and that has to be overcome. We have also been running issues regarding the interests and collecting all the data and placing it as a readable format. But after we overcome these issues, this should not be a problem.

## Collaboration
- Multiple live shares
- Multiple conversations
- Chat-GPT usage
- Asking others outside our group for help

## Sprint Diagram

<img src="{{site.baseurl}}/images/dating-app.png">