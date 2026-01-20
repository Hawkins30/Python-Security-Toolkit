# Secure Vault

## Overview

This tool demonstrates a password-protected secure file vault that encrypts files using a key derived from a user-provided password.

Files added to the vault are encrypted before being stored, and can only be decrypted by providing the correct vault password. This illustrates how secure vaults protect sensitive data even if storage files are accessed directly.

---

## Security Concept Demonstrated

- Password-based key derivation (PBKDF2)
- Symmetric encryption for file protection
- Secure handling of sensitive data at rest
- Password-protected access to encrypted content

---

## What This Tool Shows

- How an encryption key can be derived from a password
- How files can be encrypted before being stored in a vault
- How encrypted data can only be accessed with the correct password
- Why vault-style encryption is useful for protecting sensitive files

---

## Limitations

- Encryption key exists in memory during runtime
- No secure memory wiping
- No integrity verification or digital signatures
- No access logging or auditing
- No password recovery mechanism
- Local file-based storage only
- Not suitable for production secure vault systems

This implementation focuses on demonstrating secure vault concepts rather than providing a hardened or feature-complete solution.

---

## How to Run

```bash
python main.py
```
==============================================================================================

# 安全文件保险库（Secure Vault）

## 项目概述

该工具演示了一个受密码保护的安全文件保险库，通过从用户提供的密码派生加密密钥来对文件进行加密存储。

添加到保险库中的文件会在存储前被加密，只有提供正确的保险库密码才能解密，从而说明即使存储文件被直接访问，数据内容仍然受到保护。

---

## 演示的安全概念

- 基于密码的密钥派生（PBKDF2）
- 用于文件保护的对称加密
- 静态数据中的敏感信息保护
- 基于密码的加密访问控制

---

## 本工具展示了什么

- 如何通过密码派生加密密钥
- 文件在存储前如何被加密
- 只有正确密码才能访问加密内容的机制
- 为什么保险库式加密适用于保护敏感文件

---

## 限制说明

- 加密密钥在程序运行期间存在于内存中
- 未实现安全内存清理机制
- 未对数据完整性进行校验或数字签名
- 未实现访问日志或审计功能
- 不包含密码恢复机制
- 仅使用本地文件存储
- 不适用于真实生产环境的安全文件保险库

该示例旨在演示安全文件保险库的核心原理，而非提供完整的生产级实现。

---

## 运行方式

```bash
python main.py
```
