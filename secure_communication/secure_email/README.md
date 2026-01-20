# Secure Email

## Overview

This tool demonstrates a simplified secure email system that combines encryption and digital signatures to protect message confidentiality, integrity, and authenticity.

It uses a hybrid cryptographic approach: symmetric encryption for message content and asymmetric cryptography for key exchange and signing, similar to how real-world secure email systems work conceptually.

---

## Security Concept Demonstrated

- Hybrid encryption (symmetric + asymmetric)
- Digital signatures for authenticity and integrity
- Secure key exchange using public-key cryptography
- Confidentiality of messages in transit and at rest

---

## What This Tool Shows

- How symmetric encryption can efficiently protect message content
- How asymmetric encryption can securely exchange symmetric keys
- How digital signatures verify the sender and detect message tampering
- How multiple cryptographic primitives work together in secure communication

---

## Limitations

- Private keys are stored unencrypted on disk
- No key revocation, rotation, or trust model
- No certificate authority or identity verification
- No replay protection or metadata protection
- Local file-based mailbox storage
- Not suitable for production secure email systems

This implementation focuses on demonstrating secure email concepts rather than providing a complete or hardened solution.

---

## How to Run

```bash
python main.py
```
================================================================================================

# 安全电子邮件（Secure Email）

## 项目概述

该工具演示了一个简化的安全电子邮件系统，通过结合加密与数字签名来保护消息的机密性、完整性和真实性。

它采用混合加密方式：使用对称加密保护邮件内容，并使用非对称加密进行密钥交换和签名，这与真实世界中安全邮件系统的核心原理一致。

---

## 演示的安全概念

- 混合加密（对称加密 + 非对称加密）
- 数字签名用于验证真实性与完整性
- 基于公钥加密的安全密钥交换
- 消息在传输和存储过程中的机密性保护

---

## 本工具展示了什么

- 对称加密如何高效地保护消息内容
- 非对称加密如何安全地传递对称密钥
- 数字签名如何验证发送者并检测消息篡改
- 多种加密技术如何协同构建安全通信系统

---

## 限制说明

- 私钥以未加密形式存储在本地
- 未实现密钥吊销、轮换或信任体系
- 不包含证书颁发机构或身份验证机制
- 未实现重放攻击防护或元数据保护
- 邮箱数据仅存储在本地文件中
- 不适用于真实生产环境的安全电子邮件系统

该示例旨在演示安全电子邮件的核心原理，而非提供完整的安全实现。

---

## 运行方式

```bash
python main.py
```
