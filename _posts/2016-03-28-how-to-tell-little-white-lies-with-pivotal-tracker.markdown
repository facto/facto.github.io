---
layout: post
title: "How to Tell Little White Lies with Pivotal Tracker"
date: 2016-03-28T14:38:52-07:00
---

[Estimates are always lies](http://softwareforgood.com/estimates-lies/). But let's forget about that for a second.

I've used [Pivotal Tracker](https://www.pivotaltracker.com) for many years and find that it still provides tremendous value. There's an age-old debate: Which story point scale should I use when estimating? Is the default setting (Linear, or 0,1,2,3) sufficient?

I think there's more important question: **What do story point values *mean?***

This turns out to be pretty tricky. A little googling will quickly reveal that almost every developer has their own interpretation.

The answer needs to provide conceptual tools to aid our estimation efforts, not hinder them, or worse, frustrate us to the point of abandoning them altogether.

Keeping in mind that there's no such thing as perfection in Estimation Land, consider the fibonacci sequence (0,1,2,3,5,8) interpreted as follows:

---

**0:** Something trivial which directly affects and is noticeable by the user (e.g., fixing a typo, altering some copy).

**1:** A feature about which everything is known, and implementation is straightforward.

**2:** A feature about which everything is known, and there's some complexity involved.

**3:** A somewhat fuzzy feature. There's a good idea of how to move forward, but there's an integration or some other aspect that may add unforeseen complexity.

**5:** A feature that needs to be planned. It's too high-level and/or involves a large amount of complexity. Some exploratory work may need to be done.

**8:** A pie-in-the-sky feature. There's lots of discussion, exploration and planning to be done.

---

I find this fulfills my requirements for a useful estimation method.

Also, consider these meta rules:

1. **Nothing above a 3 should ever be started.** This means that 5s and 8s should always be broken down. The resulting stories will often add up to more than 5 or 8. That's ok.

2. Furthermore, **try not to put 5s and 8s in the backlog**. I find they skew the overall point count. They should really be 21s and 55s to better reflect what they often turn out to be in practice.

**Remember: estimates are always lies. However, they can be *useful* little white lies that help us inch closer to the truth.**
