# 🛡️ OWASP API Top 10 | دليل اختبار أمان API

> **Complete OWASP API Top 10 (2023) reference. Structured methodology, deep vulnerability analysis, and practical testing techniques. Enterprise-grade API security assessment skills.**

---

## 📖 عن المستودع | About

مرجع تقني متكامل لأخطر عشر ثغرات في أمان APIs وفق تصنيف OWASP API Top 10 2023.  
يشمل هذا المستودع:

- ✅ شرح مفصل لكل ثغرة مع أمثلة عملية
- ✅ منهجية اختبار اختراق منظمة خطوة بخطوة
- ✅ تحليل معمق لأساليب الاستغلال والتجاوز
- ✅ روابط مباشرة بين الثغرات والمنهجية

---

## 🔥 What's Inside Each API Category?

| # | Section | Description |
|---|---------|-------------|
| 🧠 | **Real-World Analogies** | Simple explanations to understand the vulnerability |
| 📌 | **Professional Definition** | Technical explanation and security impact |
| 🔥 | **Why It's Dangerous** | Real attack consequences and exploitation impact |
| 🧩 | **Common Vulnerability Types** | Most common attack patterns |
| 🧠 | **Attacker Mindset** | How professional attackers think |
| 🛠️ | **Practical Discovery** | Testing methodology and discovery workflow |
| 🛡️ | **Remediation & Hardening** | Professional mitigation best practices |

---

## 📂 هيكل المستودع | Repository Structure

```
OWASP-API-Top-10/
│
├── README.md
├── API-Pentesting-Methodology.md          # منهجية اختبار API
│
├── API1_BOLA.md                           # Broken Object Level Authorization
├── API2_Broken_Authentication.md          # Broken Authentication
├── API3_BOPLA.md                          # Broken Object Property Level Auth
├── API4_Unrestricted_Resource.md          # Unrestricted Resource Consumption
├── API5_BFLA.md                           # Broken Function Level Authorization
├── API6_Business_Flows.md                 # Unrestricted Access to Business Flows
├── API7_SSRF.md                           # Server-Side Request Forgery
├── API8_Security_Misconfiguration.md      # Security Misconfiguration
├── API9_Inventory_Management.md           # Improper Inventory Management
└── API10_Unsafe_Consumption.md            # Unsafe Consumption of APIs
```

---

## 📊 جدول الثغرات | Vulnerabilities Table

| # | Vulnerability | Severity | File |
|---|---------------|----------|------|
| API1 | Broken Object Level Authorization (BOLA) | 🔴 Critical | [API1_BOLA.md](API1_BOLA.md) |
| API2 | Broken Authentication | 🔴 Critical | [API2_Broken_Authentication.md](API2_Broken_Authentication.md) |
| API3 | Broken Object Property Level Auth | 🟡 Medium | [API3_BOPLA.md](API3_BOPLA.md) |
| API4 | Unrestricted Resource Consumption | 🟠 High | [API4_Unrestricted_Resource.md](API4_Unrestricted_Resource.md) |
| API5 | Broken Function Level Authorization | 🔴 Critical | [API5_BFLA.md](API5_BFLA.md) |
| API6 | Unrestricted Access to Business Flows | 🔵 Low | [API6_Business_Flows.md](API6_Business_Flows.md) |
| API7 | Server-Side Request Forgery (SSRF) | 🟠 High | [API7_SSRF.md](API7_SSRF.md) |
| API8 | Security Misconfiguration | 🔵 Low | [API8_Security_Misconfiguration.md](API8_Security_Misconfiguration.md) |
| API9 | Improper Inventory Management | 🔵 Low | [API9_Inventory_Management.md](API9_Inventory_Management.md) |
| API10 | Unsafe Consumption of APIs | 🟡 Medium | [API10_Unsafe_Consumption.md](API10_Unsafe_Consumption.md) |

---

## 🎯 الأولوية في الاختبار | Testing Priority

| الأولوية | المرحلة | الثغرات |
|----------|---------|---------|
| **1** | 🔴 Critical | API1, API2, API5 |
| **2** | 🟠 High | API4, API7 |
| **3** | 🟡 Medium | API3, API10 |
| **4** | 🔵 Low | API6, API8, API9 |

---

## 🔗 روابط ذات صلة | Related Repositories

| Repository | Description |
|------------|-------------|
| [OWASP-Top-10-2025](https://github.com/AliAlMansorisec/owasp-top-10-2025) | OWASP Web Top 10 |
| [Web-Pentest-Methodology](https://github.com/AliAlMansorisec/web-pentest-methodology) | Structured pentesting methodology |
| [PortSwigger-Labs](https://github.com/AliAlMansorisec/portswigger-labs) | Solutions to all PortSwigger labs |

---

## 👨‍💻 المطور | Author

**Ali Al-Mansori**  
Security Researcher & Penetration Tester

[![GitHub](https://img.shields.io/badge/GitHub-AliAlMansorisec-black)](https://github.com/AliAlMansorisec)

---

**Built for API security researchers, penetration testers, and bug bounty hunters.** 🚀

