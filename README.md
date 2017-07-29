= Transaction Messaging (TRAM) framework

The TRAM framework enables a Java/Spring application to send messages as part of an database transaction.
This enables an application atomically update state and send a message or a domain event.
It is a foundation of ensuring data consistency within a [microservice architecture](http://microservices.io/patterns/microservices.html).

TRAM (which was formerly known as Tarr) is described in more detail in my book [Microservice Patterns](https://www.manning.com/books/microservice-patterns).
It provides several messaging abstractions:

* messaging - send and receive messages over named channels
* events - publish domain events and subscribe to domain events
* commands - asynchronously send a command to a service and receive a reply


== Documentation

TBD



