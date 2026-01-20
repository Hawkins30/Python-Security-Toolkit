# File Encryption

## Overview

This tool demonstrates how symmetric encryption can be applied to protect the contents of files using the Fernet module from the `cryptography` library.

It allows files to be encrypted and decrypted using a shared secret key, illustrating how encryption can be used to secure data at rest.

---

## Security Concept Demonstrated

- Symmetric file encryption
- Data-at-rest protection
- Secret key generation and reuse

---

## What This Tool Shows

- How to generate and persist a symmetric encryption key
- How file contents can be encrypted to prevent unauthorized access
- How encrypted files can be safely decrypted when the correct key is available
- Why encryption is important for protecting sensitive files

---

## Limitations

- Encryption key is stored unprotected on disk
- No key rotation or access controls
- Files are overwritten in place during encryption and decryption
- No authentication or access management
- Designed for demonstration purposes only
- Not suitable for production file encryption systems

This example focuses on illustrating file encryption mechanics rather than providing a complete secure storage solution.

---

## How to Run

```bash
python main.py
```
===============================================================================================

# 文件加密（File Encryption）

## 项目概述

该工具使用 `cryptography` 库中的 Fernet 模块，演示了如何对文件内容进行对称加密与解密。

它展示了如何通过共享密钥来保护静态文件数据，从而说明数据静态加密的基本原理。

---

## 演示的安全概念

- 对称文件加密
- 静态数据保护
- 加密密钥的生成与复用

---

## 本工具展示了什么

- 如何生成并保存对称加密密钥
- 如何对文件内容进行加密以防止未授权访问
- 在拥有正确密钥的情况下如何解密文件
- 为什么文件加密对于保护敏感数据非常重要

---

## 限制说明

- 加密密钥以未受保护的形式存储在本地
- 未实现密钥轮换或访问控制
- 加密和解密过程中会直接覆盖原文件
- 未包含身份验证或权限管理机制
- 仅用于演示和学习目的
- 不适用于真实生产环境的文件加密系统

该示例旨在演示文件加密的核心机制，而非提供完整的安全存储解决方案。

---

## 运行方式

```bash
python main.py
```
