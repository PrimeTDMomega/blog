---
author: primetdm
pubDatetime: 2024-02-24T15:22:00Z
modDatetime: 2023-12-24T09:12:47.400Z
title: Why NextJS is actually Garbage
slug: nextjs-is-trash
featured: true
draft: false
tags:
  - reactjs
  - javascript
  - frameworks
  - nextjs
description: My hate for NextJS
---

# Why NextJS is actual garbage

![NexJS PHP MEME](https://preview.redd.it/k3b8cs0ob8ya1.jpg?width=640&crop=smart&auto=webp&s=4f62461779307bb42ed59f83f2e91e6cf994a976)

TLDR; NextJS is designed for specific common use cases where much of a website or app is static content. It is also young and lacks many features that would emerge in a more mature framework.

I tried out NextJS for a new project to experiment and familiarize myself with its ecosystem.

Two days in and I have found some things that are deal breakers for me. These two things are what made me stop and delete my app and consider my experimenting complete.

Fast refresh does not work with many third party libraries. You cannot disable it. Browsing the GitHub issues shows people who have wasted entire weeks with vague bugs introduced by this feature not playing well with libs. The NextJS contributors don't care. They think the internet must use their philosophies or fuck off.

https://github.com/vercel/next.js/discussions/25712

The app lifecycle does not have a feature to run code once on startup. There are many reasons to do this. My example is to check that the database I'm connecting to has the correct structure and validation rules in place. The solutions offered are to use a custom server which negates a lot of the reason to use NextJS in the first place.

https://github.com/vercel/next.js/discussions/15341

Being only 2 days in and finding this kind of situation is very worrying if you're going to try and use a framework for production quality apps. It starts the question in my mind: If I continue with this, what awful things will I find in a week or two? A month?

Be careful with your stack choices!
