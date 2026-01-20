# Login System

## Overview

This tool demonstrates a simple, stateful login system where users can register and log in using credentials stored in a local text file.

It is designed to illustrate how authentication systems manage user state and credential checking at a basic level, rather than to provide a secure implementation.

---

## Security Concept Demonstrated

- User registration and authentication flow
- Credential storage and verification
- State persistence across program runs

---

## What This Tool Shows

- How user credentials can be stored and retrieved
- How login systems compare provided credentials against stored records
- Why persistent storage introduces additional security considerations

---

## Limitations

- User credentials are stored in plaintext
- No hashing or salting of passwords
- No access controls on the credential file
- No protection against brute-force or enumeration attacks
- Not suitable for real-world authentication systems

This example is intentionally insecure to highlight common pitfalls in naïve login implementations.

---

## How to Run

```bash
python main.py
```
=================================================================================================

# 登录系统（Login System）

## 项目概述

该工具演示了一个简单的有状态登录系统，用户可以注册并通过存储在本地文本文件中的凭证进行登录。

本示例用于说明身份认证系统如何管理用户状态与凭证校验，而非提供安全的登录实现。

---

## 演示的安全概念

- 用户注册与登录流程
- 凭证的存储与校验
- 程序多次运行间的状态持久化

---

## 本工具展示了什么

- 如何存储并读取用户凭证
- 登录系统如何对输入的凭证进行校验
- 为什么持久化存储会引入额外的安全风险

---

## 限制说明

- 用户凭证以明文形式存储
- 未使用密码哈希或加盐机制
- 凭证文件缺乏访问控制
- 不具备防暴力破解或枚举攻击能力
- 不适用于真实生产环境

该示例刻意保持不安全，用于强调常见的登录系统设计误区。

---

## 运行方式

```bash
python main.py
```
