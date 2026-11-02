# Windows Security Monitoring

## Overview
Comprehensive guide on how to look for different log sources including Sysmon and correlating logs for investigation of SOC.

## Topics Covered

## **Windows Logging for SOC**

*Key concepts:* Security Log, Sysmon, Powershell, EventIDs

**What I learned:**

- **Windows log sources:** Different logs generated in Windows including Sysmon
- **Corellating logs:** Log analysis to track attackers' digital footprints
- **Event IDs and Sysmon Event IDs:** Different event IDs to track attacker and hands-on filtering techniques


**Opening EVTX file in notepad**

![opening_evtx_notepad](./screenshots/opening_evtx_notepad.png)


**Event IDs**

![event_ids](./screenshots/event_ids.png)

---

**Sarah Miller opened Google Chrome for her browsing and saved malware path**

![browser_used_and_path](./screenshots/browser_used_and_path.png)


**Bruteforcing logs source IP**

![bruteforcing_ip](./screenshots/bruteforcing_ip.png)

---

**Followed by compromised user: Administrator**

![compromised_user](./screenshots/compromised_user.png)

---

**Created new user: svc_sysrestore found in log**

![new_user_created](./screenshots/new_user_created.png)

---

**Persistence Path for persistence**

![persistence_path](./screenshots/persistence_path.png)

---

**Attacker created user for persistence and added it to group: Backup Operators**

![added_group1](./screenshots/added_group1.png)

---

**Attacker created user for persistence and added it to group: Remote Desktop Users**

![added_group2](./screenshots/added_group2.png)

---

**Malware connected to C2 IP**

![c2_connected_to_ip](./screenshots/c2_connected_to_ip.png)

---

**Windows Logging for SOC Conclusion**

![conclusion](./screenshots/conclusion.png)

