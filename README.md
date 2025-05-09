# 🔍 Chronicle YARA-L Detection Rules Portfolio

This repository contains my custom-built **YARA-L detection rules for Google Chronicle SecOps**, developed through rigorous self-study, hands-on practice, and real-world detection logic for Tier 1 SOC analysis.

## 📌 About This Project

These detection rules were crafted to identify suspicious and malicious activity across multiple telemetry fields in Chronicle, including:
 
  "Soc Tier1 Scope"
  #file-
- `file.name`
- `file.sha256`
  #network-
- `network.connection.dst_ip`
  #HTTP
- `http.request.uri`
- `http.request.user_agent`
  #DNS
- `dns.question.name`
  #Email/User
- `user.email`
  #Hex-encoded payloads

  "Soc Tier 2 Scope"

Each rule includes meaningful metadata, clean logic, and real-world use cases — ideal for SOC teams looking to strengthen visibility into common attack vectors.

---
