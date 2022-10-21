---
title: October Hackathon 🎃  API Edition
slug: october-hackathon
date: 2022-10-3
author: Dennis Ivy
read_time: 1
tags: []
order: 2
draft: false
past: false
---

Calling all backend and frontend developers to participate in the October Hackathon!

## 🎯 Objective

As a developer advocate at Agora, I am always looking to collaborate with Advocates from other companies. Wouldn't it be nice to have a website I can visit to find other advocates? 

In this hackathon we are gonna work together as backend and frontend developers to fix this issue.

Pick one of the two challenges below and build based off of the parameters set.

## 📆 Important Dates
- Start date: 10/10
- Submission deadline: 11/5
- Winners announcement: Maybe 11/10??


## 💰 Prize Money

6 Grand prize winners for a total of $1,500!

✋ How to participate

- Register - <a href="https://codebattles.dev/" target="_blanl">CodeBattles.dev</a>
- Pick a challange
- Submit project before deadline


<br>

### ⚙️ Challenge 1 - 💻 For Backend Devs

<br>

💰  Prize money: $200 - 5 winners will be selected

Build an API that outputs a list of developer advocates with their details such as where they work, social links, bio, etc. Example API response bellow.

**Project Requirements**

Your API should at a minumum have these 2 endpoints

1. `/advocates`
2. `/advocates/:username`


Your API should be searchable (By user name), paginated.

Ex: 

`/advocates/?query=dennis`

Your endpoints should provide links to user profile pictures and company logos.

User Data Ex:

```json
// advocates/:id
{
 "advocates": [
     {
         "profile_pic": "https://pbs.twimg.com/profile_images/1489066537407365126/iViPGBVE_400x400.jpg",
         "username": "dennisivy11",
         "name": "Dennis Ivy",
         "bio": "YouTuber, contributor at @traversymedia , developer advocate @agoraio and online instructor.",
         "twitter": "https://twitter.com/dennisivy11",
     },
 ]
}
```


**Submission Requirements**

- Github link
- Live URL - API must be hosted
- Tag Agora on Twitter OR Linkedin

🧑‍⚖️ What Judges Are Looking For

Judges are looking for an API that works and has data as in example above. If requirements are met, your name will be entered into a raffle for a chance to win $200. 5 winners will be chosen.

<br>

### ⚙️ Challenge 2 - 🎨 For Frontend Devs & Designers

<br>

💰  Prize money: $500 - 1 winner will be selected

Using the the data provided in this link (<a href="https://cados.up.railway.app/" target="_blank">cados.up.railway.app</a>), design and code up a template which consumes the API.

Your website should at a minumum have these 2 pages

1. `/advocates`
2. `/advocates/:username`

`Requirements`

- Github link
- Live URL
- 2 Pages

🧑‍⚖️ What Judges Are Looking For

Judges are looking for the BEST design and most usable template (clean code). The winning template will be used in a live project to complete the website "cados.dev".