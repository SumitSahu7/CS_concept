## Understanding HTTP & HTTPS

## 1. What is HTTP and Its Different Versions

```
HTTP (HyperText Transfer Protocol) is a protocol used for communication between a browser (client) and a server.

It follows a request–response model.
HTTP itself is stateless, meaning it does not remember past requests.

HTTP versions:

HTTP/1.0 – One request per connection.

HTTP/1.1 – Persistent connections, faster than 1.0.

HTTP/2 – Multiple requests at once, better performance.

HTTP/3 – Uses UDP for faster and more reliable communication.

- Interview tip: HTTP is stateless and request–response based.
```

## 2. HTTP Status Codes for Responses

```
Status codes tell the client what happened to the request.

1xx – Informational

2xx – Success (200 OK)

3xx – Redirection (301, 302)

4xx – Client error (404 Not Found)

5xx – Server error (500 Internal Server Error)

- Interview tip: 200 = success, 404 = client error, 500 = server error.
```

## 3. What is HTTPS and Why It Is Better

```
HTTPS is HTTP with security added.

It encrypts data so attackers cannot read or modify it.
It also verifies that you are talking to the real server.

- Interview tip: HTTPS = HTTP + Security.
```

## 4. How HTTPS Provides a Secure Connection

```
HTTPS uses encryption, authentication, and data integrity.

Before data transfer, the browser and server perform a TLS handshake.
They agree on encryption keys to secure communication.

After this, all data is encrypted.

- Interview tip: TLS handshake secures the connection.
```

## 5. What is SSL/TLS Encryption

```
SSL (Secure Sockets Layer) and TLS (Transport Layer Security) are security protocols.

TLS is the modern and secure version of SSL.
They encrypt data using public key and symmetric encryption.

This prevents eavesdropping and data tampering.

- Interview tip: TLS replaced SSL.
```

## 6. What are Proxy and Reverse Proxy

```
A proxy sits between the client and the internet.
It hides the client’s identity and can filter requests.

A reverse proxy sits between the client and the server.
It protects servers, balances load, and improves performance.

- Interview tip: Proxy = client-side, Reverse proxy = server-side.
```

## 7. How VPN Works and Helps Accessing Restricted Content

```
A VPN (Virtual Private Network) creates a secure tunnel between your device and a remote server.

Your internet traffic is encrypted and routed through the VPN server.
This hides your real IP address and bypasses regional restrictions.

- Interview tip: VPN = encrypted tunnel + IP masking.
```
