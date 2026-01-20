# Secure Storage

## Overview

This tool demonstrates a multi-user encrypted file storage system where each user has their own encryption key derived at registration time.

Users authenticate with salted and hashed credentials, and all file encryption and decryption operations are performed using a user-specific symmetric key. This illustrates how secure storage systems isolate data between users.

---

## Security Concept Demonstrated

- Secure authentication with salted password hashing
- Per-user symmetric encryption keys
- Data isolation between users
- Protection of files at rest

---

## What This Tool Shows

- How users can authenticate before accessing encrypted storage
- How each user can have a unique encryption key
- How file encryption prevents unauthorized access to stored data
- Why per-user keys are important for multi-tenant storage systems

---

## Limitations

- Encryption keys are stored alongside user metadata
- No secure key derivation or hardware-backed key storage
- No access logging or auditing
- No integrity verification or digital signatures
- Files are stored locally
- Not suitable for production secure storage systems

This implementation focuses on demonstrating secure storage concepts rather than providing a complete or hardened solution.

---

## How to Run

```bash
python main.py
```
=====================================================================================================

# 安全存储（Secure Storage）

## 项目概述

该工具演示了一个多用户加密文件存储系统，每个用户在注册时都会分配一个独立的加密密钥。

用户通过加盐哈希的方式进行身份认证，所有文件的加密和解密操作均使用用户专属的对称密钥，从而说明多用户环境中如何实现数据隔离。

---

## 演示的安全概念

- 使用加盐哈希的安全身份认证
- 基于用户的对称加密密钥
- 用户之间的数据隔离
- 静态文件数据保护

---

## 本工具展示了什么

- 用户在访问加密存储前如何完成身份认证
- 每个用户如何拥有独立的加密密钥
- 文件加密如何防止未授权访问
- 为什么多租户系统需要基于用户的密钥隔离

---

## 限制说明

- 加密密钥与用户元数据一同存储
- 未使用安全的密钥派生或硬件密钥存储
- 未实现访问日志或审计机制
- 未对数据完整性进行校验或签名
- 文件仅存储在本地
- 不适用于真实生产环境的安全存储系统

该示例旨在演示安全存储的核心原理，而非提供完整的生产级实现。

---

## 运行方式

```bash
python main.py
```
