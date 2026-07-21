# RJW Ransomware & Steganography Analysis

> **Disclaimer:** This repository is for educational, academic, and security research purposes only. It is intended to document malware mechanisms and defensive techniques.

## Safety Warning
Do not execute this sample or any related binaries on a host machine or personal Windows environment. Running ransomware on a primary OS will result in permanent file encryption, system corruption, and potential network propagation.

Always perform testing inside a fully isolated virtual machine (VirtualBox or VMware) with all network adapters disabled.

## Project Overview
This repository contains analysis notes and behavioral observations for the RJW ransomware variant, along with research on steganographic techniques used for stealthy payload delivery and data hiding.

Key Objectives:
* Analyze malware execution behavior and system modifications in a sandbox environment.
* Extract indicators of compromise (IOCs) such as file hashes and registry edits.
* Study steganography methods used to conceal payloads within media files during delivery or extraction.
* Document defensive strategies and mitigation steps to protect systems.

## Laboratory Setup
* Hypervisor: VirtualBox (Isolated Guest OS)
* Network Configuration: Disabled / Host-Only
* Analysis Tools: Process Monitor, x64dbg, Wireshark, Ghidra

## Author & Researcher
* **Raeed Khan**
* **Role:** Certified Ethical Hacker (CEH) & Security Researcher (Student UOB)
* **GitHub:** [Raeed-khan](https://github.com/Raeed-khan)

## References
* CISA Cybersecurity Advisories
* MITRE ATT&CK Framework
