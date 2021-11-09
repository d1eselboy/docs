---
description: Does the page become included into another when you creating a link?
---

# Can pages be nested one to another?

Let's look on example

> * I have page A.
> * In page A I had a link to an existing page B.
> * Then I moved page B inside page A (`move to` action).
> * At this point, on page A, I starting to have a link to page B.

We have no nesting  for [objects.md](../fundamentals/objects.md "mention"). So they doesn't include/store other objects.

All Anytype structure based on linking between objects. Links are directional, so you know that page A links to → page B. But you can make the link in the opposite way if you need that.&#x20;

You can create [relations.md](../fundamentals/relations.md "mention") `father` and `daughter.` And A will be father of B, and B — daughter of A.

So all objects connections will soon look like a an interconnected network:

![Some objects have links from completely different context](<../.gitbook/assets/Screenshot 2021-11-09 at 12.54.59 (1).png>)

