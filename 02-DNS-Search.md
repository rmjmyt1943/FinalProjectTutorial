# Part 2: The Address Book (DNS)

Now that we know who the Client and Server are, how does the Client find the specific Server it needs?

## The Problem: Names vs. Numbers
Humans are good at remembering names (like `google.com`). Computers are only good at remembering numbers. Every computer on the internet has a unique address called an **IP Address** (e.g., `142.250.190.46`).

## The Solution: DNS
**DNS** stands for **Domain Name System**. It is the phonebook of the internet.

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/7727a7e8-5c60-4277-a67f-bbaa15472ef6" />


### The Process
When you type `github.com` into your browser, the following steps occur within milliseconds:

1.  **The Lookup:** Your browser asks a DNS Resolver: *"Where can I find github.com?"*
2.  **The Search:** The DNS system searches its database.
3.  **The Answer:** The DNS system responds: *"github.com is located at 140.82.112.3."*
4.  **The Connection:** Now that your browser has the IP address, it can connect directly to the GitHub server.

### Internal Definitions
If you are confused by the terminology, review these terms:
* <a id="ip-def"></a>**IP Address:** A unique string of numbers separated by periods that identifies each computer using the Internet Protocol.
* <a id="domain-def"></a>**Domain Name:** A human-readable label used to identify a specific website (e.g., `example.com`).

[Back to top of page](#part-2-the-address-book-dns)

---

### Navigation
* [**Previous Step: Part 1 - Clients and Servers**](01-Clients-Servers.md)
* [Return to Home](README.md)
