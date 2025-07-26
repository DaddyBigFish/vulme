<img src="https://github.com/user-attachments/assets/502369e5-0489-4de4-89a1-00beea33720e" alt="vulme" width="150"/>      

# Description
The tool vulme was designed to aid in the search for existing vulnerabilities by querying WAZUH's CVE database directly from the command line.
# Installation
```
sudo wget https://github.com/DaddyBigFish/vulme/raw/refs/heads/main/vulme -O /usr/local/bin/vulme; sudo chmod +x /usr/local/bin/vulme
```
# Example
```
vulme vsFTPd 2.3.4
┏━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━┳━━━━━━━┳━━━━━━━━━┓
┃ CVE           ┃ Description                                                                                                     ┃ Date       ┃ Score ┃ Metric  ┃
┡━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━╇━━━━━━━╇━━━━━━━━━┩
│ CVE-2011-2523 │ vsftpd 2.3.4 downloaded between 20110630 and 20110703 contains a backdoor which opens a shell on port 6200/tcp. │ 2019/11/27 │ 9.8   │ CVSS3.1 │
└───────────────┴─────────────────────────────────────────────────────────────────────────────────────────────────────────────────┴────────────┴───────┴─────────┘
                                         Vulnerabilities identified for vsFTPd 2.3.4               vulme by DaddyBigFish
```
