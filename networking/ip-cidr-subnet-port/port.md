# ✅ README.md — PORT (Computer Networking)

---

## ✅ PORT (Computer Networking) – Full Concept

---

## 1. Definition of Port

A **Port** is a logical endpoint in a computer network that helps identify **which service or application** should receive data.

---

## 2. What is a Port?

A port is like a **door** of a computer.

- IP Address tells **which computer**
- Port Number tells **which application inside that computer**

So:

- IP = House Address
- Port = Room Number inside the house

---

## 3. Why Ports are Needed?

Ports are needed because:

- Many applications use internet at the same time
- Data must reach the correct application

Example:

On one device:

- Chrome uses web browsing
- WhatsApp uses messaging
- Zoom uses video calling

Ports help separate this traffic.

---

## 4. Port Works With IP Address

Communication needs:

✅ IP Address + Port Number

Example:

```
192.168.1.10:80
```

Means:

- Device IP = 192.168.1.10
- Port = 80 (Web service)

---

## 5. Port Number Range

Port numbers are 16-bit numbers.

So range is:

```
0 to 65535
```

Because:

```
2^16 = 65536
```

---

# ✅ Types of Ports

---

## 6. Well-Known Ports (0–1023)

Used for standard services.

| Port   | Service      |
| ------ | ------------ |
| 20, 21 | FTP          |
| 22     | SSH          |
| 23     | Telnet       |
| 25     | SMTP (Email) |
| 53     | DNS          |
| 80     | HTTP         |
| 443    | HTTPS        |

---

## 7. Registered Ports (1024–49151)

Used by specific software applications.

Example:

- Databases
- Games
- Custom applications

---

## 8. Dynamic / Private Ports (49152–65535)

Used temporarily for client communication.

Example:

When you open YouTube, your computer uses a temporary port.

---

# ✅ Common Port Numbers (Very Important)

| Port | Protocol       | Use                |
| ---- | -------------- | ------------------ |
| 80   | HTTP           | Web browsing       |
| 443  | HTTPS          | Secure websites    |
| 22   | SSH            | Secure login       |
| 21   | FTP            | File transfer      |
| 25   | SMTP           | Sending email      |
| 110  | POP3           | Receiving email    |
| 53   | DNS            | Domain name system |
| 3306 | MySQL          | Database           |
| 8080 | HTTP Alternate | Web servers        |

---

# ✅ Port in TCP and UDP

---

## 9. TCP Ports

TCP provides:

- Reliable communication
- Connection-based transfer

Used in:

- HTTP/HTTPS
- Email
- File transfer

---

## 10. UDP Ports

UDP provides:

- Fast communication
- No connection setup

Used in:

- Video streaming
- Online gaming
- DNS

---

# ✅ Example of Port in Real Life

---

## Web Browsing Example

When you open:

```
www.google.com
```

Your system connects using:

- IP address of Google server
- Port 443 (HTTPS)

So connection looks like:

```
ServerIP:443
```

---

# ✅ Port vs IP Address

| Feature    | IP Address    | Port                |
| ---------- | ------------- | ------------------- |
| Identifies | Device        | Application/service |
| Example    | 192.168.1.10  | 80                  |
| Works at   | Network Layer | Transport Layer     |

---

# ✅ Port Forwarding (Basic Idea)

Port Forwarding means:

Directing external traffic from a specific port to a device inside a network.

Used in:

- Hosting servers
- Online gaming
- Remote access

---

# ✅ Summary (Important Points)

- Port is a number that identifies a service on a computer
- Port works with IP address for communication
- Range is 0–65535
- Well-known ports are used for standard protocols
- TCP and UDP both use ports

---

# ✅ Exam Answer (5 Marks)

A port is a logical communication endpoint used in networking to identify specific services or applications on a device.
It works along with an IP address to ensure data reaches the correct application.
Port numbers range from 0 to 65535 and are divided into well-known, registered, and dynamic ports.
Common ports include 80 for HTTP and 443 for HTTPS.
Ports are mainly used in TCP and UDP communication.

---
