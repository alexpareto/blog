---
layout: post
title: "Choosing a Tech Stack"
published: true
---

The best tech stack for a startup is the one that lets our team be the most productive. We get a lot of things with productivity: we can ship more, find product market fit faster, avoid running out of runway, and be happier.

So what’s the framework for choosing a tech stack that we can be productive with? After spending some time thinking about the common themes in past choices, I came up with a framework to use when making these decisions. It's detailed below (and is still evolving).

## The Framework

First we need to figure out two things:

1. Who will be using this tech stack?
2. What are we building?

These two question are important because they shape the four guidelines to follow when looking for a tech stack:

1. Use what we already know
2. Don't reinvent the basics
3. Choose something that scales for performance and for hiring
4. Follow the leaders

Let's dive into these in a bit more detail.

### Use What We Already Know

This is the first trait because it's likely the most important. Spending time learning new technologies can be a huge slow down on productivity early on in a project. Even when we do get up to speed, it can take years to understand all the nuances of a new language or technology.  If we already know the technology, we will debug problems faster, find solutions more quickly, and be more productive.

This is why knowing who will use the tech stack is important. If the whole team is extremely proficient at Angular and nobody knows React, then the team will build an Angular MVP much faster than a React one.

### Don't Reinvent the Basics

"Basics" is intentionally vague. This looks very different for various projects. If a "basic" tool in our application is concurrency, then Go may be a better choice than Python. On the other hand if a basic primitive in our application is lots of CRUD endpoints, perhaps using a framework like Rails or Django is a better choice. 

In general, it is possible to implement these "basics" in most languages (if we use what we know), but this time could also be spent talking to customers or getting closer to product/market fit. The best stack lets us not think about the basics and focus on building what makes our application unique instead.

### Choose Something That Scales for Performance and for Hiring

This becomes important after we hit product market fit and start to grow the company. The less we have to think about optimizing the performance of our application, the more differentiating features we can ship. 

Thinking about hiring is also important. If we choose an obscure language or technology - for example, a Graph DB over a relational one - we will have a lot harder time recruiting and hiring. I've found the [most wanted and most loved lists](https://insights.stackoverflow.com/survey/2020#most-loved-dreaded-and-wanted) on Stack Overflow for languages and frameworks to be a good measure of this.

### Follow the Leaders

Following the leaders means that the stack is in use by other companies in the industry. I like to look to other startups in the space that have successfully scaled and were founded relatively recently. Having a tech stack supported by other industry veterans means that we know some things out of the box:

1. It will scale for hiring and performance (it's already been done)
2. There will be a large community for support and help

[StackShare](https://stackshare.io/) is a good source to find information about what technologies are in use by various startups and larger companies. The other place would be companies' careers pages (see what technology they look for in hiring). 

Some of my more recent favorites: Brex (Elixir/Postgres/React), Notion (Node/Postgres/React), Retool (Node/Postgres/React).

If we have a tech stack that satisfies the above, we'll be in a great position to start shipping, iterating, and talking to customers. 

---

I'd love to hear thoughts on this, especially if others have useful guidelines that are missing. Shoot me an email (hey@alexpareto.com) or find me on Twitter @alexpareto. 
