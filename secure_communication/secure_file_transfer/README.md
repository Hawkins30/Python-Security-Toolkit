# Secure File Transfer

## Overview

This tool demonstrates a simplified secure file transfer system that combines encryption and digital signatures to protect files during transfer.

It uses a hybrid cryptographic approach: symmetric encryption for file contents and asymmetric cryptography for key exchange and signature verification, illustrating how secure file transfer systems ensure confidentiality, integrity, and authenticity.

---

## Security Concept Demonstrated

- Hybrid encryption (symmetric + asymmetric)
- Digital signatures for integrity and authenticity
- Secure key exchange using public-key cryptography
- Protection of files in transit

---

## What This Tool Shows

- How files can be encrypted using symmetric encryption (Fernet)
- How symmetric keys can be securely exchanged using RSA public keys
- How digital signatures verify the sender and detect tampering
- How encryption and signing work together in secure file transfer workflows

---

## Limitations

- Private keys are stored unencrypted on disk
- No key revocation, rotation, or trust infrastructure
- No secure transport layer or network transmission
- Transfer package format is custom and not standardized
- Local file-based storage only
- Not suitable for production secure file transfer systems

This implementation is designed to demonstrate core security principles rather than provide a complete or hardened file transfer solution.

---

## How to Run

```bash
python main.py
```
==================================================================================================

# 安全文件传输（Secure File Transfer）

## 项目概述

该工具演示了一个简化的安全文件传输系统，通过结合加密与数字签名来保护文件在传输过程中的安全性。

它采用混合加密方式：使用对称加密保护文件内容，并使用非对称加密进行密钥交换和签名验证，从而确保机密性、完整性和真实性。

---

## 演示的安全概念

- 混合加密（对称加密 + 非对称加密）
- 使用数字签名保证完整性与真实性
- 基于公钥加密的安全密钥交换
- 传输中文件数据的保护

---

## 本工具展示了什么

- 如何使用对称加密对文件内容进行加密
- 如何使用 RSA 公钥安全地传递对称密钥
- 数字签名如何验证发送者身份并检测文件篡改
- 加密与签名如何协同构建安全文件传输流程

---

## 限制说明

- 私钥以未加密形式存储在本地
- 未实现密钥吊销、轮换或信任体系
- 不包含真实的网络传输层
- 传输包格式为自定义实现，非标准协议
- 仅使用本地文件存储
- 不适用于真实生产环境的安全文件传输系统

该示例旨在演示安全文件传输的核心原理，而非提供完整的生产级解决方案。

---

## 运行方式

```bash
python main.py
```
