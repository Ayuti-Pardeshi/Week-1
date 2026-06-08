# Part A: Network Devices Research

## Router

### Purpose

Connects different networks and provides internet access.

### How it Works

Routes packets between networks using routing tables.

### Real World Usage

Home Wi-Fi routers.

---

## Switch

### Purpose

Connects devices within a local network.

### How it Works

Uses MAC addresses to forward data to the correct device.

### Real World Usage

Office and enterprise networks.

---

## Hub

### Purpose

Connects multiple devices in a network.

### How it Works

Broadcasts data to all connected devices.

### Real World Usage

Older LAN environments.

---

## Access Point

### Purpose

Provides wireless network access.

### How it Works

Converts wired network signals into Wi-Fi signals.

### Real World Usage

College, office, and public Wi-Fi networks.

---

## Firewall

### Purpose

Protects systems from unauthorized access.

### How it Works

Filters incoming and outgoing traffic according to rules.

### Real World Usage

Windows Firewall and enterprise firewalls.

---

## Modem

### Purpose

Connects a network to an ISP.

### How it Works

Converts digital signals into forms suitable for transmission over communication lines.

### Real World Usage

Fiber, DSL, and cable internet connections.

---

# Part B: IP Address Classification

| IP Address    | Type    | Reason                               |
| ------------- | ------- | ------------------------------------ |
| 192.168.1.10  | Private | Falls in 192.168.0.0/16              |
| 10.0.0.5      | Private | Falls in 10.0.0.0/8                  |
| 172.16.5.20   | Private | Falls in 172.16.0.0 - 172.31.255.255 |
| 8.8.8.8       | Public  | Google's Public DNS                  |
| 1.1.1.1       | Public  | Cloudflare Public DNS                |
| 192.168.100.1 | Private | Falls in 192.168.0.0/16              |

---

# Part C: Understanding My Network

## IPv4 Address

[Enter your IPv4 Address]

## Default Gateway

[Enter your Default Gateway]

## DNS Server

[Enter your DNS Server]

### Which IP range does your device belong to?

My device belongs to the private IP address range.

### Is it Public or Private?

Private.

### What role does your router play?

The router connects my local network to the internet and forwards packets between networks.

### What would happen if the DNS server stopped working?

Domain names such as google.com would not resolve into IP addresses, making website access difficult.

---

# Part D: Network Communication Flow

Device → Router → DNS Server → Google Server → Response Back

### Step 1

The user enters [www.google.com](http://www.google.com) in the browser.

### Step 2

The request is sent to the router.

### Step 3

The DNS server resolves the domain name into an IP address.

### Step 4

The request reaches Google's server.

### Step 5

Google sends the response back.

### Step 6

The webpage loads in the browser.

---

# Part E: Practical Commands

## Command 1

ipconfig /all

Screenshot Attached: Yes

---

## Command 2

nslookup google.com

Screenshot Attached: Yes

---

## Command 3

ping google.com

Screenshot Attached: Yes

---

## Questions

### What IP address did DNS return for Google?

[Enter Result From nslookup]

### Was the ping successful?

[Yes / No]

### Why is DNS important before communication begins?

DNS converts human-readable domain names into IP addresses so devices can communicate with servers.
