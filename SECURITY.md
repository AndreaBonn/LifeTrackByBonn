# Security Policy

## Life Tracker by Bonn

[![Versione Italiana](https://img.shields.io/badge/🇮🇹_Versione_Italiana-009246?style=flat-square)](./SECURITY_IT.md) &nbsp; [![README](https://img.shields.io/badge/📖_README-4A90E2?style=flat-square)](./README_EN.md)

---

## 🔒 Security Overview

**Life Tracker** takes security and privacy seriously. This document outlines our security practices, how we protect your data, and how to report security vulnerabilities.

---

## 🛡️ Security Measures

### Authentication

- **Firebase Authentication** — Industry-standard authentication system
- **Email verification** — Required for account activation
- **Secure password storage** — Passwords are hashed and never stored in plain text
- **Session management** — Automatic session expiration and secure token handling

### Data Protection

- **Encryption in transit** — All data is transmitted over HTTPS
- **Encryption at rest** — Data stored in Firebase Firestore is encrypted
- **User isolation** — Each user can only access their own data
- **Firestore Security Rules** — Advanced rules prevent unauthorized access

### Infrastructure

- **Firebase Hosting** — Secure, scalable hosting with automatic SSL certificates
- **Cloud Functions** — Backend logic runs in isolated, secure environments
- **European data centers** — Data stored in Europe (region: europe-west1)
- **Regular updates** — Dependencies and libraries are kept up to date

### Application Security

- **Input validation** — All user inputs are validated on both client and server
- **XSS prevention** — HTML sanitization to prevent cross-site scripting attacks
- **CSRF protection** — Firebase Authentication provides built-in CSRF protection
- **Rate limiting** — Protection against brute-force attacks and abuse
- **Audit logging** — Critical operations are logged for security monitoring

---

## 🔐 Data Privacy

### What data we collect

Life Tracker collects only the data you explicitly provide:

- **Account information**: Email, name, profile details
- **Health data**: Weight, sleep, calories, steps, vital parameters, meals, medications
- **Usage data**: Timestamps, device information (for sync purposes)

### What we DON'T collect

- ❌ We do NOT track your browsing behavior
- ❌ We do NOT sell your data to third parties
- ❌ We do NOT use your data for advertising
- ❌ We do NOT share your data without your consent

### Data storage

- All data is stored in **Firebase Firestore** (Google Cloud)
- Data is stored in **European data centers** (region: europe-west1)
- Data is **encrypted at rest** and **in transit**
- You can **export** or **delete** your data at any time

### Third-party integrations

Life Tracker integrates with:

- **Google Fit** (optional) — Only if you explicitly authorize it
- **Telegram** (optional) — Only if you provide your bot token and chat ID

These integrations are **opt-in** and can be disconnected at any time.

---

## 🚨 Reporting Security Vulnerabilities

If you discover a security vulnerability in Life Tracker, please report it responsibly.

### How to report

1. **DO NOT** open a public issue on GitHub
2. **Contact me directly** via GitHub profile or email
3. **Provide details**: Description, steps to reproduce, potential impact
4. **Wait for response**: I will acknowledge your report within 48 hours

### What to expect

- **Acknowledgment** within 48 hours
- **Investigation** and assessment of the vulnerability
- **Fix** deployed as soon as possible (depending on severity)
- **Credit** in the acknowledgments section (if you wish)

### Responsible disclosure

Please allow reasonable time for the vulnerability to be fixed before public disclosure. I appreciate your cooperation in keeping Life Tracker secure for all users.

---

## 🔍 Security Best Practices for Users

To keep your account secure:

- ✅ Use a **strong, unique password** (at least 8 characters, mix of letters, numbers, symbols)
- ✅ **Verify your email** after registration
- ✅ **Log out** when using shared devices
- ✅ **Don't share** your password with anyone
- ✅ **Enable two-factor authentication** (if available in the future)
- ✅ **Keep your browser updated** for the latest security patches

---

## 📋 Security Checklist

Life Tracker implements the following security measures:

- [x] HTTPS encryption for all connections
- [x] Firebase Authentication with email verification
- [x] Firestore Security Rules for data isolation
- [x] Input validation and sanitization
- [x] XSS and CSRF protection
- [x] Rate limiting on sensitive operations
- [x] Audit logging for critical actions
- [x] Regular dependency updates
- [x] Secure password storage (hashed)
- [x] Session management and automatic expiration
- [x] European data centers (GDPR compliant)
- [x] Data export and deletion capabilities

---

## 🔄 Security Updates

Security updates are deployed automatically:

- **Critical vulnerabilities**: Fixed within 24-48 hours
- **High-priority issues**: Fixed within 1 week
- **Medium-priority issues**: Fixed within 2 weeks
- **Low-priority issues**: Fixed in the next regular update

Users are automatically updated when they reload the application (PWA auto-update).

---

## 📜 Compliance

Life Tracker is designed with privacy and security in mind:

- **GDPR compliant** — Data stored in European data centers
- **Data portability** — Export your data in CSV format
- **Right to deletion** — Delete your account and all data at any time
- **Transparency** — Clear information about data collection and usage

---

## 📞 Contact

For security-related questions or concerns:

- **GitHub**: [@AndreaBonn](https://github.com/AndreaBonn)
- **Security issues**: Contact me directly via GitHub profile

For general support, see the [README](./README.md).

---

## 🙏 Acknowledgments

I would like to thank the security researchers and users who have helped improve Life Tracker's security.

If you have reported a vulnerability and would like to be acknowledged, please let me know.

---

**Last updated:** January 2025

**© 2025 Andrea Bonacci — All Rights Reserved**

[![Versione Italiana](https://img.shields.io/badge/🇮🇹_Versione_Italiana-009246?style=flat-square)](./SECURITY_IT.md) &nbsp; [![README](https://img.shields.io/badge/📖_README-4A90E2?style=flat-square)](./README_EN.md)
