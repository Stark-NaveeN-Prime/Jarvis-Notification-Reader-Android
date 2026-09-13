# JARVIS Notifications Reader

> An offline-first Android utility designed to capture, filter, parse, and manage real-time device notification streams, distributed under a cryptographic serial-key subscription model.

---

## Table of Contents

1. [Executive Summary](#executive-summary)
2. [Core Capabilities](#core-capabilities)
3. [Technical Specifications & Permissions](#technical-specifications--permissions)
4. [Licensing & Subscription Tiers](#licensing--subscription-tiers)
5. [Activation Procedure](#activation-procedure)
6. [Security, Privacy & Anti-Abuse](#security-privacy--anti-abuse)
7. [Terms & Legal Disclaimers](#terms--legal-disclaimers)
8. [Support & Official Channels](#support--official-channels)

---

## Executive Summary

**JARVIS Notifications Reader** is an Android software utility developed and published by **StarkNaveenPrime**. The application allows end-users to read, organize, isolate, and interact with incoming system and third-party app notifications through a structured interface.

Premium tiers are enforced via non-cloud-dependent, time-limited serial license keys. This architecture ensures high operational reliability and user privacy by avoiding unnecessary remote telemetry servers.

---

## Core Capabilities

* **Real-Time Notification Interception:** Streams and records notification events instantly upon receipt by the Android subsystem.
* **Notification Filtering & Deduplication:** Eliminates repetitive push alerts and prioritizes high-importance application updates.
* **Local Offline Verification:** License validation operates independently of persistent network connections or third-party cloud auth backends.
* **Transaction Transparency:** Full integration with offline billing standards, providing structured transaction receipts and verifiable records.

---

## Technical Specifications & Permissions

### System Requirements
* **Platform:** Android (OS version support based on target APK build release)
* **Architecture:** ARM64 / Universal Android runtime

### Elevated Permissions Required
* `android.permission.BIND_NOTIFICATION_LISTENER_SERVICE`
  * **Scope & Purpose:** Mandatory system-level permission required to access notification payloads, source package names, and alert events.
  * **Privacy Guarantee:** Notification content remains strictly on the client hardware. No alert data, personal communications, or package telemetry are uploaded to external clouds or servers.

---

## Licensing & Subscription Tiers

Access to premium software features is structured strictly as **time-limited, non-auto-renewing subscription licenses**. Lifetime license models are not offered under this release. Continued software access following expiration requires manual renewal.

| Tier | Duration | Base Retail Price | Renewal Protocol |
| :--- | :--- | :--- | :--- |
| **Monthly** | 1 Month (30 Days) | ₹49 | Manual purchase; replacement serial key issued |
| **Quarterly** | 3 Months (90 Days) | ₹99 | Manual purchase; replacement serial key issued |
| **Six-Month** | 6 Months (180 Days) | ₹179 | Manual purchase; replacement serial key issued |
| **Yearly** | 12 Months (365 Days) | ₹299 | Manual purchase; replacement serial key issued |

> **License Policy:** Unless explicitly specified in writing, one purchased serial key entitles the purchaser to single-device activation.

---

## Activation Procedure

1. **Deployment:** Download and install the official package `JARVIS_Notifications_Reader.apk`.
2. **System Permission:** Open system settings when prompted and activate **Notification Access** for JARVIS Notifications Reader.
3. **Key Input:** Navigate to **Settings > License Activation** within the application.
4. **Validation:** Enter your issued 16-character alphanumeric key:
   ```text
   JRVS-XXXX-XXXX-XXXX
