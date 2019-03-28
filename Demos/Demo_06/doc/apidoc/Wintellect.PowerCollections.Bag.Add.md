---
uid: Wintellect.PowerCollections.Bag`1.Add(`0)
remarks: *content
---

_Adding an item takes approximately constant time, regardless of the number of items in the bag_

How use it:
```C#
// Simple initialization
Bag<string> bag1 = new Bag<string>(StringComparer.InvariantCultureIgnoreCase);

bag1.Add("Hello");
bag1.Add("foo");
bag1.Add("");
bag1.Add("HELLO");
bag1.Add("foo");
bag1.Add(null);
bag1.Add("hello");
bag1.Add("Eric");
bag1.Add(null);
```