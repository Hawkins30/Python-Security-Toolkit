# Secure Cloud Storage

## Overview

This tool demonstrates a simplified secure cloud-style storage system that combines authentication, encryption, and per-user key management.

Users authenticate with salted and hashed credentials, and all uploaded files are encrypted using a user-specific symmetric key before being stored, illustrating how cloud storage systems can protect data confidentiality.

---

## Security Concept Demonstrated

- Secure authentication with salted password hashing
- Symmetric encryption for data-at-rest protection
- Per-user encryption key management
- Separation of credentials and encryption keys
- Basic key revocation

---

## What This Tool Shows

- How users can authenticate before accessing encrypted storage
- How files can be encrypted before being stored in a shared environment
- Why encryption keys should be stored separately from encrypted data
- How per-user keys enable access control and data isolation
- How revoking a key immediately prevents future access to stored data

---

## Limitations

- Encryption keys are stored unencrypted on disk
- No secure key derivation or hardware-backed key storage
- No access logging or audit trails
- No integrity verification or digital signatures
- No networked or multi-node storage layer
- Local filesystem only
- Not suitable for production cloud storage systems

This implementation is designed to demonstrate cloud security concepts rather than provide a full-featured secure storage service.

---

## How to Run

```bash
python main.py
```
===================================================================================================

# 安全云存储（Secure Cloud Storage）

## 项目概述

该工具演示了一个简化的安全云存储系统，结合了身份认证、加密以及基于用户的密钥管理机制。

用户通过加盐哈希的方式进行认证，所有上传的文件都会在存储前使用用户专属的对称密钥进行加密，从而说明云存储系统如何保护数据机密性。

---

## 演示的安全概念

- 使用加盐哈希的安全身份认证
- 用于静态数据保护的对称加密
- 基于用户的加密密钥管理
- 凭证与加密密钥的分离存储
- 基础的密钥吊销机制

---

## 本工具展示了什么

- 用户在访问加密存储前如何完成身份认证
- 文件在共享存储环境中如何被加密保护
- 为什么加密密钥应与加密数据分开存储
- 基于用户的密钥如何实现访问控制和数据隔离
- 密钥被吊销后如何立即阻止后续数据访问

---

## 限制说明

- 加密密钥以未加密形式存储在本地
- 未使用安全的密钥派生或硬件密钥存储
- 未实现访问日志或审计功能
- 未对数据完整性进行验证或签名
- 不包含网络化或分布式存储层
- 仅使用本地文件系统
- 不适用于真实生产环境的云存储系统

该示例旨在演示云存储安全的核心思想，而非提供完整的生产级实现。

---

## 运行方式

```bash
python main.py
```
