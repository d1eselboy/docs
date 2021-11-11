# How to add relation to multiple objects

### **Using a Type**

Let's look on example. Say you need to add a new relation `Color,` to your **Type** `Cat`. And you already have 10 objects of this type.&#x20;

1. You need to open [library.md](../fundamentals/library.md "mention")
2. Find and open the [type](../fundamentals/type/ "mention") `Cat`
3. Add a new [relations.md](../fundamentals/relations.md "mention") `Color` there.

When you open any object `Cat` you will find `Color` in relations view and in `/` menu.

{% hint style="warning" %}
You cannot edit the default relations in types** created by Anytype**. But you can use [sets.md](../fundamentals/sets.md "mention"), which also create relation in existing objects.
{% endhint %}

### **Using a Set**

Say you need to add the relation `Related` to all your `Tasks`. You can't change the default relations for this Type.&#x20;

1. [#creating-sets](../fundamentals/sets.md#creating-sets "mention") with type Task&#x20;
2. Add a new column. Settings → Relations → **+ **→ `Related`
3. Each object in the Set will now show this relation. Also see will see at as **suggested** in each object.

![](../.gitbook/assets/test.gif)

