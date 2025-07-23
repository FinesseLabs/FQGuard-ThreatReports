# 🛡️ Finesse Threat Reports

This repo documents real-world cybersecurity threat detection and response from my personal home network, powered by GL.iNet routers, WiFi Pineapple, and FQGuardBot (custom alert system). All reports are based on actual logged data and home lab defense.

---

## 🔍 Incident: Unauthorized Device "mk7"
**Date:** July 21, 2025  
**MAC Address:** `00:3F:10:A4:79:B0`  
**Vendor:** Shenzhen GainStrong Technology Co., Ltd.  
**IP Address:** Private IP `(192.168.x.x)` 
**Ports Open:** 22 (SSH), 53 (DNS), 80 (HTTP)  
**Status:** Blocked and removed after detection  
**Threat Level:** Medium-High  
**Report:** [View Full Report](./Finesse_Incident_Report_072125_FINAL.pdf)





---

## 🕵🏽‍♀️ Detection Timeline

| Time | Event |
|------|-------|
| 12:16 AM | Device first joined the network |
| 6:50 PM | Appeared in WiFi Pineapple logs |
| 7:43 PM | MAC redetected on main LAN |
| 8:36 PM | Confirmed active on router labeled as "mk7" |
| 10:00 PM | Device blocked + router rebooted — threat removed |

---

## 🧠 Analyst Notes

This device was detected across multiple platforms (WiFi Pineapple + router logs), indicating probable local probing. Vendor lookup confirmed it as a low-cost network device manufacturer. The MAC address was blocked, and WPS/guest WiFi disabled to prevent future access.

---

## 📁 Files in this Repo

| File | Description |
|------|-------------|
| `Finesse_Threat_Report_2025-07-21.pdf` | Full report with timeline, actions taken, and evidence |
| ![Intruder SS](./intruder.jpg) | Screenshot showing live threat presence in router UI |

---

## 🎯 Goal of This Repo
To document real attacks and network intrusions in a transparent, educational format — and to showcase my growing skills in cybersecurity defense 👩🏾‍💻🔥

---

### 📲 Follow My Cyber Journey  
TikTok: `@finesse_unfiltered`  
More projects coming soon via Finesse Labs™
