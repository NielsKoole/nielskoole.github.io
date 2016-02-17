---
layout: post
title:  "Speed up the factory - from a developer perspective"
date:   2016-01-29 16:00:00 +0100
categories: roadmap
---
Inside out.

So we have been struggling for a while to get our development up to speed. While we improve every day, there are always things you want to improve more. We found out that even when we work in bi-weekly sprints, we couldn't deliver features as fast as we wanted to. Therefore we decided to work in feature teams. Then we were able to pickup a feature and decide within the feature team what kind of releasable MLF (Minimum Lovable Feature) we could deliver in that sprint. So a great move to get insights in the progress of the app, result: every sprint a releasable set of features we could deliver to our customers and end-users.

This really helps us to make clear how we are performing as a team vs. deadlines we put ourselves up to. But maybe even more important, a feature team defines by itself what the deliverable will be. Read that line again. It's very important that the people who are building your product, stand behind the things they build and understand why they need to be built. Because this will make the team feel responsible for what they are delivering at the end of the sprint. That's what brings the company, the people and the product forwards.

Great. But as usual there are always some downsides. Since no feature team is always the same and you can be in multiple teams in one sprint, it's very important that everyone is able to keep a clear overview of his plate of work. This means that planning becomes a big part of your daily work as well. Not everyone would vouch for this, but we think this is a necessary capability in very changing environment. This makes the company more flexible to jump in whenever a new situation comes in place.

As an app developer I wanted to share some experiences which helped me a lot getting my stuff done. While waiting for feedback is killing your productivity, there are tools out there that really can help you out. I find it very important to get feedback as soon as possible. So therefore we started working with a tool called BuddyBuild. This is a CI tool that is able to build and deploy app releases (almost) out of the box. You can add your git repository, select the branch you want to build and start building. Our architecture works with Cocoapods and even that worked right away. And after setting up some webhooks, it was just a matter of pushing code to the git repository and within 15 minutes my stakeholders got an email to install the test release. BuddyBuild made it even possible to send feedback within the app by making screenshots and adding a comment that becomes visible in BuddyBuild. I think you should at least give it a try.

However you can optimize your time by getting your feedback as soon as possible, you'll see that there are always moments that you'll be held back from doing anything for the sprint. These moments are great to e.g. pick up bugs, fix some technical depth or start working on some nice features you've always wanted to do (or even write blogposts once in a while). If you don't have enough time to pick up non sprint related stuff, it's you who decides how you plan your next sprint.

Niels Koole
iOS developer at Roadmap
