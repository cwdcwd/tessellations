## Tessellations Series. Pattern... The First!
### The Abstract Factory Pattern

It's taken me a while to pick th first pattern to run with for this series. There's so many great patterns but the one I figured that will lead us better to the next pattern is the... *Abstract Factory*.

This pattern is important and foundational. Let me state, according to the GoF, the intent of this pattern: 
"[To] provide an interface for creating families of related or dependent objects without specifying their concrete classes"

Well that's swell, ain't it? What this means, in a practical sense, is 1) that we'd like to abstract things in such a way that we don't have to specify their implementation and 2) make them related in such a way that we can swap them in and out in our applications. 

We develop a factory that, just like a real world factory, churns out widgets that we know subscribe to a well defined set of specifications. The rest is details that frankly, to our application, we're not concerned with. All we're concerned with is the prescribed interface to deal with these widgets. The reason I like this factory as a first pattern is that concept is, in my opinion, the heart and soul of OOP. I don't care about how this black box works but I know I can do certain things with it. 

Enough abstract talk though, let's get to specific (oh, the irony).  

