---
layout: page
title: Encrypted Chatroom
description: Private chatting and video-sharing platform
img: assets/img/encrypted_chatroom.jpg
importance: 3
category: tech
related_publications: false
---
### Project Title: Secure TCP Socket-Based System with Encrypted Communication and Real-Time Video Streaming

**Project Overview:**
This project is a robust TCP socket-based communication system designed to provide secure, encrypted client-to-client messaging and real-time video streaming capabilities. It efficiently manages multiple client connections, ensuring smooth, secure, and real-time communication. The system is built with a focus on security, utilizing public key encryption to safeguard all interactions between clients while offering seamless video streaming without the need for file storage on the client side.

<!-- <div class="col-sm mt-3 mt-md-0"> -->
<div>
        {% include video.liquid path="https://www.youtube.com/embed/Fn9QgUqdQzE" class="img-fluid rounded z-depth-1" %}
</div>

**Key Features:**
- **End-to-End Encrypted Communication:** The system employs public key encryption to ensure secure messaging between clients. The server manages the public keys for each client, allowing for encrypted communications without compromising privacy or data integrity. Clients can send messages securely by retrieving the recipient's public key from the server, ensuring all communications are protected.
  
- **Public Key Management:** The server stores and manages each client’s public key, enabling encrypted communication between clients. When a client wishes to communicate, the server securely retrieves and provides the necessary public key, maintaining the confidentiality of messages.

- **Real-Time Notifications:** Clients are instantly notified of new connections and incoming messages. This real-time update feature ensures a smooth, uninterrupted experience by keeping clients informed of the system’s status at all times, fostering seamless communication between users.

- **Real-Time Video Streaming:** The system features real-time video streaming, allowing clients to request and view video files without storing them locally. The server streams requested videos directly to the client, maintaining both security and efficiency by preventing the need for file downloads or local storage on the client side.

**Technologies and Security Measures:**
- **TCP Socket Communication:** The system utilizes TCP sockets to establish reliable communication between the server and multiple clients, providing a stable platform for both text-based messaging and video streaming.
- **End-to-End Encryption:** Public key encryption ensures that all messages exchanged between clients are secure, protecting sensitive information from unauthorized access.
- **Public Key Infrastructure (PKI):** The server acts as the key manager, storing and providing public keys on request to facilitate encrypted client communications.
  
**Key Functionalities:**
- **Secure Client-to-Client Messaging:** Clients can communicate securely with each other using end-to-end encryption. Messages are encrypted with the recipient’s public key, ensuring privacy even in a multi-client environment.
  
- **Efficient Connection Management:** The system supports multiple clients simultaneously, efficiently managing connections to ensure stable, secure communication. Clients receive real-time notifications of new connections and messages, maintaining a dynamic and responsive user experience.

- **On-Demand Video Streaming:** Clients can request video content, which the server streams in real time without saving it on the client’s device. This approach enhances security and prevents unnecessary file storage, while still delivering video content efficiently.

**Expected Impact:**
This system demonstrates the practical implementation of secure, encrypted communication in a multi-client environment, offering a high level of data privacy and real-time responsiveness. By integrating video streaming, the system extends its functionality beyond simple messaging, providing a well-rounded communication platform for various use cases, from secure file transfers to live media streaming.

**Challenges Overcome:**
- **Managing Public Keys for Multiple Clients:** The system effectively handles public key management, ensuring encrypted communication without adding complexity to the user experience.
- **Seamless Real-Time Communication:** The system ensures real-time updates and notifications, keeping clients informed  connections and messages, even when multiple clients are connected.

**Technologies Used:**
- **Programming Language:** Python (or another suitable language) for socket programming and managing communication protocols.
- **TCP Sockets:** To establish and maintain reliable connections between the server and clients.
- **Public Key Encryption:** For secure, encrypted client-to-client communication.
- **Video Streaming Protocols:** Used to handle on-demand video streaming without the need for client-side file storage.

**Conclusion:**
This secure TCP socket-based system delivers encrypted, real-time communication between clients while offering robust video streaming capabilities. With public key management for end-to-end encryption and seamless connection handling, the system ensures both privacy and efficiency, making it ideal for applications requiring secure messaging and media delivery in a multi-client setup.

