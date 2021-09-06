# Observing the Observer Pattern

**What problems does the Observer Pattern seek to solve?**

The Observer Pattern seeks to solve the problem of updating a page in response to events and data. 

**What are the three mechanisms of the observer pattern?**

The subscribe method, the unsubscribe method, and the broadcast method.

**Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.**

the bcw-template uses the proxy object and encapsulation to protect the data inside the appstate, then uses the observer pattern to respond to events by using the subscribe method to draw information back to the screen.

**Afternoon Challange:**

https://nicksondrup.github.io/sportinggood-store/