---
layout: post
title: History of Open Source
---

> Explain (in your own words) the difference between software development following the cathedral model and software development following the bazaar model; which of the two environments do you personally prefer?

The __cathedral model__ of software development represents a sort of authoritarian, closed model of development where a single developer or small closed group of developers work on a project with little to no external input. The __bazaar model__ is more open -- to contributions in terms of literal contributions to development, directions of the project, testing, etc.

Personally, I find it more comfortable working in the cathedral model sometimes because I think we can all become control freaks with our own work -- we want to dictate every aspect of everything when we believe that we know what's best for ourselves and our projects. However, I think the bazaar model is more valuable because no one person is omniscient enough to not benefit from external input, and the merits of collaborative work, while requiring more compromise and distance from the vision of an "individual wizard", are definitely apparent.

> The Cathedral and The Bazaar essay has 19 “lessons”. Pick two of these that you find to be the most intriguing, interesting, telling, or ones that you simply liked. Quote them in your blog and try to explain what they’re supposed to mean.

1. Treating your users as co-developers is your least-hassle route to rapid code improvement and effective debugging.

  I think that this is good advice -- often, as developers, we are annoyed at the ways that users interface with our projects. When someone points out a bug it's much easier to point the blame at someone else -- "well, it shouldn't be used like that ... it should be used like I intended" -- than to look inwards and admit you don't have a totalizing vision of every single way something could be used. Keeping users in mind while developing and getting users involved while developing can help make this process a little more natural / painless.

2. If you treat your beta-testers as if they're your most valuable resource, they will respond by becoming your most valuable resource.

  Doing QC / looking for bugs is not exactly a rewarding process -- it's pretty boring to comb through something just to make sure it works as it's intended in all possible cases. This doesn't mean that it isn't an important task!

> Comment on the discussion of free vs. open. In what ways are they similar and how are they different?

I think that the article by Richard Stallman made a lot of good points about divisions of ideology in the FOSS movement, but ultimately I felt like a lot of it was hyper-focused on semantics where I don't know if I honestly believe that the simple distinction of saying 'open source' over 'free software' can really foment the changes / indicate an individual's ideology in the way that Stallman tries to argue. Essentially, what I understood from the article, was that open source was more concerned with how something was made and not the users -- where free software is a more holistic, purpose-oriented view of software that incorporates the users more than open-source does. All free software is open-source, but not all open-source software is free software (some licenses allow for anti-free software behavior). While I think that Stallman makes some valid points I think he paints in broad strokes and hangs up on semantics more than he should. For example, when Patrick Masson came to speak about OSI, he definitely touched on and valued a lot of the 'free software' values that Stallman talked about.

> Blog about your personal progress towards the team project: what have you done, what did you learn, what are the tasks that you will be working on next week?

Last week I touched up some changes that Ashley made to my solution for the bug we picked out and we sent in a pull request. We got a response pretty quickly that pointed out a different, possibly more simple and platform-agnostic way to solve the problem, so this week we'll probably try to take that approach as well.
