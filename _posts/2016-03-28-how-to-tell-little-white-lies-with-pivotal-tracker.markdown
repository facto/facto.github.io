---
layout: post
title: "How to Tell Little White Lies with Pivotal Tracker"
date: 2016-03-28T14:38:52-07:00
---

[Estimates are always lies](http://softwareforgood.com/estimates-lies/). But let's forget about that for a second.

I've used [Pivotal Tracker](https://www.pivotaltracker.com) for many years and find that it still provides tremendous value. There's an age-old debate: **which story point method should I use when estimating?**

I think the more important question is: What do those values mean? A little googling will quickly reveal that almost every developer has their own interpretation.

I prefer the fibonacci sequence (0,1,2,3,5,8), and this is how I interpret it:

---

**0:** Trivial and directly affects and is noticeable by the user (e.g., fixing a typo, altering some copy).

**1:** Everything is known, and the feature is straightforward.

**2:** Everything is known, and the feature has some complexity.

**3:** There's a good idea of how to move forward, but there's an integration or some other aspect that may add unforeseen complexity.

**5:** Too high-level and/or involves a large amount of complexity. Needs to be planned and possibly spiked.

**8:** Pie-in-the-sky

---

**Nothing above a 3 should ever be delivered.** In other words, 5s and 8s should always be broken down. The resulting stories will often add up to more than 5 or 8. That's ok.

The only thing I'd change about this process involves 5s and 8s. They should really be 20s and 50s to better reflect what they turn out to be in practice.

**Remember: estimates are always lies. However, they can be little white lies that help us come a little closer to the truth.**
