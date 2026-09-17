# Week 06


## task 02 Create Web Pages in OpenWRT 
![date and Time](./image/week06_task02_data&time.png)


## task 03  Capture HTTP Packets 
![Capture Packet](./image/week06_task03_capture-packets.png)

## task 04 
ng `http` so I could focus on the HTTP traffic.

The browser sent HTTP GET requests when I opened the web pages. For example, it requested:

`GET /index.html HTTP/1.1`

The server responded with `HTTP/1.1 200 OK`, which means the requested page was found and successfully sent back.

The browser also requested my newly created page:

`GET /12345678.html HTTP/1.1`

The server again responded with `200 OK`, meaning the page was successfully received.

## b) Five Address Values

For the first HTTP request, I identified the following values:

- Source MAC: `08:00:27:14:87:98`
- Destination MAC: `0a:00:27:00:00:05`
- Source IP: `192.168.1.100`
- Destination IP: `192.168.1.10`
- Destination TCP port: `80`

These values identify the devices and the HTTP service being used.

## c) Date and Time Button

When I clicked the button to show the date and time, the browser did not send another HTTP request.

This was because the date and time were generated locally by JavaScript in the browser. The web server was not needed to provide this information.

## d) HTTP Request Packet

The HTTP request for my page was:

`GET /12345678.html HTTP/1.1`

The packet was made up of several layers:

```text
Ethernet Header – 14 bytes
        ↓
IPv4 Header – 20 bytes
        ↓
TCP Header – 20 bytes
        ↓
HTTP Request

The Ethernet header contained the source and destination MAC addresses. The IPv4 header contained the source and destination IP addresses. The TCP header used port 80 for HTTP.

The packet diagram was saved as:

week4task4-http.png

week4task4-http.drawio

e) Referrer
The Referer field showed the page that the browser came from.

Example:

Referer: http://192.168.1.10/index.html

This tells the server which web page the browser was viewing before requesting the new page. Servers can use this information for website statistics and understanding how users navigate between pages.

f) Browser Information
The HTTP request contained a User-Agent field. This gives the server information about the browser and operating system.

For example, it can identify that the browser is Google Chrome running on Windows.

g) HTTP Version and Transport Protocol
The capture used HTTP/1.1.

The transport protocol was TCP.

The protocol layers were:

HTTP
 ↓
TCP
 ↓
IPv4
 ↓
Ethernet

h) TCP Connection Setup
Before the HTTP data was transferred, TCP established a connection using a three-way handshake.

The three packets were:

SYN

SYN + ACK

ACK

The process was:

Client              Server
  |                   |
  | ----- SYN ------> |
  | <--- SYN/ACK ---- |
  | ----- ACK ------> |

In my capture, the connection started at approximately 1.250000 seconds and the HTTP data started at approximately 1.253500 seconds.

The difference was approximately 3.5 milliseconds.



# Task 05

- I used the developer tools in my web browser to look at the cookies stored by a website that I regularly visit. I did not include the actual cookie values because some of them can contain private or sensitive            information.

- The cookies stored different types of information about my browser and my activity on the website.

- Some of the information included:

- **Session information** – Cookies can contain a session ID that allows the website to recognise my browser while I am using the website.
- **Login or authentication information** – Some cookies help remember that a user has logged in, although the actual password is normally not stored in the cookie.
- **User preferences** – Cookies can remember settings such as language, region, theme or other preferences.
- **Shopping/cart information** – On some websites, cookies can be used to remember items added to a shopping cart.
- **Tracking information** – Some cookies are used to track visits and user activity. This can help the website understand how people use its pages.
- **Analytics information** – Cookies can be used by analytics services to identify returning browsers and collect information about website usage.
- **Advertising information** – Some third-party cookies can be used to help provide personalised advertising or measure advertising activity.

I saw that typically cookies have a name, value, plus other attributes like domain, path, expiration date, and security attributes. I did not record or share the actual values as it may contain user information that might be able to identify or authenticate a user.

In general, it was a wakeup call for me that cookies aren't only for remembering your login session. They can also have preferences and session data, tracking identifiers and other data used to identify and interact with a browser.
