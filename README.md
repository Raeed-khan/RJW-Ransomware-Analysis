# RJW Ransomware Analysis

> **Disclaimer:** This project is for educational and security research purposes only. The goal is to document ransomware mechanics and help improve threat detection.

## Safety Warning
Do not execute this sample or any related malware binaries on a live host system or personal Windows environment. Running ransomware on a primary OS will result in permanent file loss, system corruption, and potential network propagation. 

Always conduct malware analysis inside a fully isolated virtual machine (VirtualBox or VMware) with all network adapters disabled.

## Project Overview
This repository contains analysis notes and behavioral observations for the RJW ransomware variant.

Key Objectives:
* Observe execution behavior and system modifications in a sandbox.
* Document indicators of compromise (IOCs) such as file hashes and registry edits.
* Study potential defensive and mitigation measures.

![Malware Analysis Screenshot](malware_screenshot.png)

## Laboratory Setup
* Hypervisor: VirtualBox (Isolated Guest OS)
* Network Configuration: Disabled / Host-Only
* Analysis Tools: Process Monitor, x64dbg, Wireshark, Ghidra

## References
* CISA Cybersecurity Advisories
* MITRE ATT&CK Framework
