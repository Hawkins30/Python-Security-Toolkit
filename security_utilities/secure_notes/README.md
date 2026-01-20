# Secure Notes

## Overview

This tool demonstrates a secure notes application where all note content is encrypted using a key derived from a user-provided master password.

Notes are stored in encrypted form on disk and can only be viewed or modified after providing the correct password. This illustrates how personal data can be protected even if storage files are accessed directly.

---

## Security Concept Demonstrated

- Password-based key derivation (PBKDF2)
- Encryption of sensitive user-generated data
- Secure handling of data at rest
- Password-protected access to encrypted content

---

## What This Tool Shows

- How a master password can derive a strong encryption key
- How note contents can be encrypted before storage
- How encrypted notes can be safely decrypted for viewing or editing
- Why encrypting personal data is important for privacy and security

---

## Limitations

- Encryption key exists in memory during runtime
- No secure memory wiping
- No integrity verification or digital signatures
- No multi-user support or access controls
- No password recovery mechanism
- Local file-based storage only
- Not suitable for production secure note-taking applications

This implementation focuses on demonstrating encrypted data storage concepts rather than providing a fully hardened secure notes system.

---

## How to Run

```bash
python main.py
```
===================================================================================================

# 安全笔记（Secure Notes）

## 项目概述

该工具演示了一个安全笔记应用，所有笔记内容都会使用从主密码派生的加密密钥进行加密存储。

笔记以加密形式保存在本地文件中，只有在输入正确的主密码后才能查看或修改，从而说明即使存储文件被直接访问，内容仍然受到保护。

---

## 演示的安全概念

- 基于密码的密钥派生（PBKDF2）
- 用户生成数据的加密存储
- 静态数据中的隐私保护
- 基于密码的访问控制

---

## 本工具展示了什么

- 如何通过主密码派生高强度加密密钥
- 笔记内容在存储前如何被加密
- 加密笔记如何被安全地解密查看或编辑
- 为什么对个人数据进行加密对于隐私和安全非常重要

---

## 限制说明

- 加密密钥在程序运行期间存在于内存中
- 未实现安全内存清理机制
- 未对数据完整性进行校验或数字签名
- 不支持多用户或细粒度访问控制
- 不包含密码恢复机制
- 仅使用本地文件存储
- 不适用于真实生产环境的安全笔记应用

该示例旨在演示加密笔记存储的核心原理，而非提供完整的生产级实现。

---

## 运行方式

```bash
python main.py
```
