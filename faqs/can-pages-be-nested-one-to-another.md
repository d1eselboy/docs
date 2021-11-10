---
description: >-
  Does the page become included into another when you creating a link or moving
  object?
---

# Can pages be nested one to another?

Let's look at on example:

> * I have object A.
> * In object A I had a link to an existing object B.
> * Then I moved object B inside object A (`move to` action).
> * At this point, on object A, I starting to have a link to object B. What's happened?

Answer: **they both starting to have links to each other**.

We have <mark style="background-color:red;">no nesting</mark>  for [objects.md](../fundamentals/objects.md "mention"). So object doesn't physically include/store other objects.

All Anytype structure based on linking between objects. Links are directional, so you know that page A links to → page B. You can make the link in the opposite way if you need that. You can't use classical hierarchy when files belong to folders and folders create a path. But you can make some of the objects Favourite so they will be accessible straight from Home.&#x20;

All objects connections will soon look like an interconnected network:

![Some objects have links from completely different context](<../.gitbook/assets/Screenshot 2021-11-09 at 12.54.59 (1).png>)

