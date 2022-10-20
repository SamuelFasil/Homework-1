# Notes 2
## 1, What is DNS?
The Domain Name System (DNS) is the phonebook of the Internet. Humans access information online through domain names, like nytimes.com or espn.com. Web browsers interact through Internet Protocol (IP) addresses. DNS translates domain names to IP addresses so browsers can load Internet resources.
Each device connected to the Internet has a unique IP address which other machines use to find the device. DNS servers eliminate the need for humans to memorize IP addresses such as 192.168.1.1 (in IPv4), or more complex newer alphanumeric IP addresses such as 2400:cb00:2048:1::c629:d7a2 (in IPv6). 

### How does DNS work?

The process of DNS resolution involves converting a hostname (such as www.example.com) into a computer-friendly IP address (such as 192.168.1.1). An IP address is given to each device on the Internet, and that address is necessary to find the appropriate Internet device - like a street address is used to find a particular home. When a user wants to load a webpage, a translation must occur between what a user types into their web browser (example.com) and the machine-friendly address necessary to locate the example.com webpage. In order to understand the process behind the DNS resolution, it’s important to learn about the different hardware components a DNS query must pass between. For the web browser, the DNS lookup occurs "behind the scenes" and requires no interaction from the user’s computer apart from the initial request.

The Hypertext Transfer Protocol (HTTP) is an application layer protocol in the Internet protocol suite model for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web, where hypertext documents include hyperlinks to other resources that the user can easily access, for example by a mouse click or by tapping the screen in a web browser.

Development of HTTP was initiated by Tim Berners-Lee at CERN in 1989 and summarized in a simple document describing the behavior of a client and a server using the first HTTP protocol version that was named 0.9.[2]

That first version of HTTP protocol soon evolved into a more elaborated version that was the first draft toward a far future version 1.0.

Development of early HTTP Requests for Comments (RFCs) started a few years later and it was a coordinated effort by the Internet Engineering Task Force (IETF) and the World Wide Web Consortium (W3C), with work later moving to the IETF.

HTTP/1 was finalized and fully documented (as version 1.0) in 1996. It evolved (as version 1.1) in 1997 and then its specifications were updated in 1999 and in 2014.
Its secure variant named HTTPS is used by more than 80% of websites.

HTTP/2, published in 2015, provides a more efficient expression of HTTP's semantics "on the wire". It is now used by 43% of websites[7] and supported by almost all web browsers (over 97% of users). It is also supported by major web servers over Transport Layer Security (TLS) using an Application-Layer Protocol Negotiation (ALPN) extension where TLS 1.2 or newer is required.

HTTP/3, the successor to HTTP/2, was published in 2022. It is now used by over 25% of websites and is supported by many web browsers (over 75% of users). HTTP/3 uses QUIC instead of TCP for the underlying transport protocol. Like HTTP/2, it does not obsolesce previous major versions of the protocol. Support for HTTP/3 was added to Cloudflare and Google Chrome first, and is also enabled in Firefox. HTTP/3 has lower latency for real-world web pages, if enabled on the server, load faster than with HTTP/2, and even faster than HTTP/1.1, in some cases over 3× faster than HTTP/1.1 (which is still commonly only enabled).

HTTP: No Data Encryption Implemented
Every URL link that begins with HTTP uses a basic type of “hypertext transfer protocol”. Created by Tim Berners-Lee back in the early 1990’s, when the Internet was still in its infancy, this network protocol standard is what allows web browsers and servers to communicate through the exchange of data.
## 2, HTTP and HTTPS
HTTP is also called “a stateless system”, which means that it enables connection on demand. You click on a link, requesting a connection, and your web browser sends this request to the server, which responds by opening the page. The quicker the connection is, the faster the data is presented to you.

As an “application layer protocol”, HTTP remains focused on presenting the information, but cares less about the way this information travels from one place to another. Unfortunately, this means that HTTP can be intercepted and potentially altered, making both the information and the information receiver (that’s you) vulnerable.

