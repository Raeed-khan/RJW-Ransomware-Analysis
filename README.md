# RJW Ransomware Analysis

> **Disclaimer:** This project was created for educational and security research purposes only. I am sharing my findings to help students and researchers understand ransomware behavior and defense mechanisms.

---

## 🛑 SAFETY WARNING
Do **NOT** run this sample or any related scripts on your main host machine or personal Windows PC. Executing ransomware on a live system will lead to:
- Permanent encryption and loss of personal files (photos, documents, system files).
- System crash and potential registry corruption.
- Risk of spreading across your local Wi-Fi / home network.

All analysis must be conducted inside a fully isolated Virtual Machine (VirtualBox/VMware) with networking set to **Disabled** or **Host-Only**.

---

## 📌 About This Project
This repository documents my hands-on research on the RJW ransomware variant. The primary goals of this project are:
* **Behavior Tracking:** Observing how the payload executes and interacts with the Windows environment.
* **IOC Extraction:** Identifying file hashes, registry modifications, and dropped files.
* **Defense & Detection:** Studying ways to mitigate, block, and analyze similar malware threats safely.

---

## 👥 Research Team & Credits
