# Login Check

## Overview

This tool demonstrates a very basic login check mechanism by comparing user input against a predefined password.

It is intentionally minimal and is designed to illustrate the core idea of authentication checks rather than secure login practices.

---

## Security Concept Demonstrated

- Basic authentication logic
- Credential comparison

---

## What This Tool Shows

- How user input can be validated against stored credentials
- Why naïve string comparison is insufficient for real authentication systems

---

## Limitations

- The password is hard-coded in plaintext
- No hashing or salting is used
- No protection against brute-force attempts
- Not suitable for real-world use

This example exists purely to highlight *what not to do* in production systems.

---

## How to Run

```bash
python main.py
```
===============================================================================

# 登录校验（Login Check）

## 项目概述

该工具通过将用户输入与预设密码进行比较，演示了一个最基础的登录校验机制。

该示例刻意保持最小化，用于说明身份认证的基本思想，而非安全的登录实现方式。

---

## 演示的安全概念

- 基础身份认证逻辑
- 凭证比较机制

---

## 本工具展示了什么

- 如何对用户输入进行简单校验
- 为什么直接进行字符串比较在真实系统中是不安全的

---

## 限制说明

- 密码以明文形式硬编码在代码中
- 未使用哈希或加盐机制
- 不具备防暴力破解能力
- 不适用于真实生产环境

该示例主要用于说明真实系统中应避免的做法。

---

## 运行方式

```bash
python main.py
```