HTTPS: Encrypted Connections
HTTPS is not the opposite of HTTP, but its younger cousin. The two are essentially the same, in that both of them refer to the same “hypertext transfer protocol” that enables requested web data to be presented on your screen. But, HTTPS is still slightly different, more advanced, and much more secure.

Simply put, HTTPS protocol is an extension of HTTP. That “S” in the abbreviation comes from the word Secure and it is powered by Transport Layer Security (TLS) [the successor to Secure Sockets Layer (SSL)], the standard security technology that establishes an encrypted connection between a web server and a browser.

Without HTTPS, any data you enter into the site (such as your username/password, credit card or bank details, any other form submission data, etc.) will be sent plaintext and therefore susceptible to interception or eavesdropping. For this reason, you should always check that a site is using HTTPS before you enter any information.

In addition to encrypting the data transmitted between the server and your browser, TLS also authenticates the server you are connecting to and protects that transmitted data from tampering.

It helps me to think about it like this - HTTP in HTTPS is the equivalent of a destination, while SSL is the equivalent of a journey. The first is responsible for getting the data to your screen, and the second manages the way it gets there. With joint forces, they move data in a safe fashion.  

The Advantages and Disadvantages of HTTPS
As discussed above, HTTPS helps ensure cyber-safety. It is, without any doubt, a better network protocol solution than its older cousin, HTTP.

But, is HTTPS all about the advantages? Perhaps there’s a drawback to it all? Let’s find out.  

### The Advantages of Using HTTPS
The security benefits mentioned above - authenticating the server, encrypting data transmission, and protecting the exchanges from tampering - are the obvious main advantages to using HTTPS. Site operators want and need to protect their visitors data (HTTPS is actually a requirement for any sites collecting payment information according to the PCI Data Security Standard) and site visitors want to know that their data is being transmitted securely.

The growing demand for data privacy and security from the general public is another advantage to using HTTPS. In fact, according to We Make Websites, 13% of all cart abandonment is due to payment security concerns. Site visitors want to know that they can trust your site, especially if they are entering financial details, and using HTTPS is one way to do that (i.e. it’s one way to show your visitors that any information they enter will be encrypted).

HTTPS can also help with your SEO. Back in 2014, Google announced HTTPS as a ranking signal. Since then, some studies and anecdotal experience from companies who have implemented HTTPS indicate a correlation to higher rankings and page visibility.

Browsers are also jumping in on efforts to increase HTTPS usage by implementing UI changes that will negatively affect non-HTTPS sites. For example, Google announced earlier this year that Chrome by July (only a few months from now!) that they will mark all HTTP sites as non-secure.

## 3, What is an SSL Certificate?

SSL stands for Secure Sockets Layer and, in short, it's the standard technology for keeping an internet connection secure and safeguarding any sensitive data that is being sent between two systems, preventing criminals from reading and modifying any information transferred, including potential personal details. The two systems can be a server and a client (for example, a shopping website and browser) or server to server (for example, an application with personal identifiable information or with payroll information). It does this by making sure that any data transferred between users and sites, or between two systems remain impossible to read. It uses encryption algorithms to scramble data in transit, preventing hackers from reading it as it is sent over the connection. This information could be anything sensitive or personal which can include credit card numbers and other financial information, names and addresses. 

TLS (Transport Layer Security) is just an updated, more secure, version of SSL. We still refer to our security certificates as SSL because it is a more commonly used term, but when you are buying SSL from DigiCert you are actually buying the most up to date TLS certificates with the option of ECC, RSA or DSA encryption. HTTPS (Hyper Text Transfer Protocol Secure) appears in the URL when a website is secured by an SSL certificate. The details of the certificate, including the issuing authority and the corporate name of the website owner, can be viewed by clicking on the lock symbol on the browser bar.
