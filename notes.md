# Namaste Node.js

## 1. Introduction

### What is Node.js?
- Node.js is JavaScript runtime environment built on Chrome V8 Engine.
- Open Source.
- Cross Platform.
- Executes JavaScript code outside a web browser.
- Has Event Driven Architecture.
- Non Blocking IO (Asynchronous I/O).

### History
- Developed by Ryan Dahl (in 2009).
- Initially used Spider Monkey (by Firefox) after 2 days of working on it he moved to V8 (by Google Chrome).
- Initial name of Node.js was Web.js.
- Most companies were using blocking server - Apache HTTP Server and he wanted to create non-blocking server.
- In 2010, NPM (Node Package Manager) was  happened which was developed by the person named - Issac... and Node.js got boost and popularity.
- Till this time, Node.js was built only for MacOS and Linux. In 2011, Joyent(which is parent company of Node.js) + Microsoft deal happened and it became accessible for bigger developer community.
- 2012 - Ryan left the project and Issac was given the responsibility of Node.js, then developement speed and release was slow down.
- In 2014, A person named, Fedor created fork of node.js and named it as IO.js and started contributing heavily. So there was confusion in developers.
- Sept. 2015, Both merged and "Node.js Foundation formed".
- In 2019, JS Foundation and Node.js Foundation merged and formed "OpenJS Foundation" which is maintaining Node.js.

## 1. JS on the Server
- JS Engine is written in C++
- Node.js is simply C++ application with V8 engine embedded into it.
- V8 can be embedded in Any C++ aplication.
- V8 needs to follow ECMA Standards.
- When we write code in high level language like JS, C++ (JS Engine) converts that code in machine code which in understood by computer in binary (0s and 1s).