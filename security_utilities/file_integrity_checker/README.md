# File Integrity Checker

## Overview

This tool demonstrates how file integrity can be verified by computing and comparing cryptographic hash values.

By generating SHA-256 hashes of two files and comparing them, the tool can detect whether a file has been modified, corrupted, or tampered with.

---

## Security Concept Demonstrated

- File integrity verification
- Cryptographic hashing (SHA-256)
- Detection of unauthorized file modification

---

## What This Tool Shows

- How cryptographic hash functions can uniquely represent file contents
- How even small changes in a file produce completely different hashes
- Why hash comparison is useful for detecting tampering or corruption

---

## Limitations

- Does not authenticate the source of the file
- Does not provide encryption or confidentiality
- Only compares two files at a time
- No baseline hash storage or automated monitoring
- Designed for manual integrity checks
- Not suitable for production integrity monitoring systems

This implementation focuses on illustrating integrity verification concepts rather than building a full intrusion detection or monitoring solution.

---

## How to Run

```bash
python main.py
```
=================================================================================================

# 文件完整性校验（File Integrity Checker）

## 项目概述

该工具通过计算并比较文件的加密哈希值，演示了文件完整性校验的基本方法。

通过对两个文件生成 SHA-256 哈希并进行对比，可以检测文件是否被修改、损坏或遭到篡改。

---

## 演示的安全概念

- 文件完整性校验
- 加密哈希函数（SHA-256）
- 未授权文件修改的检测

---

## 本工具展示了什么

- 加密哈希如何唯一表示文件内容
- 文件中哪怕极小的改动也会导致哈希值发生巨大变化
- 为什么哈希比对适用于检测文件篡改或损坏

---

## 限制说明

- 无法验证文件来源的真实性
- 不提供加密或数据机密性保护
- 每次只能比较两个文件
- 未实现基线哈希存储或自动化监控
- 适用于手动完整性检查
- 不适用于真实生产环境的完整性监控系统

该示例旨在演示完整性校验的核心概念，而非构建完整的安全监测方案。

---

## 运行方式

```bash
python main.py
```
