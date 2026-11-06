---
layout: single
title: "Lab Challenges"
permalink: /labs/
author_profile: true
---

### Lab Challenge 1: Hack The Box – Network Enumeration & PCAP Analysis
* **Problem Statement:** Analyze an unknown PCAP capture file to identify anomalous network activity, reconstruct protocol streams, and extract embedded payload flags.
* **Approach:** Filtered packet captures by protocol type (HTTP, DNS, TCP), isolated suspicious sessions, and extracted exfiltrated data.
* **Tools Used:** Wireshark, Tshark, HTB Pwnbox / Parrot OS.
* **Key Lessons Learned:** Cleartext protocols expose sensitive operational data; enforcing TLS/SSL across all network boundaries is essential.

### Lab Challenge 2: Cisco Packet Tracer Security & Topology Configuration
* **Problem Statement:** Implement Layer 2 switch port security and Access Control Lists (ACLs) to block unauthorized network devices and VLAN traversing.
* **Approach:** Applied static/sticky MAC address security binding and configured extended IP ACLs to restrict unauthorized Inter-VLAN routing.
* **Tools Used:** Cisco Packet Tracer.
* **Key Lessons Learned:** Layer 2 defense mechanisms block threat actors before traffic ever reaches Layer 3 firewalls.
