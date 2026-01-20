# Salted Login System

## Overview

This tool demonstrates a more secure login system that uses password hashing with per-user salts and stores credentials in a local JSON file.

It is designed to illustrate proper password handling practices compared to naïve plaintext storage, while remaining intentionally simple and educational.

---

## Security Concept Demonstrated

- Password hashing with salts
- Secure credential storage
- Verification of hashed credentials

---

## What This Tool Shows

- How salting protects against rainbow table attacks
- How hashed passwords can be safely compared without storing plaintext credentials
- Why persistent credential storage requires careful handling

---

## Limitations

- Uses a general-purpose hash function (SHA-256) rather than a dedicated password hashing algorithm
- No key stretching (e.g. bcrypt, scrypt, Argon2)
- No account lockout or rate limiting
- Local file-based storage only
- Not suitable for production authentication systems

This example focuses on demonstrating correct concepts rather than providing a hardened authentication solution.

---

## How to Run

```bash
python main.py
```
===================================================================================================

# 加盐登录系统（Salted Login System）

## 项目概述

该工具演示了一个更安全的登录系统，使用带盐的密码哈希，并将用户凭证存储在本地 JSON 文件中。

本示例用于说明相比明文存储，更合理的密码处理方式，同时保持实现简洁、易于理解。

---

## 演示的安全概念

- 密码加盐与哈希
- 安全的凭证存储方式
- 哈希凭证的校验机制

---

## 本工具展示了什么

- 加盐如何防御彩虹表攻击
- 如何在不存储明文密码的情况下进行身份验证
- 为什么持久化凭证存储需要谨慎设计

---

## 限制说明

- 使用通用哈希算法（SHA-256），而非专用密码哈希算法
- 未实现密钥拉伸（如 bcrypt、scrypt、Argon2）
- 不包含账户锁定或速率限制机制
- 仅使用本地文件存储
- 不适用于真实生产环境的身份认证系统

该示例旨在展示正确的安全概念，而非提供完整的安全解决方案。

---

## 运行方式

```bash
python main.py
```
