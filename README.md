<div id="top"></div>

<!-- PROJECT SHIELDS -->
<br/>
<p align="center">
    <img src="https://github.com/chrisdelmoro/42cursus/blob/main/resources/repo/webserve.png" alt="Logo" width="150" height="150">

  <p align="center">
    A project to reimplement a basic Nginx http server.
    <br/>
    <img src="https://img.shields.io/badge/Mandatory-OK-brightgreen"/>
    <img src="https://img.shields.io/badge/Final%20Score-100-blue"/>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The Webserv project at École 42 is designed to give students hands-on experience in developing a simple web server from scratch. This project focuses on several core aspects:

1. **HTTP Protocol**: Students learn about the Hypertext Transfer Protocol (HTTP), its request/response model, various HTTP methods (GET, POST, DELETE, etc.), status codes, and headers.

2. **Networking**: The project involves working with sockets, which are endpoints for sending and receiving data across a network. Students learn how to create, bind, listen to, and manage connections using sockets.

3. **Concurrency**: Handling multiple simultaneous connections is a key part of the project. Students explore concepts such as multi-threading or multi-processing to manage concurrent client requests.

4. **Configuration Management**: Students create a configuration file for their web server, allowing customization of server behavior, such as specifying listening ports, server names, root directories, error pages, and other settings.

5. **Static and Dynamic Content Serving**: The server must be capable of serving static files (e.g., HTML, CSS, JavaScript) and potentially handling dynamic content generation via CGI (Common Gateway Interface) scripts.

6. **Error Handling**: Proper handling and returning of appropriate HTTP error codes and messages for various client and server errors are emphasized.

7. **Security Considerations**: Basic security measures, such as preventing directory traversal attacks and ensuring proper input validation, are part of the project.

The Webserv project provides students with a comprehensive understanding of web server architecture, HTTP, and networking fundamentals. It emphasizes practical skills and problem-solving, preparing students for real-world web development and networking challenges.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* C++

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Setting up the server is easy.

### Prerequisites

Make sure you have the c++ compiler installed and make as well. 


<!-- USAGE EXAMPLES -->
## Usage

Simply access the root of the repository on your CLI of choise and run:
```sh
make
```

Other than that, the server works rather similarly to the real Nginx server. You can change several configuration aspects of it by customizing the files within the 'configuration' folder, especially through server.toml.

By default, the server will be listening on three different ports. This was done to show different use cases and scenarios during the evaluation process of the project. These ports are 8081, 8000, and 3001.

By accessing ports 8000 or 3001 on your localhost, you will find a static demo website running. Port 8081 will not return the page because it is configured to only accept incoming connections from the "youtube.com" domain. I imagine no one with actual access to it will ever run this server. 🤣🤣🤣

On the demo page, you will find several buttons to demonstrate the server's capabilities, such as a calculator and a current bitcoin value display, to show the abilities of the server to run basic dynamic content using CGIs. On the calculator, if you provide two numbers that result in a sum of 42, it will trigger an easter egg. This is to show how the server can handle errors.

You will also find the ability to upload files to the server as well as browse previously uploaded files on the server.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the [GNU General Public License version 3 (GPLv3)](https://www.gnu.org/licenses/gpl-3.0.html). 

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Christian C. Del Moro - christian.delmoro@protonmail.com

Project Link: [https://github.com/chrisdelmoro/webserv](https://github.com/chrisdelmoro/webserv)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot]: ../images/screenshot.png
