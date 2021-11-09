# How can I add relations to all existing objects with one Type?

#### **Using the Type Store**

Let's look on example. Say you need to add a new relation `Color,` to your **Type** `Cat`. And you already have 10 objects of this type.&#x20;

1. You need to open **Library**
2. Find and open the [type.md](../fundamentals/type.md "mention") `Cat`
3. Add a new **Relation** `Color` there.

When you open any object `Cat` you will find a new relation in relations view.

{% hint style="warning" %}
You cannot edit the default relations in types** created by Anytype**. But you can use [set.md](../fundamentals/set.md "mention"), which also create relation in existing objects.
{% endhint %}

#### **Using a Set**

Say you need to add the relation `Progress` to all your `Tasks`. You can't change the default relations for this Type. But you can add a new column to the Set of this Type — a Set of Tasks — you will then see this relation suggested in each object.

Each object in the Set will now show this relation.
