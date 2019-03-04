# Introduction to Web Development

*Speaker- Chetan Surana R*

*Slides used in the session can be viewed [here](https://slides.com/cynergycodingclub/introtocp-4)*

*We also built a sample HTML file which can be found [here](https://github.com/cynergy-ruas/Web-Dev-Series/blob/master/index.html)* <br>**This file is the session task which is to be completed by everyone before next-session**

## Purpose of the Workshop

From this workshop series we shall explore and master the technology that makes the web run, the terminology involved, and how it all comes together to power the websites we know and love. 
The session covers the following topics: 

- What the web is 
- How it works 
- Basic architecture of Web-Apps 
- Web Application we will be building throughout the series

## What exactly is Web

- The world wide web was invented by Sir Tim Berners-Lee. 
- He was trying to find a new way for scientists to easily share the data from their experiments. It is the leading information retrieval service of the Internet (q.v.; the worldwide computer network). 
- The Web gives users access to a vast array of documents that are connected to each other by means of hypertext or hypermedia link.
- Tim suggested three main technologies that meant all computers could understand each other (HTML, URL and HTTP).

## Web and Internet : TWO DIFFERENT THINGS

- Most people assume they're the same thing, but they're not. 
- The Internet is a term that's used to refer to a massive network of millions of computers all over the world that are used to share and transmit information. This is done through various protocols and languages and includes things like email, SMS messaging, application data, as well as the web itself. 
- The World Wide Web, which is usually shortened to just the web, is way of transmitting data over the Internet using the HTTP protocol and HTML. 
- ***The Internet is infrastructure while the Web is service on top of that infrastructure.*** 

## What is the all HYPE-* about

- Hypertext is text which contains links to other texts.
- HTML (Hyper Text Markup Language): The publishing format for the web. It includes the ability to format documents and link to other documents and resources.
- HTTP (Hypertext Transfer Protocol): Allows HTML documents to be requested and transmitted between browsers and web servers via the internet. 
- *URL is a kind of 'address' that is unique to each resource on the web. It could be the address of a webpage or an image file.*

## Two Sides of the communication

- *Clients are the devices that request and render web content*. Popular clients include browsers, mobile applications, screen readers, and the various content aggregators. 
- *Servers are applications that deliver web content or services to clients*. There is a wide range of web servers and types that specialize in specific types of data or specific processing capabilities.

## Web application architecture

- Client Side: Developed in HTML, JavaScript and CSS and existing within the user’s web browser, it doesn’t need any specific OS/device-related adjustments.
- Server-Side: app logic, or the main control center, and database, where all persistent data is stored

### One web server (with database): 

Simplest and the most risky model. If the server goes down, so does the web app. Good for testing.

### Two+ web servers, one database:

The idea is for a webserver not to store any data: even when it gets information from a client, the webserver processes it, writes the data to the database, and forgets about it. This is also known as ‘stateless architecture’. With at least two web servers, you avoid a single point of failure. 

### Two+ web servers, two+ databases:

Databases store identical data or have the data evenly distributed among them. In the first case, no more than 2 databases is usually needed; when one is down, the other can replace it, loss-free. Since data aren’t replicated in the second case, some data may become temporarily unavailable if one of the many databases crashes.

## Diving deep in the development part:

- When we discuss the “frontend” of the web, what we’re really talking about is the part of the web that you can see and interact with. The frontend usually consists of two parts: 
  - the web design and 
  - front end web development.
- The backend usually consists of three parts: 
  - a server, 
  - an application, and 
  - a database. 

*If you book a flight or buy concert tickets, you usually open a website and interact with the frontend. Once you’ve entered that information, the application stores it in a database that was created on a server.* 

*For sake of ease, just think about a database as a giant Excel spreadsheet on your computer, but your computer (server) is stored somewhere in Arizona (because its cold there :p).*
*All of that information stays on the server so when you log back into the application to print your tickets, all of the information is still there in your account.*

**We call a person that builds all of this technology to work together a backend developer**. 

*Backend technologies usually consist of languages like PHP, Ruby, Python, etc. To make them even easier to use they’re usually enhanced by frameworks like Ruby on Rails, Cake PHP, and Code Igniter that all make development faster and easier to collaborate on.*

## What we will build throughout the series?

[Here is the link of the full-fledged web application which we might be able to complete.](https://codingninjas.in)

## Some resources to get started:

- Session Slides: https://slides.com/cynergycodingclub/introtocp-4#/
- Fast -track online video course: https://www.edx.org/course/html5-and-css-fundamentals-2
- Extensive web devlopment training and certificates too: https://freecodecamp.com
- Hands on experience from screencast: https://scrimba.com/g/ghtml, https://scrimba.com/g/gintrotocss
- Best Resource to learn git: https://www.codecademy.com/learn/learn-git
- Hands on experience from web tutorial based (no video): https://www.codecademy.com/learn/learn-html, https://www.codecademy.com/learn/learn-css
- For learning any specific language: https://exercism.io
- For learning various parts of web developments (you have to search a bit in this): www.w3schools.com
- Best Resource to learn anything: GOOGLE.COM
- Want a roadmap or guidance: contact [CYNERGY Coding Club](https://cynergy-ruas.github.io)

