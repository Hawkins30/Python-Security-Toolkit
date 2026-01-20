# Password Leak Checker

## Overview

This tool checks whether a password has appeared in known data breaches using the Have I Been Pwned (HIBP) password API.

It uses a privacy-preserving k-anonymity approach, ensuring that the full password hash is never sent over the network. This demonstrates how security tools can query breach databases without exposing sensitive information.

---

## Security Concept Demonstrated

- Password hygiene and breach awareness
- Use of breached-password databases
- Privacy-preserving API design (k-anonymity)
- Defensive security practices

---

## What This Tool Shows

- How compromised passwords can be detected using public breach data
- How k-anonymity protects user privacy during API queries
- Why checking passwords against breach databases improves account security
- How security tooling can balance usefulness and privacy

---

## Limitations

- Relies on a third-party external API
- Requires an active internet connection
- Does not assess password strength beyond breach history
- No rate limiting or retry logic
- Intended for interactive, manual checks
- Not suitable for bulk or production credential scanning

This tool is designed to demonstrate breach-awareness concepts rather than provide a production credential auditing system.

---

## How to Run

```bash
python main.py
```
====================================================================================================

# 密码泄露检测（Password Leak Checker）

## 项目概述

该工具通过 Have I Been Pwned（HIBP）密码 API，检测某个密码是否出现在已知的数据泄露事件中。

它采用了保护隐私的 k-匿名（k-anonymity）机制，在查询过程中不会发送完整的密码哈希，从而说明安全工具如何在实用性与隐私保护之间取得平衡。

---

## 演示的安全概念

- 密码安全与泄露意识
- 使用已泄露密码数据库
- 保护隐私的 API 设计（k-匿名）
- 防御性安全实践

---

## 本工具展示了什么

- 如何利用公开的泄露数据检测受影响的密码
- k-匿名机制如何在查询过程中保护用户隐私
- 为什么检测泄露密码可以提升账户安全性
- 安全工具如何在不暴露敏感信息的情况下发挥作用

---

## 限制说明

- 依赖第三方外部 API
- 需要互联网连接
- 不评估密码复杂度，仅检测是否泄露
- 未实现速率限制或重试机制
- 适用于交互式、手动检测
- 不适用于生产环境中的大规模凭证扫描

该示例旨在演示密码泄露检测与隐私保护的核心理念，而非提供完整的生产级审计系统。

---

## 运行方式

```bash
python main.py
```
