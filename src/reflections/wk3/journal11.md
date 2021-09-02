# An Intro to Javascript Proxy Objects

**What are the two common operations that we will set in the handler?**

We will be using the console.log() and the return operations often in the handler.

**What do you have to make sure you are doing with every Get to insure the value does not become undefined?**

The get operator returns the value of the key inside the object. So you need to return the keys passed into the get operator.

**What are some of the benefits of the proxy object that we are using in our structure for applications?**

The proxy object we are using allows us to add an extra layer of security to our data. You have to go through the proxystate if you wanna talk to the data. 

**Afternoon Challenge**

https://nicksondrup.github.io/fall21-gregslist-1/