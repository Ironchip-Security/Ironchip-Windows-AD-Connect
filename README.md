<h1 align="center">Ironchip Windows AD Connect</h1>

<p align="center">
  <a href="https://github.com/Ironchip-Security/Ironchip-Windows-AD-Connect/releases/latest">
    <img alt="Latest release" src="https://img.shields.io/github/v/release/Ironchip-Security/Ironchip-Windows-AD-Connect?color=green"/>
  </a>

  <a href="https://github.com/Ironchip-Security/Ironchip-Windows-AD-Connect/releases/latest">
    <img alt="Release date" src="https://img.shields.io/github/release-date/Ironchip-Security/Ironchip-Windows-AD-Connect?color=orange"/>
  </a>
</p>

## IDENTITY PROTECTION

Elevate your cybersecurity strategy with Ironchip Identity Platform, designed to bring the power of Multi-Factor Authentication (MFA) to your desktop computing environment. [Know more](https://www.ironchip.com/en/mobileless-authentication).

**Role-based privilege management:** Set different user privileges to prevent unauthorized users from misusing the system.

**Restrict access from unauthorized places:** Limit access to authorized areas for enhanced security.

**Supervision of accesses in real time:** Monitor user activity, view access history, generate reports, and download them for complete control.

**Intrusion detection system (IDS):** Receive alerts for SIM swapping, phishing, device switching, and more.

---

### Download

Download the latest Ironchip AD Connect binary for your system:

<p align="left">
  <a href="https://github.com/Ironchip-Security/Ironchip-Windows-AD-Connect/releases/latest">
    <img alt="Download Ironchip Module" src="https://custom-icon-badges.demolab.com/badge/-Download%20Module-blue?style=for-the-badge&logo=download&logoColor=white">
  </a>
</p>

---

## Installation & Configuration

### Step 1: Install service
**Installing the service requires a terminal with Administrator privileges**

Install the service for auto-start when the device powers on:

```bash
./ironchip-ad-connect.exe s install
```

### Step 2: Start service
Start the service to use without restarting device:

```bash
./ironchip-ad-connect.exe s start
```
### Step 3: Configure
Configure necessary credentials in http://localhost:10300

---

### Uninstall / Revert

To remove Ironchip AD Connect service:

1. Stop the running service:

```bash
./ironchip-ad-connect.exe s stop
```
2. Uninstall the service:

```bash
./ironchip-ad-connect.exe s uninstall
```
