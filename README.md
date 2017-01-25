As part of my faculty’s graduation project, I studied about End-to-End Encryption in browser for a messenger service. I researched a lot, trying to find the best library for doing the client encryption and I ended using Web Cryptography API, which is a W3C standard for encryption in browser that is very fast, complex and complete.

This is a demo chat application which aims to test the cryptographic wrapper that I've created. The cryptographic library is not present by the way, because of the confidential laws that apply to it, because the crypto system used was not designed by me, I worked only on it's implementation.

As a demo for presentation, I created a server in Node.js that connects to the ReactJS client through Socket.io and some simple Ajax requests.  
 
