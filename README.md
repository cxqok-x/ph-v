

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Flask-2.0%2B-black?style=for-the-badge&logo=flask"/>
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/PRs-Welcome-orange?style=for-the-badge"/>
</p>

<p align="center">
  <b>🔐 Next-Generation Phishing Simulation & Security Training Platform</b><br/>
  <i>For Authorized Security Professionals & Ethical Researchers Only</i>
</p>

---

## 📡 Live Demo

<p align="center">
  <img src="https://via.placeholder.com/800x450/0a0a0a/00ff41?text=🔴+SIMULATION+RUNNING" alt="Dashboard Preview"/>
</p>

---

## 🎯 Mission Statement

> *"To strengthen organizational security by simulating real-world threats in a controlled, ethical environment."*

This platform helps security teams:
- 🛡️ **Identify vulnerabilities** in human security layers
- 📊 **Measure awareness** through realistic scenarios
- 🚨 **Test incident response** capabilities
- 📈 **Generate actionable insights** for training programs

---

## ✨ Key Features

| Feature | Description | Status |
|---------|-------------|--------|
| 🎭 **Multi-Platform Simulation** | Instagram, Facebook, LinkedIn, Banking | ✅ |
| 🤖 **AI-Powered Analytics** | Behavioral pattern detection | 🚧 |
| 📱 **Responsive Design** | Mobile-optimized phishing pages | ✅ |
| 🔔 **Real-Time Alerts** | Slack/Email/SMS notifications | ✅ |
| 🗺️ **Geo-Location Tracking** | IP-based location mapping | ✅ |
| 🧪 **A/B Testing** | Compare campaign effectiveness | 🚧 |
| 📊 **Dashboard Analytics** | Visual campaign statistics | ✅ |
| 🔒 **Auto Data Deletion** | GDPR-compliant auto-purge | ✅ |
| 🎮 **Gamification** | Security awareness scoring | 🚧 |
| 🌐 **Multi-Language** | 10+ language support | 🚧 |

---

## 🧬 Architecture

```mermaid
graph TD
    A[User] -->|Clicks Link| B[Phishing Page]
    B -->|Credentials Entered| C[Backend API]
    C -->|Hash+Metadata| D[Logger Service]
    D -->|Trigger Rule| E[Alert Engine]
    E -->|Send Notification| F[SOC Team]
    C -->|Redirect| G[Error Page]
    H[Admin Dashboard] -->|View Logs| D
    H -->|Configure| I[Campaign Settings]
    J[Auto-Cleanup] -->|Delete Logs| D