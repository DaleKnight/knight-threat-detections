# 📧 Email Security Detections

Detection engineering focused on phishing, spoofing, and business email compromise (BEC) scenarios using Microsoft Sentinel and Defender XDR.

---

## 🚨 Detections

### VIP Display Name Impersonation – Sender Mismatch
Detects potential BEC attacks where a trusted display name is used but the sender is unauthorized.

👉 [View Detection](vip-displayname-impersonation.md)

---

### Inbound DMARC Domain Spoof – Auth Failure Correlation
Detects inbound spoofing attempts using SPF/DKIM/DMARC failures and composite authentication.

👉 [View Detection](inbound-dmarc-domain-spoof.md)
