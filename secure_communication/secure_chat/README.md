# Secure Chat

## Overview

This tool demonstrates a simple encrypted chat system using sockets and symmetric encryption to protect messages exchanged between a client and a server.

Messages are encrypted using a shared secret key, illustrating how encryption can be applied to network communication to prevent plaintext transmission.

---

## Security Concept Demonstrated

- Encrypted network communication
- Symmetric encryption using Fernet
- Protection of data in transit

---

## What This Tool Shows

- How a client and server can exchange encrypted messages
- How symmetric encryption can protect chat contents over a socket connection
- Why encrypting data in transit is important for communication security

---

## Limitations

- Encryption key is generated and sent in plaintext at connection time
- No authentication of client or server identity
- No protection against man-in-the-middle attacks
- Single-client, blocking design
- Localhost-only demonstration
- Not suitable for production secure messaging systems

This implementation is intentionally simplified to demonstrate encrypted communication concepts rather than provide a secure chat platform.

---

## How to Run

1. Start the server:
   ```bash
   python server.py
   python client.py
    ```
===============================================================================================

# 安全聊天（Secure Chat）

## 项目概述

该工具演示了一个使用套接字和对称加密的简单聊天系统，用于保护客户端与服务器之间传输的消息内容。

消息通过共享密钥进行加密，从而说明如何在网络通信中防止明文数据传输。

---

## 演示的安全概念

- 加密的网络通信
- 使用 Fernet 的对称加密
- 传输中数据的保护

---

## 本工具展示了什么

- 客户端与服务器如何交换加密消息
- 如何使用对称加密保护套接字通信内容
- 为什么在通信过程中加密数据非常重要

---

## 限制说明

- 加密密钥在连接建立时以明文形式传输
- 未验证客户端或服务器身份
- 无法防御中间人攻击
- 仅支持单客户端、阻塞式通信
- 仅用于本地演示
- 不适用于真实生产环境的安全聊天系统

该实现旨在演示加密通信的基本概念，而非提供完整的安全聊天解决方案。

---

## 运行方式

1. 启动服务器：
   ```bash
   python server.py
   python client.oy
   ```
