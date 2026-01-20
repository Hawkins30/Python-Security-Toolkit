# Encryption Demo (Fernet)

## Overview

This tool demonstrates basic symmetric encryption and decryption using the Fernet module from the `cryptography` library.

It shows how a single secret key can be used to both encrypt and decrypt data, illustrating the core principles of symmetric-key encryption.

---

## Security Concept Demonstrated

- Symmetric encryption
- Secret key generation and management
- Confidentiality of data at rest and in transit

---

## What This Tool Shows

- How to generate and persist a secret encryption key
- How plaintext data can be encrypted using a shared secret
- How encrypted data can be decrypted back into its original form
- Why key management is critical in symmetric encryption systems

---

## Limitations

- Encryption key is stored unprotected on disk
- No key rotation or access controls
- No authentication or integrity verification beyond Fernet defaults
- Designed for demonstration purposes only
- Not suitable for production encryption workflows

This example focuses on explaining symmetric encryption mechanics rather than building a hardened encryption system.

---

## How to Run

```bash
python main.py
```
==============================================================================================

# 加密演示（Fernet）

## 项目概述

该工具使用 `cryptography` 库中的 Fernet 模块，演示了对称加密与解密的基本流程。

它展示了如何使用同一个密钥对数据进行加密和解密，从而说明对称密钥加密的核心原理。

---

## 演示的安全概念

- 对称加密
- 密钥生成与管理
- 数据机密性保护

---

## 本工具展示了什么

- 如何生成并保存对称加密密钥
- 如何使用共享密钥对明文数据进行加密
- 如何将加密数据解密还原为原始内容
- 为什么密钥管理在对称加密系统中至关重要

---

## 限制说明

- 加密密钥以未受保护的形式存储在本地
- 未实现密钥轮换或访问控制
- 未额外实现完整性或身份验证机制
- 仅用于演示和学习目的
- 不适用于真实生产环境的加密流程

该示例旨在说明对称加密的基本机制，而非提供完整的安全实现。

---

## 运行方式

```bash
python main.py
```
