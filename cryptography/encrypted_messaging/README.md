# Encrypted Messaging

## Overview

This tool demonstrates a simple encrypted messaging system using asymmetric (public-key) cryptography to ensure message confidentiality.

Messages are encrypted with the recipient’s public key and can only be decrypted using the recipient’s private key, illustrating how public-key encryption protects message contents from unauthorized access.

---

## Security Concept Demonstrated

- Asymmetric (public-key) encryption
- Message confidentiality
- Secure key usage for encryption and decryption

---

## What This Tool Shows

- How RSA key pairs can be generated for individual users
- How public keys are used to encrypt messages
- How private keys are required to decrypt received messages
- Why asymmetric encryption is useful for secure communication between parties

---

## Limitations

- Private keys are stored unencrypted on disk
- No authentication of message sender (confidentiality only, not authenticity)
- No key rotation or revocation
- No secure key exchange or trust model
- Local file-based message storage
- Not suitable for production secure messaging systems

This implementation focuses on demonstrating encryption concepts rather than building a complete secure messaging platform.

---

## How to Run

```bash
python main.py
```
==============================================================================================

# 加密消息系统（Encrypted Messaging）

## 项目概述

该工具演示了一个使用非对称（公钥）加密的简单消息系统，用于保障消息内容的机密性。

消息使用接收方的公钥进行加密，只有对应的私钥才能解密，从而防止未授权的第三方读取消息内容。

---

## 演示的安全概念

- 非对称（公钥）加密
- 消息机密性
- 加密与解密中的密钥使用

---

## 本工具展示了什么

- 如何为用户生成 RSA 公钥和私钥
- 如何使用公钥对消息进行加密
- 私钥在解密消息中的关键作用
- 为什么非对称加密适用于安全通信场景

---

## 限制说明

- 私钥以未加密形式存储在本地
- 未验证消息发送者身份（仅保证机密性，不保证真实性）
- 未实现密钥轮换或吊销机制
- 不包含安全的密钥交换或信任模型
- 消息仅存储在本地文件中
- 不适用于真实生产环境的安全通信系统

该示例旨在演示加密通信的核心原理，而非提供完整的安全消息解决方案。

---

## 运行方式

```bash
python main.py
```
