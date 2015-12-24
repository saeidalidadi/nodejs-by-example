# nodejs-by-example
A summary from Node.js By Example book by Krasimir Tsonev that is a good reference for all want to learn *Node.js* as a new language for web server development.
## Preface
The fact that we use the same languae (javascript) on both the *server* and client-side make development fluent.
This book contain a step-by-step guide to building a *social network*.
The book covers basic phases such as the *architecture* and management of the assets pipeline, and it discusses features such as *users friendship* and *real-time communication*.
## Chapter 1: Node.js Fundamentals
- Node.js is one of popular javascript-driven technologies nowdays.
- It was created in 2009 by Rayan Dahl.
- Its package manager (NPM) is full of usefull modules.

In this chapter we will learn about:
* Node.js building blocks
* The main capabilities of the envirenment 
* The package management of Node.js -- `NPM`

### Node.js Architecture
* Node.js like other high performance servers architecture has an event loop operation with non-blocking input/output
* Most of the servers written in Java or C use multithreading.this means that they process every request in a new thread.
* Node.js use a single-thread architecture, this means that all the request that come to server are processed by a single-thread.
* Node.js is scalable and to achieve this we just have to run diffrenet Node.js processes and use a load blancer that distributes the requests between theme.

### Installing Node.js
For fast and easy way installation visit [https://nodejs.org/download](https://nodejs.org/download) and downlad appropriate installer for your operation system.

Node.js is avalable in APT package manager.
the following commands will install Node.js and Node Package Manager (NPM):
```
sudo apt-get update
sudo apt-get install nodejs
sudo apt-get install npm
```

