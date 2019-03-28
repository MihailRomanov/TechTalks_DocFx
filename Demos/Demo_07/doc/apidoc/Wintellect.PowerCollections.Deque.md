---
uid: Wintellect.PowerCollections.Deque`1
seealso: 
  - linkType: HRef
    linkId: "xref:Wintellect.PowerCollections.Bag`1.Add(`0)"
    altText: "Bag.Add(`0)"
  - linkType: HRef
    linkId: "xref:queue_intro"
    altText: "Queue theory"
remarks: *content
---

The **Deque** class can also be used as a more flexible alternative to the [Queue](xref:System.Collections.Generic.Queue`1) and [Stack](xref:System.Collections.Generic.Stack`1) classes. 

- Deque is as efficient as Queue and Stack for adding or removing items, but is more flexible: it allows access to all items in the queue, and allows adding or removing from either end.
- Deque is implemented as a ring buffer, which is grown as necessary. The [size of the buffer](xref:Wintellect.PowerCollections.Deque`1.Capacity) is doubled whenever the existing capacity is too small to hold all the elements.