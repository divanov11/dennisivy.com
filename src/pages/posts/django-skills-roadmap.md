---
title: Django Skills Roadmap To Getting A Job
slug: django-skills-roadmap
date: 2022-6-19
author: Dennis Ivy
read_time: 6
tags: [Django]
order: 1
hero: 
draft: false
---

![](images/django-skills-1.png)

I just got asked this question on LinkedIn and I have to say, it’s a tough question to answer but I get it all to often so I’ll address it here.

You can also see the video version of this posted on YouTube here

First thing I’ll say is that nothing is concrete, everything depends on the company, the person interviewing you and the needs they have to fill. This answer is the typical cop-out so I’ll be more specific and give you some examples.

## Getting hired with minimal experience

For me personally, I got my first role as a Django dev after 3 months of studying, with no experience. I’ve also hired juniors with little to no knowledge because I needed them to perform more light weight tedious tasks and expected them to learn more on the job.

## What most Juniors need to know

Lets assume I am the one hiring, I need someone who can be part of my core team and take direction from a lead developer, and execute tasks efficiently without needing to be coached up all the time. This person will have a senior to rely on but is expected to know how to perform common tasks and modify the core code base.

What does this person need to know?

**CRUD** — Know how to perform basic Create Read Update and Delete operations. This tells me you know how to set up a Django application, core concepts and how to work with the database and views, and probably the template engine.

**Authentication, Authorization & User Roles** — Just like CRUD, handling user permissions and performing basic tasks like registering users and knowing how to work with sessions is a key part in most applications.

**Static Files** — Images, PDF’s and other static files like CSS and JavaScript files. Do you know where to store these files and how to configure your app to handle user uploaded content?

**Building API’s** — Although not every app will have an API, its common practice to use a framework like Django to build an API to use with a frontend framework like React, Vue or Svelte, or even to just provide some public data. Not only would I expect you to know how API’s work, I’d probably want you to have a base understanding of implementing REST practices and how to build a Restful API using the Django REST framework.

**Project Architecture** — I’ll go easy on most junior’s here, but I would expect you to properly separate your projects apps based on categories' and use case. For example, when do you decide to separate your code into a new app and how do you separate it? Where do you store your templates and why? How do you structure and separate your URLs?

**Basic Web Dev knowledge** — This one probably doesn't need to be mentioned but I’ll do it anyways. Please have a basic understanding of how the web works and spend some time to get to know the following:

- Basic Python
- HTML
- CSS
- Git & GitHub
- Request response cycles & Http methods

In summary, just know how to build a basic application and make sure you don’t have a blank stare in your face when I mention a concept that includes one of the key points. Not knowing exactly how something works is ok, just know how to ask the write questions and take the time to learn basic terminology. I’d recommend skimming through the [Django docs](https://docs.djangoproject.com/en/4.0/) and reading a bit about every concept. You wont need to know half the stuff but at least know what I’m referring to and be willing to learn it if asked.

## Applications junior's should know how to build

I can learn a lot about what someone is capable of based on the projects they build. Below I will list a few projects juniors should build and why. Each project has a different level of functionality that a junior should be capable of building out with just the Django docs, stack overflow and the occasional google search, just no following a tutorial. The occasional search for some source code on GitHub is also ok, I just want to make sure you’re building and not copying.

- **To Do App** — I always recommend everyone start with some basic CRUD application to learn how to setup an app and work with the database. Challenge yourself and add authentication and user permissions. Try building it twice, one with [function based views](https://youtu.be/4RWFvXDUmjo) and one with [class based views.](https://youtu.be/llbtoQTt4qw)

- **Ecommerce website** — Along with basic CRUD and Authentication that most eCommerce site’s will need, you’ll learn more about complex database relationships when it comes to adding Products, Orders, Tags and more. Building an eCommerce site will teach you a lot about designing your models and complex queries. Let’s also add search, pagination and user roles to that equation. 

- **Social Network** — A social network will also force you to learn about designing your database. For example, how would you build out the “friends” or “following” feature’s? What about likes and determining what post a user will see in their feed.

You’ll learn a lot by building these projects out but please don’t think that you’ll need to spend months building them. Try the “To Do” app and start applying for jobs, then learn as you go.

## Getting into the technical details

At a high level I talked about what capabilities you must have for a typical junior position, so lets get into specifics now to create sort of a road map of what you need to know.

### Basics:

- Project setup
- Apps
- Views & Urls
- Templates & Template Language
- Admin Panel

**Class Based View’s** — Regardless of what you use in your app, knowing how to read and write class based views is important.

**Models & Django’s ORM** — Be capable of writing basic models, creating relationships between these models and have a good understanding of how to read and write queries to the database.

**Model Forms** — Used in both function based views and Class based views. Know how to use and modify them.

**Signals** — Signal dispatchers, I use them all the time and so should you. I don’t have much more to say on this one, just trust me, signals are important ;)

**Serializer’s** — Know how to serialize your data, nest serializer's and follow best rest practices when creating or modifying serializer's. A key component when working with django REST framework (DRF).

**Session & Token Authentication** — Have a base knowledge of how session and token authentication works and how to implement both.

## Important but not deal breakers

- Deploying applications & hosting
- Middleware
- Caching
- Context managers
- Viewsets & Routers
- Writing tests

## What Mid level & Senior Dev’s Should know

As a senior or more seasoned dev, you’ll be expected to know all of the above but at a higher level, including the “Important but not deal breakers”, Sorry, only the junior dev’s get a pass here.

Along with the technical knowledge base you’ll be expected to give input on key decisions on things like core project architecture, lead junior dev’s and write efficient code. If a junior writes bad code it’s up to a senior to spot it and fix it.

In summery, for the “Mid level & Senior Dev” section, just be ready to answer any question related to the docs, especially from juniors, know your code base and know why and what technologies to use for each case.

I released a video about Django interview questions over a year ago so I’ll link that up along with some other resources you should check out.

- [“Django Interview Questions (Junior Developer)”](https://youtu.be/9ai0b1LRMQM)
- [“Python Django Explained In 8 Minutes”](https://youtu.be/0sMtoedWaf0)
