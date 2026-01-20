# Digital Signatures

## Overview

This tool demonstrates the use of digital signatures to ensure message authenticity and integrity using asymmetric cryptography.

It shows how messages can be signed with a private key and later verified using the corresponding public key, allowing recipients to detect tampering and confirm the sender’s identity.

---

## Security Concept Demonstrated

- Digital signatures
- Asymmetric (public-key) cryptography
- Message integrity and authenticity
- Cryptographic verification

---

## What This Tool Shows

- How RSA key pairs can be generated for signing and verification
- How private keys are used to sign messages
- How public keys are used to verify message authenticity
- How digital signatures detect message tampering

---

## Limitations

- Private keys are stored unencrypted on disk
- No key rotation or revocation mechanism
- No secure key distribution model
- No access control around key usage
- Local file-based storage only
- Not suitable for production cryptographic systems

This implementation focuses on demonstrating the mechanics of digital signatures rather than providing a hardened messaging system.

---

## How to Run

```bash
python main.py
```
==================================================================================================

# 数字签名（Digital Signatures）

## 项目概述

该工具演示了如何使用非对称加密实现数字签名，以确保消息的真实性与完整性。

通过使用私钥对消息进行签名，并使用对应的公钥进行验证，接收方可以确认消息是否被篡改以及发送者的身份。

---

## 演示的安全概念

- 数字签名
- 非对称（公钥）加密
- 消息完整性与真实性
- 加密验证机制

---

## 本工具展示了什么

- 如何生成用于签名与验证的 RSA 密钥对
- 私钥如何用于对消息进行签名
- 公钥如何用于验证消息来源
- 数字签名如何检测消息是否被篡改

---

## 限制说明

- 私钥以未加密形式存储在本地
- 未实现密钥轮换或吊销机制
- 不包含安全的密钥分发模型
- 未对密钥使用进行访问控制
- 仅使用本地文件存储
- 不适用于真实生产环境的加密系统

该示例旨在演示数字签名的工作原理，而非提供完整的安全通信解决方案。

---

## 运行方式

```bash
python main.py
```
