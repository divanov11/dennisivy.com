---
title: WordPress Vs Hand Coding
slug: wordpress-or-django
date: 2020-9-25
author: Dennis Ivy
read_time: 4
tags: [Django, Wordpress]
order: 3
hero: https://dennisivy-personal.s3.amazonaws.com/images/wordpress_or_django.jpg
draft: false
---

I get this question a lot, especially after completing my own website (DennisIvy.com) using Django. A lot of people thought it was an overkill but I had good reason to do so. I'll explain why I chose to custom build it along with going over when you should use a platform vs doing a custom build.

Click to play video

[![](./images/wordpress-video-preview.PNG)](https://youtu.be/3xOu8PcfycA)


### Don't Reinvent the wheel

My personal belief is that you shouldn't reinvent the wheel if you don't have to. This may be tempting for many developers but ultimately you should focus on delivering the best product as fast as possible. On the other hand, there are those cases when you'll need custom features these platforms don't provide.

The beauty of these plug-in-play platforms is that you can have a site up and running in hours with little overhead. You'll immediately have plenty of theme options and plugins to make sites work seamlessly. No need to build in your own contact form, image slider or layout builder, just use a plugin. A lot of the heavy lifting has been done for you so why build it yourself when you have deadlines.

![](https://dennisivy-personal.s3.amazonaws.com/uploads/2020/09/25/wordpress-themes-1.png)

So, what are some examples of when you should use WordPress?

`Small Business`- For most small businesses a simple template with a basic contact form and an image gallery will do the job. I've probably built over 100 websites by now using WordPress for small businesses. These included coffee shops, law firms, construction companies etc.

`Blog/Personal Profile`- A personal profile for an athlete, blogger or developer also doesn't require much. These sites typically need somewhere to write up a few articles for SEO or just content creation, a feature already built in to most platforms like WordPress.

`eCommerce` - These are more complex than most websites but, in many cases, there are plugins to handle online stores with digital and physical products along with payment integration. For WordPress I've been using a plugin called WooCommerce that has worked well in most cases.

### When WordPress is not enough

My wife actually built her own site using WordPress where she sold digital products for her photography/design business. As of late the site is under construction because I'm doing a full custom build which leads me perfectly into my next point, when should you custom build?

For my wife it got overwhelming tracking emails and transactions for customers that couldn't find their digital products after a few months because it was buried somewhere in their email inbox. So when we decided we would need a way to allow customers to create an account and view all their digital products, order more products and even run ads to customers based on the type of products they previously purchased, I realized WordPress just wasn't going to cut it.

![](https://dennisivy-personal.s3.amazonaws.com/uploads/2020/09/25/sulamita-account.PNG)

Any time I start running into features like this I try as hard as I can to make it work using a basic platform. Once it becomes too difficult or nearly impossible, I start focusing on building it myself.

Here are a few examples of when I needed to custom build.

`Laboratory Management System` - A custom platform I built used for storing lab data and displaying sample results to users along with search features and much more. Read more about it here.

`Membership Site`  - CodeWithSteps.com, this is a membership site I currently have running where users can register, and pay for access to products. An e-learning platform with lots of customizations.

`eCommerce` - I know I mentioned this as a WordPress site earlier, but there are times when an ecommerce site needs more. Personally I would custom build any ecommerce platform if the features included anything more than some basic payment integration and display of products.

### What should you do?

So does this mean you should go learn WordPress or something of that sort? For me personally, because of my experience I find it easier just to use Django for any one of the examples I mentioned.

But, for those of you still learning, it might be worth trying something like WordPress, Squarespace or Wix for the smaller projects. There's a good chance you might run into a feature that you don't know how to hand build and the last thing you want is to spend weeks on something that is already done for you.

**Plugins & Templates are not just for WordPress**

I know I mentioned that WordPress had built in plugins but there are also plugins and themes for hand coded sites, it just may take a little more work to integrate them. A platform like Form Stack for example makes it easy to integrate a contact form, surveys and even payment integration into any kind of website.

**Why I chose not to use WordPress.**

In short, I had two reasons. First, I feel very limited with WordPress and wanted to add features such as search, pagination and my own admin dashboard. On the other hand, I wanted to show others how to custom build a blogging platform. I used my personal site as an example but I really wanted to teach users how to build in their own rich text editor, slug fields, ect.

My hope is not that everyone builds their own website like me, but knows how these features are built for a future project where they may need them.