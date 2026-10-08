# Networking Learning

## Network Interfaces

A network interface is a connection through which a system communicates over a network.

`lo` is the loopback interface.

`eth0` is the network interface used by my WSL environment.

## IP Addresses

An IP address identifies a network interface/address.

`127.0.0.1` is the IPv4 loopback address and refers to the local system.

My WSL IPv4 address was `172.23.18.12`.

## Ports

A port identifies a network service/application on a system.

Example:

`127.0.0.1:8000`

`127.0.0.1` = IP address

`8000` = port

Common ports:

`53` = DNS

`80` = HTTP

`443` = HTTPS

## Client and Server

A client sends requests.

A server listens for requests and sends responses.

Example:

Client → HTTP request → Server

Server → HTTP response → Client

## HTTP

HTTP is a protocol used for communication between clients and web servers.

Common HTTP methods:

GET - retrieve data
POST - create/submit data
PUT - replace/update data
PATCH - partially update data
DELETE - delete data

## API

An API provides a defined way for software systems to communicate.

An API endpoint is a specific URL/path used to access functionality or data.

Example:

`/users/1`

## JSON

JSON is a common format for exchanging structured data between software systems.

Example:

{
  "id": 1,
  "name": "Leanne Graham"
}

## DNS

DNS (Domain Name System) translates domain names into IP addresses.

Example:

`google.com` → an IP address

DNS commonly uses port `53`.

## HTTPS

HTTPS is HTTP protected by TLS encryption.

Port `443` is commonly used for HTTPS.

## Networking Flow

Domain name
    ↓
DNS
    ↓
IP address
    ↓
Port
    ↓
TCP connection
    ↓
HTTP/HTTPS
    ↓
Request
    ↓
Server
    ↓
Response


## Useful Commands

`ip addr` - show network interfaces and IP addresses

`ping -c 4 <IP>` - test connectivity to an IP address

`ss -tuln` - show listening TCP/UDP ports

`curl <URL>` - make an HTTP request

`curl -v <URL>` - make an HTTP request and show connection/request/response details

`nslookup <domain>` - query DNS for a domain

`python3 -m http.server 8000` - start a simple HTTP server on port 8000
