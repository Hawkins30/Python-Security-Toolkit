# Two-Factor Authentication (2FA)

## Overview

This tool demonstrates a simple two-factor authentication (2FA) system that combines password-based login with time-based one-time passwords (TOTP).

It builds on earlier authentication examples by adding a second authentication factor, illustrating how multi-factor authentication improves account security.

---

## Security Concept Demonstrated

- Two-factor authentication (something you know + something you have)
- Time-based one-time passwords (TOTP)
- Secure credential verification with hashed and salted passwords

---

## What This Tool Shows

- How TOTP-based 2FA works using an authenticator-style approach
- How password authentication can be combined with a second factor
- Why adding a second factor significantly reduces account compromise risk

---

## Limitations

- Uses SHA-256 instead of a dedicated password hashing algorithm
- OTP secrets are stored locally without encryption at rest
- Includes a debug helper to display OTPs (for demonstration only)
- No rate limiting, account lockout, or recovery mechanisms
- Local file-based storage only
- Not suitable for production authentication systems

This implementation is designed to demonstrate concepts rather than provide a hardened security solution.

---

## How to Run

```bash
python main.py
```
==================================================================================================

# 双因素认证（Two-Factor Authentication）

## 项目概述

该工具演示了一个简单的双因素认证（2FA）系统，将基于密码的登录与基于时间的一次性验证码（TOTP）相结合。

本示例在之前的登录系统基础上引入第二个认证因子，用于说明多因素认证如何提升账户安全性。

---

## 演示的安全概念

- 双因素认证（“你知道的” + “你拥有的”）
- 基于时间的一次性密码（TOTP）
- 使用加盐哈希进行凭证校验

---

## 本工具展示了什么

- 使用类似认证器机制的 TOTP 工作原理
- 如何将密码认证与第二认证因子结合
- 为什么第二因子能够显著降低账户被攻破的风险

---

## 限制说明

- 使用的是 SHA-256，而非专用密码哈希算法
- OTP 密钥以明文形式存储在本地文件中
- 包含用于演示的 OTP 显示功能（仅限学习用途）
- 未实现速率限制、账户锁定或恢复机制
- 仅使用本地文件存储
- 不适用于真实生产环境的身份认证系统

该实现旨在演示安全概念，而非提供完整的安全解决方案。

---

## 运行方式

```bash
python main.py
```
