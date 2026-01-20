# Secure Keychain

## Overview

This tool demonstrates a password-protected keychain (password manager) that securely stores credentials using encryption derived from a master password.

A cryptographic key is derived using a password-based key derivation function (PBKDF2), and all stored passwords are encrypted before being written to disk. This illustrates how keychains protect sensitive secrets even if storage files are accessed.

---

## Security Concept Demonstrated

- Password-based key derivation (PBKDF2)
- Encryption of stored credentials
- Secure handling of secrets at rest
- Separation of master password and stored data

---

## What This Tool Shows

- How a master password can derive a strong encryption key
- How credentials can be encrypted before storage
- Why key derivation functions slow down brute-force attacks
- How encrypted keychains protect secrets even if files are stolen

---

## Limitations

- Encryption key exists in memory during runtime
- No secure memory wiping
- No protection against keylogging or compromised host systems
- No automatic lock or timeout mechanism
- No backup or recovery mechanism
- Local file-based storage only
- Not suitable for production password managers

This implementation focuses on demonstrating keychain security principles rather than providing a hardened password manager.

---

## How to Run

```bash
python main.py
```
==================================================================================================

# 安全密钥链（Secure Keychain）

## 项目概述

该工具演示了一个受主密码保护的密钥链（密码管理器），通过从主密码派生加密密钥来安全地存储凭证信息。

系统使用基于密码的密钥派生函数（PBKDF2）生成加密密钥，并在将密码写入磁盘前对其进行加密，从而说明即使存储文件被获取，凭证内容仍然受到保护。

---

## 演示的安全概念

- 基于密码的密钥派生（PBKDF2）
- 存储凭证的加密保护
- 静态数据中的秘密管理
- 主密码与存储数据的分离

---

## 本工具展示了什么

- 如何通过主密码派生高强度加密密钥
- 如何在存储前对凭证进行加密
- 为什么密钥派生函数可以有效减缓暴力破解攻击
- 即使密钥链文件被窃取，凭证仍可保持安全的原因

---

## 限制说明

- 加密密钥在程序运行期间存在于内存中
- 未实现安全内存清理机制
- 无法防御键盘记录或主机被攻破的情况
- 未实现自动锁定或超时机制
- 不包含备份或恢复功能
- 仅使用本地文件存储
- 不适用于真实生产环境的密码管理器

该示例旨在演示密钥链的核心安全原理，而非提供完整的安全实现。

---

## 运行方式

```bash
python main.py
```
