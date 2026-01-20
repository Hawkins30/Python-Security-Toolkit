# Secure Sharing

## Overview

This tool demonstrates a simplified secure file sharing system with encryption, user authentication, and access logging.

Users can encrypt files, decrypt their own files, and record file-sharing actions between users. All sensitive files are encrypted at rest, and all key actions are logged for auditing purposes.

---

## Security Concepts Demonstrated

- Password-based user authentication
- Per-user encryption keys
- Encryption of files at rest
- Access logging and audit trails
- Controlled sharing intent between users

---

## What This Tool Shows

- How users can authenticate securely using hashed passwords
- How encrypted files can be created per user
- How decryption is restricted to the correct encryption key
- How file access and sharing actions can be logged for accountability
- Why audit logs are important in secure systems

---

## How Sharing Works

- Files are encrypted using the owner’s encryption key
- Encrypted files can only be decrypted by the same user
- Sharing actions are recorded in an access log
- This simulates how real systems track file sharing and access

Actual cryptographic key exchange between users is intentionally simplified to keep the focus on access control and auditing concepts.

---

## Limitations

- Encryption keys are stored locally in user records
- No real key exchange or re-encryption for recipients
- No role-based access controls
- No permission revocation
- No secure key storage or hardware-backed security
- Local file-based storage only
- Not suitable for real-world secure file sharing systems

This implementation focuses on illustrating core security concepts rather than providing a production-ready sharing platform.

---

## How to Run

```bash
python main.py
```
===============================================================================================

# 安全共享（Secure Sharing）

## 项目概述

该工具演示了一个简化的安全文件共享系统，结合了加密、用户认证和访问日志记录。

用户可以加密文件、解密自己的文件，并记录文件在用户之间共享的行为。所有敏感文件在存储时都会被加密，所有关键操作都会被记录以便审计。

---

## 演示的安全概念

- 基于密码的用户认证
- 每用户独立的加密密钥
- 文件静态加密（加密存储）
- 访问日志与审计追踪
- 受控的文件共享行为记录

---

## 本工具展示了什么

- 用户如何通过哈希密码进行安全登录
- 如何为每个用户创建并使用独立的加密密钥
- 文件解密如何受限于正确的密钥
- 文件访问与共享行为如何被记录
- 为什么访问日志在安全系统中至关重要

---

## 文件共享机制说明

- 文件使用文件所有者的加密密钥进行加密
- 只有原用户才能解密自己的加密文件
- 共享行为会被记录在访问日志中
- 该设计模拟了真实系统中的共享审计机制

为了突出访问控制与审计概念，示例中简化了真实的加密密钥交换流程。

---

## 限制说明

- 加密密钥以本地方式存储在用户数据中
- 未实现真实的密钥交换或重新加密
- 不支持角色或权限控制
- 不支持权限撤销
- 未使用安全密钥存储或硬件安全模块
- 仅使用本地文件系统
- 不适用于真实生产环境的安全文件共享系统

该示例的目标是教学与演示安全概念，而非构建完整的生产级系统。

---

## 运行方式

```bash
python main.py
```
