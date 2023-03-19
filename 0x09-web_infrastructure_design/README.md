 Web infrastructure design
DevOps 
SysAdmin 
web infrastructure 

Concepts
For this project, we expect you to look at these concepts:

[DNS](https://intranet.alxswe.com/concepts/12)  
[Monitoring](https://intranet.alxswe.com/concepts/13)  
[Web Server](https://intranet.alxswe.com/concepts/17)  
[Network basics](https://intranet.alxswe.com/concepts/33) 
[Load balancer](https://intranet.alxswe.com/concepts/46)  
Server](https://intranet.alxswe.com/concepts/67).

Read or watch:

ensure you check all the concept pages
[What is a database](https://intranet.alxswe.com/rltoken/n3CdS3EA5l5psDDKbEhApA)  
[What’s the difference between a web server and an app server?](https://intranet.alxswe.com/rltoken/0as4wDlFqyhLhf0f_gedcw)  
[DNS record types](https://intranet.alxswe.com/rltoken/Pl3UoEfAO7K_jUKRLMmnAQ)  
[Single point of failure](https://intranet.alxswe.com/rltoken/uxpx2YhXs10TFLIDg78chA)  
[ow to avoid downtime when deploying new code](https://intranet.alxswe.com/rltoken/4ansLu2gtHnoFrNThqyObA)  
[High availability cluster (active-active/active-passive)](https://intranet.alxswe.com/rltoken/TAJeVYy9U9iLaEDd6XkbRA)  
[What is HTTPS](https://intranet.alxswe.com/rltoken/c0zs2MxrmxFLsCPOizxq6g)  
[What is a firewall](https://intranet.alxswe.com/rltoken/j6idMcUTyNEDj1oYDQFmUw)  

Tasks
0. Simple web stack
Description
This is a simple web infrastructure that hosts a website that is reachable via www.foobar.com. There are no firewalls or SSL certificates for protecting the server's network. Each component (database, application server) has to share the resources (CPU, RAM, and SSD) provided by the server.

Specifics About This Infrastructure
What a server is.
A server is a computer hardware or software that provides services to other computers, which are usually referred to as clients.

The role of the domain name.
To provide a human-friendly alias for an IP Address. For example, the domain name www.wikipedia.org is easier to recognize and remember than 91.198.174.192. The IP address and domain name alias is mapped in the Domain Name System (DNS)

The type of DNS record www is in www.foobar.com.
www.foobar.com uses an A record. This can be checked by running dig www.foobar.com.
Note: the results might be different but for the infrastructure in this design, an A record is used.
Address Mapping record (A Record)—also known as a DNS host record, stores a hostname and its corresponding IPv4 address.

The role of the web server.
The web server is a software/hardware that accepts requests via HTTP or secure HTTP (HTTPS) and responds with the content of the requested resource or an error messsage.

The role of the application server.
To install, operate and host applications and associated services for end users, IT services and organizations and facilitates the hosting and delivery of high-end consumer or business applications

The role of the database.
To maintain a collection of organized information that can easily be accessed, managed and updated

What the server uses to communicate with the client (computer of the user requesting the website).
Communication between the client and the server occurs over the internet network through the TCP/IP protocol suite.
