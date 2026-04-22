# safeline-waf-dvwa-lab
SafeLine WAF + DVWA Lab Setup with Kali Linux &amp; Ubuntu (Attack Simulation)

# 🔐 SafeLine WAF + DVWA Lab

## 📌 Overview
Configured SafeLine WAF on Ubuntu to protect DVWA and tested attacks from Kali Linux.

## 🏗 Architecture
Kali → SafeLine → Apache → DVWA

## ⚙️ Setup
- Domain: dvwa.local
- Port: 8080
- Upstream: 127.0.0.1:80

## 🧪 Attacks Tested
- SQL Injection (`' OR 1=1#`)
- XSS (`<script>alert(1)</script>`)

## 🧠 Learnings
- WAF configuration
- Reverse proxy setup
- Debugging network & port issues

## 📄 Full Guide
See: safeline_dvwa_lab_guide.pdf
