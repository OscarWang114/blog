---
title:  "5/27 Today I Learned"
date:   2018-05-27 23:40:00 +0800
categories: [ til ]
tags: [ til ]
toc: true
toc_label: "Items"
toc_icon: "list-ul"
---

## Two-factor authentication (2FA)
* Requires users to present 2 different evidences/factors to confirm their identity.
* The 2 factors can be 'something they know', 'something they have', or 'something they are'.
* Example: To withdraw money from an ATM, you need **a password you know** + **a bank card you have**.
* Generalization: Multi-factor authentication.

## Two-step authentication
* Similar to 2FA, but uses 'something they know' + a second factor other than 'something they have', or 'something they are'.
* The second factor can be a code sent via text, voice call, or an app.
* Example: [Google Authenticator](https://github.com/google/google-authenticator/wiki/Key-Uri-Format) provides a 6- to 8-digit one-time password.

## One-time password (OTP) Revisited
* HMAC-based One-Time Password algorithm (HOTP) generates OTP using **a secret and a counter** both shared by the client and server. The counter increments every time a password is created to keep the client and server in sync.
* HMAC stands for Hash-based Message Authentication Code.
* Time-based One-Time Password algorithm (TOTP) is similar to HOTP but **replaces the counter with the current time stamp**. To tolerate network latency and out-of-sync clocks, the timestamp usually **increments in 30-second intervals**.
* The shared secret (and the HOTP counter) needs to be communicated to the client and server at some time. Google Authenticator does this a using QR code encoded URI.

## WAI-ARIA
* WAI: Web Accessibility Initiative
* WAI-ARIA: Accessible Rich Internet Application Suite. It defines a way to make Web content and applications more accessible to people with disabilities.
* [Overview](https://www.w3.org/WAI/standards-guidelines/aria/)

## Caveat
* Pronunciation: Kaviat
* Meaning: A warning or caution of specific conditions or limitations
