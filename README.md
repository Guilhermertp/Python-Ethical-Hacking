# Ethical Hacking with Python 🐍🔐

A hands-on collection of Python scripts and projects covering ethical hacking techniques — from network scanning to malware analysis and web application hacking.

> ⚠️ **Disclaimer:** This repository is intended for **educational purposes only**. All techniques demonstrated here should only be used in controlled environments with explicit permission. Unauthorized use of these tools is illegal and unethical.

---

## 📚 Table of Contents

| # | Section | Script |
|---|---------|--------|
| 1 | [Initial Setup & Linux Commands](https://github.com/Guilhermertp/Python-Ethical-Hacking/tree/main/Initial%20Setup%20%26%20Linux%20Commands) | — |
| 2 | [Writing a MAC Address Changer – Python Basics](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20a%20MAC%20Address%20Changer%20%E2%80%93%20Python%20Basics/mac_address_changer.py) | `mac_address_changer.py` |
| 3 | [MAC Changer – Algorithm Design](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/MAC%20Changer%20%E2%80%93%20Algorithm%20Design/mac_changer.py) | `mac_changer.py` |
| 4 | [Programming a Network Scanner](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Programming%20a%20Network%20Scanner/network_scanner.py) | `network_scanner.py` |
| 5 | [Writing an ARP Spoofer](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20an%20ARP%20Spoofer/arp_spoofer.py) | `arp_spoofer.py` |
| 6 | [Writing a Packet Sniffer](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20a%20Packet%20Sniffer/packet_sniffer.py) | `packet_sniffer.py` |
| 7 | [Writing a DNS Spoofer](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20a%20DNS%20Spoofer/dns_spoofer.py) | `dns_spoofer.py` |
| 8 | [Writing a File Interceptor](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20a%20File%20Interceptor/file_interceptor.py) | `file_interceptor.py` |
| 9 | [Writing a Code Injector](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20a%20Code%20Injector/code_injector.py) | `code_injector.py` |
| 10 | [Bypassing HTTPS](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Bypassing%20HTTPS/bypass_https.py) | `bypass_https.py` |
| 11 | [Writing an ARP Spoof Detector](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20an%20ARP%20Spoof%20Detector/arp_spoof_detector.py) | `arp_spoof_detector.py` |
| 12 | [Writing Malware](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20Malware/malware.py) | `malware.py` |
| 13 | [Writing Malware – Keylogger](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20Malware%20%E2%80%93%20Keylogger/keylogger.py) | `keylogger.py` |
| 14 | [Writing Malware – Backdoors](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20Malware%20%E2%80%93%20Backdoors/backdoor.py) | `backdoor.py` |
| 15 | [Writing Malware – Packaging](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20Malware%20%E2%80%93%20Packaging/malware_packaging.py) | `malware_packaging.py` |
| 16 | [Website / Web Application Hacking](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Website%20-%20Web%20Application%20Hacking/web_app_hacking.py) | `web_app_hacking.py` |
| 17 | [Website Hacking – Writing a Crawler](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Website%20Hacking%20%E2%80%93%20Writing%20a%20Crawler/web_crawler.py) | `web_crawler.py` |
| 18 | [Writing a Program to Guess Login Information](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20a%20Program%20to%20Guess%20Login%20Information/login_guesser.py) | `login_guesser.py` |
| 19 | [Writing a Vulnerability Scanner](https://github.com/Guilhermertp/Python-Ethical-Hacking/blob/main/Writing%20a%20Vulnerability%20Scanner/vulnerability_scanner.py) | `vulnerability_scanner.py` |

---

## 📁 Repository Structure

```
Python-Ethical-Hacking/
│
├── README.md
│
├── Initial Setup & Linux Commands/
│
├── Writing a MAC Address Changer – Python Basics/
│   └── mac_address_changer.py
│
├── MAC Changer – Algorithm Design/
│   └── mac_changer.py
│
├── Programming a Network Scanner/
│   └── network_scanner.py
│
├── Writing an ARP Spoofer/
│   └── arp_spoofer.py
│
├── Writing a Packet Sniffer/
│   └── packet_sniffer.py
│
├── Writing a DNS Spoofer/
│   └── dns_spoofer.py
│
├── Writing a File Interceptor/
│   └── file_interceptor.py
│
├── Writing a Code Injector/
│   └── code_injector.py
│
├── Bypassing HTTPS/
│   └── bypass_https.py
│
├── Writing an ARP Spoof Detector/
│   └── arp_spoof_detector.py
│
├── Writing Malware/
│   └── malware.py
│
├── Writing Malware – Keylogger/
│   └── keylogger.py
│
├── Writing Malware – Backdoors/
│   └── backdoor.py
│
├── Writing Malware – Packaging/
│   └── malware_packaging.py
│
├── Website - Web Application Hacking/
│   └── web_app_hacking.py
│
├── Website Hacking – Writing a Crawler/
│   └── web_crawler.py
│
├── Writing a Program to Guess Login Information/
│   └── login_guesser.py
│
└── Writing a Vulnerability Scanner/
    └── vulnerability_scanner.py
```

---

## 🛠️ Requirements

- Python 3.x
- Linux (Kali recommended) or a VM lab environment
- Common libraries: `scapy`, `requests`, `beautifulsoup4`, `pynput`

```bash
pip install scapy requests beautifulsoup4 pynput
```

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
