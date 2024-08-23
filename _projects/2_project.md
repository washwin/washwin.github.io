---
layout: page
title: Encrypted Chatroom
description: Private chatting and video-sharing platform
img: assets/img/encrypted_chatroom.jpg
importance: 1
category: work
related_publications: false
---

This is a robust TCP socket-based system designed to facilitate secure, encrypted communication between clients, along with real-time video streaming capabilities. The system is engineered to manage multiple client connections efficiently, providing a secure and seamless communication environment.

Central to this system is the integration of public key management, which ensures end-to-end encryption. Each client’s public key is stored and managed by the server, allowing for secure communication between clients without compromising privacy. When a client wishes to communicate with another, the system retrieves the necessary public key from the server, ensuring that all messages are encrypted and secure.

Additionally, the system features real-time notifications, keeping all connected clients updated on the status of new connections and messages. This real-time communication ensures a smooth and uninterrupted user experience, allowing clients to stay connected without any delays.

The video streaming functionality is also a key component, enabling clients to request and view video files in real time. The server handles these requests without needing to save the video files on the client side, maintaining the security and integrity of the content.


<div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/embed/Fn9QgUqdQzE" class="img-fluid rounded z-depth-1" %}
</div>