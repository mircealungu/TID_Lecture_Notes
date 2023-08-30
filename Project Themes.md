
## Project 0: A Messaging Client
- You have to implement a variation of WhatsApp for a special audience?
- E.g. the elderly would want a very simple application, etc.

## Project 1: A Web-Based Client Decentralized Social Sharing Website 

nostr is a communication protocol that is very simple, and aims to encourage communication that is censorship-resistant. 
- [Readme.md](https://github.com/nostr-protocol/nostr)
- [Cutting through spam](https://www.reddit.com/r/nostr/comments/121ytwf/cutting_through_the_spam_on_damus/)

At its core, it allows cryptographically signed messages to be forwarded to other users. The most natural application to build on top of such a protocol would be an alternative to Twitter. The basic aspects of the protocol are very simple: a client sends events, and registers for streams of events. The most important type of event is a "message" event. 

You have to implement a `nostr` client for a specific type of user. 

There are already many existing `nostr` [clients](https://nostr.com/clients). 

## Project 2: A Centralized Social Sharing Website 

This is pretty much your chance to reimplement a Twitter-like project, but better :) And just as in the previous themes, make sure that you have a very specific type of user in mind. 

This version gives you the chance to practice more backend work than the de-centralized version, because in this case you implement all the data representation of your domain model with Parse.js -- a backend-as-a-service platform that makes it very easy to implement full-stack applications. And do not worry, we will show you how to work with Parse.js. 






