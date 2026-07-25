# Assignment
Module 1: PCCST501 – Computer Networks

## Title
How the Internet Delivers a Web Page

## Objective
To briefly explain the process of loading a website (Amazon), covering TCP/IP, DNS, HTTP, TCP, and cookies.

## Solution

**1. TCP/IP Protocol Stack**
A 5-layer model for internet communication:
* **Application:** User interface (HTTP, DNS).
* **Transport:** Reliable data delivery (TCP).
* **Network:** Routes packets via IP addresses.
* **Data Link:** Moves data locally via MAC addresses.
* **Physical:** Hardware transmission (cables, Wi-Fi).

**2. Role of DNS**
Translates a domain name (`www.amazon.com`) into an IP address (`205.251.242.103`) so the browser can locate the server.

**3. HTTP**
The browser (client) sends a GET request, and the server replies with an HTTP response containing the webpage files.

**4. TCP**
Ensures reliable delivery by tracking packets, retransmitting lost data, and managing network congestion.

**5. Architecture**
**Client-Server**. Your browser is the client requesting data; Amazon's computers are the servers providing it.

**6. HTTP vs. FTP**
HTTP uses one connection to view web pages. FTP uses two connections (control and data) to transfer raw files.

**7. Cookies**
Cookies remember session data. Example: Amazon uses a cookie to remember what you put in your shopping cart, even if you aren't logged in.

**8. Flow**
URL Typed -> DNS Lookup -> TCP Handshake -> HTTP GET Request -> Server Processes -> HTTP Response -> Browser Renders Page.

## Output
The Amazon homepage successfully loads and displays on the user's screen.

## Conclusion
Application-layer protocols like HTTP and DNS are vital for a user-friendly internet. They translate complex network processes into seamless everyday tasks, working with the TCP/IP stack to ensure reliable and efficient web browsing.
