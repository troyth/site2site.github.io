---
title: Client-Server Model
layout: lecture
perex: Client-server model lecture notes
---
#### The web is built upon a set of protocols (such as HTTP) and languages (such as HTML, CSS and Javascript) that employ the physical network connections and protocols that make up the Internet according to a client-server model. The client takes the form of a browser on the user's machine. The server is a remote computer that stores the files required to render web pages.

*   ![Client Server 2](https://raw.github.com/site2site/site2site.github.io/master/images/lectures/client-server-model/client-server-2.gif)

*   **Client-Server Model**
	
	The general idea is this: the Internet connects a client request to the server corresponding to the URL that sends the response that the browser renders as a web page

*   ![Client Server 3](https://raw.github.com/site2site/site2site.github.io/master/images/lectures/client-server-model/client-server-3.gif)

*	The client sends an HTTP request (GET, POST, PUT or DELETE) to the Internet in the form of a URL

*   ![Client Server 4](https://raw.github.com/site2site/site2site.github.io/master/images/lectures/client-server-model/client-server-4.gif)

*	The Domain Name System (DNS) is used to decode the URL into the Internet Protocol (IP) address of the server

*	![Client Server 5](https://raw.github.com/site2site/site2site.github.io/master/images/lectures/client-server-model/client-server-5.gif)

*	Once the IP address is resolved, the server at that address is sent the client's request

*	![Client Server 6](https://raw.github.com/site2site/site2site.github.io/master/images/lectures/client-server-model/client-server-6.gif)

*	The web server - a program such as Apache, nGinx, Node.js - listens for requests and routes them to the correct folder to retrieve the requested file

*	![Client Server 7](https://raw.github.com/site2site/site2site.github.io/master/images/lectures/client-server-model/client-server-7.gif)

*	The server then returns an HTTP response with the requested file

*	![Client Server 8](https://raw.github.com/site2site/site2site.github.io/master/images/lectures/client-server-model/client-server-8.gif)

*	The client browser receives the response, checks that the status code is ok, and then begins to render the page

*	![Client Server 9](https://raw.github.com/site2site/site2site.github.io/master/images/lectures/client-server-model/client-server-9.gif)

*	The HTML file is made up of two main parts, the <head> and the <body>. The <head> contains meta-data about the page, dependencies, and other information such as the page title that shows up in the browser tab. The <body> contains the page content. See this Gist with the standard HTML structure.

*	<script src="https://gist.github.com/troyth/4699954.js"></script>

*	![Client Server 10](https://raw.github.com/site2site/site2site.github.io/master/images/lectures/client-server-model/client-server-10.gif)

*	The example above show how and where different blocks of HTML are rendered in the browser.