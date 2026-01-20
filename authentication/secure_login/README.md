# Secure Login (Hashed Passwords)

## Overview

This tool demonstrates a simple login system that improves on plaintext credential storage by hashing passwords before saving them.

It is designed to introduce the concept of password hashing and show why hashing is a necessary step in securing authentication systems.

---

## Security Concept Demonstrated

- Password hashing
- Credential verification without plaintext storage

---

## What This Tool Shows

- How passwords can be transformed using a cryptographic hash function
- How hashed credentials can be compared during login
- Why hashing is safer than storing plaintext passwords

---

## Limitations

- Uses SHA-256, a general-purpose hash function rather than a password-specific algorithm
- No salting, making hashes vulnerable to rainbow table attacks
- No rate limiting or account lockout
- Credentials stored in a local text file
- Not suitable for production authentication systems

This example intentionally focuses on illustrating the hashing concept rather than providing a fully secure solution.

---

## How to Run

```bash
python main.py
```
=================================================================================================

# 安全登录（密码哈希）

## 项目概述

该工具演示了一个通过对密码进行哈希处理来改进明文存储的简单登录系统。

本示例用于引入密码哈希的概念，并说明为什么哈希是构建安全身份认证系统的必要步骤。

---

## 演示的安全概念

- 密码哈希
- 无需存储明文密码的凭证校验

---

## 本工具展示了什么

- 如何使用加密哈希函数处理密码
- 登录过程中如何比较哈希后的凭证
- 为什么哈希存储比明文存储更安全

---

## 限制说明

- 使用的是通用哈希算法（SHA-256），而非专用密码哈希算法
- 未使用加盐机制，容易受到彩虹表攻击
- 未实现速率限制或账户锁定
- 凭证存储在本地文本文件中
- 不适用于真实生产环境的登录系统

该示例主要用于说明密码哈希的核心思想，而非完整的安全实现。

---

## 运行方式

```bash
python main.py
```
