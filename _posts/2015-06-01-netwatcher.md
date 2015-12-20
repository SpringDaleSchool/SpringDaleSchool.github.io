---
title: "NetWatcher"
repository:
  name: "github.com/jsidrach/NetWatcher/"
  url: "https://github.com/jsidrach/NetWatcher/"
libraries:
  - name: "node.js"
    url: "https://nodejs.org/"
  - name: "Bootstrap"
    url: "http://getbootstrap.com/"
  - name: jQuery
    url: "https://jquery.com/"
languages: [PHP, HTML, JavaScript, CSS, bash]
---
Web-based interface to manage FPGA network probes (devices capable of capturing or injecting network traffic).
The project also brings together other relevant aspects of the capture and injection of web traffic, such as trace storage management, write speed of the used disks or trace format detection and conversion.
NetWatcher is divided in two parts: a (REST-like) web service to execute commands in the FPGA and monitor it, and a graphical web interface to connect to this service, make calls to it visually and display the results.
It was developed as an End-of-Degree Project in collaboration with the [High-Performance Computing and Networking](http://www.hpcn.es) research group.
