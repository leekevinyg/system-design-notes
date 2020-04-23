# Grokking The System Design Interview Notes

Notes for the Educative course [Grokking the System Design Interview](https://www.educative.io/track/scalability-system-design-for-developers)

- <a href="#Framework">Framework</a>

<a name="Framework"></a>
<h2>Framework</h2>

Design a Twitter Like Service

(1) **Clarify requirements**

System design questions are open ended. In a limited time interview scnerio, clarifying attributes and goals of a system allows us to focus on just on designing those parts. 

- Can users post tweets?
- Should we also design and create the user’s timeline?
- Can users follow other people?
- Do Tweets contain photos and video?
- Will users be able to search tweets?
- Will there be push notifications for tweets?

(2) **Back of the envelope estimations**

Helps later on when the focus is on scaling, partitioning, load balancing and caching.

- What scale is expected from the system? 
- How many new tweets? Number of tweet views? 
- Number of timeline generations per second?
- How much storage is needed?
- What network bandwidth usage are we expecting? (Important in deciding how to manage traffic and balance load between servers. Add details later.)

(3) **System interface definitions**

Establishes a contract for the system and verifies that you got the requirements right.
