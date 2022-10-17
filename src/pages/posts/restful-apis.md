---
title: Designing RESTful API's
slug: restful-apis
date: 2022-10-13
author: Dennis Ivy
read_time: 2
tags: [api]
order: 2
draft: false
past: true
---

What is an API and what is a REST, or a RESTful API? I often see developers use the term REST API without fully knowing what makes an API RESTful. After all you can have an API and you can have a RESTful API.

When doing a search on youtube for example you'll see alot of videos using the the keyword REST but many of them really are just describing what an API is without even touching on the topic of rest.

I've realized we have really mixed these two definitions together so what I want to do here is talk about what an API is, how we can make it RESTful, and a scale we can use to see how well an API is following the REST standard.

### What is an API

In my own words an API is a portal for communicating with some sort of server with predefined rules and endpoints. API's give us a way of interacting with these endpoints by retriving and sending data.

As a backend developer I can great a set of endpoints (or urls) someone make request to. Let's look at this example of an endpoint wich returns an array of objects with information about products in a store.

The endpoint I would provide to a frontend developer would look something like this.

```
mywebsite.com/api/products
```

The response someone would get when making a request to this endpoint would look like this.

```json
[
    {
        "id":1,
        "name":"Iphone 14",
        "img":"mywebsite.com/iphone.png"
    },
    {
        "id":2,
        "name":"Samsong Galexy",
        "img":"mywebsite.com/samsong.png"
    },
    {
        "id":3,
        "name":"Macbook Pro",
        "img":"mywebsite.com/macbook.png"
    },
]
```

API's typically return a response in XML or JSON format. Now days you'll most likly see JSON data like in the example above. 


With this data a frontend developer can now do what they need on the frontend to render this data in the template or interact with it without ever needing to see what the backend of this application looks like. The API give them an access point.

### 


# NEW Build the demo a few times tonight * Prep slides

"Building API's with Django"

"Build a Simple & Searchable API with Django"

#PREP FOR STREAM
- Slides
  - Agora Intro slide
  - Turn this to that
  -  API
  -  API Use Cases
  -  My first tweet slide
  -  Django Slide
- Cados link
- proshop link
- Django & DRF docs
  

## Step By Step

- Intro as an Agorian & Channel

- What My talk will be about
  - API's
  - Building API's with Django & A simple searchable API with Django

- What are API's and why do we need them
  - Show API definition slide
    - An API provides an access point and a way of communicating with a server side application in a uniform way.
    - Turn this to that picture (JSON data)
    - Example: (This to that)
      - Backend dev
        - Database, server -> API data
      - Frontend Dev
        - Makes request to url & gets data, then renders in to "this"
    - Show cados example

  - Talk about a few use cases
    - Backend and frontend
    - Public Data
      - Twitter API
        - My first Tweet
        - Get user data request
    - Mention cados hackathon API

<!-- What is REST
- Representational State Transfer
- Explain definition

What makes an API RESTful
- . -->

Building API's with Django
- Django is great for building API's
- My background with Django and API's I've built (Cados, Ecommerce)
- I use Django for API (Cados, Ecommerece)
  
Code Along (Took 21 min in practice)
- Prereq - Python & Virutal environment
- Start django project and create app & move environment to project
- Config views and urls to return simple JSON response (endpoints view)
- Create a advocates and advocate view
- Install django rest framework
- Update views
- create model (Advocate: name, bio) & register in admin panel
- create serializer
- Serializer and return data
- advocate detail view
- Searchable API



## Slides

**Intro as Agorian**

**Intro To My Talk**

- API & REST API's
- Building API's
- 