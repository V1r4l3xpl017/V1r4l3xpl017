```text
#                                                                                        
#     ▄    ▄ ▄▄▄              ▄▄  ▀▀█     ▄▄▄▄                ▀▀█     ▄▄▄▄  ▄▄▄    ▄▄▄▄▄▄
#     ▀▄  ▄▀   █     ▄ ▄▄    ▄▀█    █    ▀   ▀█ ▄   ▄  ▄▄▄▄     █    ▄▀  ▀▄   █        █▀
#      █  █    █     █▀  ▀  █▀ █    █      ▄▄▄▀  █▄█   █▀ ▀█    █    █  ▄ █   █       ▄▀ 
#      ▀▄▄▀    █     █     █▄▄▄█▄   █        ▀█  ▄█▄   █   █    █    █    █   █      ▄▀  
#       ██   ▄▄█▄▄   █         █    ▀▄▄  ▀▄▄▄█▀ ▄▀ ▀▄  ██▄█▀    ▀▄▄   █▄▄█  ▄▄█▄▄   ▄▀   
#                                                      █                                 
#                                                      ▀                         

root@v1r4l3xpl017:~# cat /etc/motto
read the code, break the assumptions, write it up properly.

root@v1r4l3xpl017:~# cat about.txt
|=[ about.txt ]=-----------------------------------------------------------|
+--------------------------------------------------------------------------+
| Developer and DevSecOps turned to offensive security. Years of shipping  |
| web apps and APIs taught me where the corners get cut, because I was the |
| one cutting them. Now I go looking for those corners on purpose.         |
+--------------------------------------------------------------------------+
|=[ EOF ]=-----------------------------------------------------------------|
root@v1r4l3xpl017:~# cat toc.txt
|=[ Table of Contents ]=---------------------------------------------------|
+------+----------------------+--------------------------------------------+
| ID   | FILE                 | CONTENTS                                   |
+======+======================+============================================+
| 0x01 | stats.txt            | certs, studying, bug bounty, CTFs, CVEs    |
+------+----------------------+--------------------------------------------+
| 0x02 | interests.txt        | areas of focus: web, AD, Wi-Fi, bounty     |
+------+----------------------+--------------------------------------------+
| 0x03 | services.txt         | what I offer and how engagements run       |
+------+----------------------+--------------------------------------------+
| 0x04 | arsenal.txt          | skills, tools, languages and infra         |
+------+----------------------+--------------------------------------------+
| 0x05 | disclosure.txt       | how I report what I find                   |
+------+----------------------+--------------------------------------------+
|=[ EOF ]=-----------------------------------------------------------------|
root@v1r4l3xpl017:~# cat stats.txt
#                                       
#      ▄▄▄▄ ▄▄▄▄▄▄▄   ▄▄  ▄▄▄▄▄▄▄  ▄▄▄▄ 
#     █▀   ▀   █      ██     █    █▀   ▀
#     ▀█▄▄▄    █     █  █    █    ▀█▄▄▄ 
#         ▀█   █     █▄▄█    █        ▀█
#     ▀▄▄▄█▀   █    █    █   █    ▀▄▄▄█▀
#                                       
#                                       
|=[ 0x01 ]=[ stats.txt ]=--------------------------------------------------|
+------------+-------------------------------------------------------------+
| KEY        | DETAIL                                                      |
+============+=============================================================+
| certs      | Penetration Testing, CESAR School + Tempest                 |
+------------+-------------------------------------------------------------+
| studying   | CPTS (HTB)                                                  |
+------------+-------------------------------------------------------------+
| bugbounty  | Hackerone, Bughunt                                          |
+------------+-------------------------------------------------------------+
| ctfs       | HTB and Hacking Club                                        |
+------------+-------------------------------------------------------------+
| cves       | 0 (first one goes to security-advisories after the fix)     |
+------------+-------------------------------------------------------------+
|=[ EOF ]=-----------------------------------------------------------------|
root@v1r4l3xpl017:~# cat interests.txt
#                                                                   
#     ▄▄▄▄▄  ▄▄   ▄▄▄▄▄▄▄▄ ▄▄▄▄▄▄ ▄▄▄▄▄  ▄▄▄▄▄▄  ▄▄▄▄ ▄▄▄▄▄▄▄  ▄▄▄▄ 
#       █    █▀▄  █   █    █      █   ▀█ █      █▀   ▀   █    █▀   ▀
#       █    █ █▄ █   █    █▄▄▄▄▄ █▄▄▄▄▀ █▄▄▄▄▄ ▀█▄▄▄    █    ▀█▄▄▄ 
#       █    █  █ █   █    █      █   ▀▄ █          ▀█   █        ▀█
#     ▄▄█▄▄  █   ██   █    █▄▄▄▄▄ █    ▀ █▄▄▄▄▄ ▀▄▄▄█▀   █    ▀▄▄▄█▀
#                                                                   
#                                                                    
|=[ 0x02 ]=[ interests.txt ]=----------------------------------------------|
+----+--------------------------+------------------------------------------+
| ID | AREA                     | DESCRIPTION                              |
+====+==========================+==========================================+
| 01 | Web & API Security       | Access control, authentication and       |
|    |                          | authorization, injection, SSRF, business |
|    |                          | logic and API security, tested the way   |
|    |                          | an attacker reads the app.               |
|    |                          | [FOCUS] Access Control | Auth | API      |
+----+--------------------------+------------------------------------------+
| 02 | Active Directory         | Enumeration, Kerberos and NTLM attacks,  |
|    |                          | ACL and delegation abuse, ADCS and the   |
|    |                          | path to Domain Admin.                    |
|    |                          | [FOCUS] Kerberos | NTLM | ADCS           |
+----+--------------------------+------------------------------------------+
| 03 | Wi-Fi Security           | WPA2 and WPA-Enterprise testing, rogue   |
|    |                          | AP and evil-twin setups, guest-to-       |
|    |                          | corporate segmentation and MitM.         |
|    |                          | [FOCUS] WPA2 | Enterprise | Evil Twin    |
+----+--------------------------+------------------------------------------+
| 04 | Bug Bounty & Disclosure  | Hunting on in-scope programs, writing    |
|    |                          | reports that get fixed, and coordinated  |
|    |                          | disclosure with CVEs when it applies.    |
|    |                          | [EXPLORE] Bug Bounty | CVE               |
+----+--------------------------+------------------------------------------+
|=[ EOF ]=-----------------------------------------------------------------|
root@v1r4l3xpl017:~# cat services.txt
#                                                            
#      ▄▄▄▄  ▄▄▄▄▄▄ ▄▄▄▄▄  ▄    ▄ ▄▄▄▄▄    ▄▄▄  ▄▄▄▄▄▄  ▄▄▄▄ 
#     █▀   ▀ █      █   ▀█ ▀▄  ▄▀   █    ▄▀   ▀ █      █▀   ▀
#     ▀█▄▄▄  █▄▄▄▄▄ █▄▄▄▄▀  █  █    █    █      █▄▄▄▄▄ ▀█▄▄▄ 
#         ▀█ █      █   ▀▄  ▀▄▄▀    █    █      █          ▀█
#     ▀▄▄▄█▀ █▄▄▄▄▄ █    ▀   ██   ▄▄█▄▄   ▀▄▄▄▀ █▄▄▄▄▄ ▀▄▄▄█▀
#                                                            
#                                                            
|=[ 0x03 ]=[ services.txt ]=-----------------------------------------------|
+----+--------------------------+------------------------------------------+
| ID | SERVICE                  | DESCRIPTION                              |
+====+==========================+==========================================+
| 01 | Web & API Pentest        | Black/gray-box testing of web apps and   |
|    |                          | REST APIs. PoC, impact and fix for every |
|    |                          | finding.                                 |
+----+--------------------------+------------------------------------------+
| 02 | Active Directory Pentest | Assumed-breach engagements, from the     |
|    |                          | first foothold to Domain Admin.          |
+----+--------------------------+------------------------------------------+
| 03 | Wi-Fi Assessment         | Wireless security testing and guest-to-  |
|    |                          | corporate segmentation review.           |
+----+--------------------------+------------------------------------------+
| 04 | Secure Code Review       | Source review for the bugs a black-box   |
|    |                          | test never reaches.                      |
+----+--------------------------+------------------------------------------+
| 05 | Cloud & Infra Hardening  | IAM, Terraform, Ansible and Kubernetes   |
|    |                          | review, with the patch attached.         |
+----+--------------------------+------------------------------------------+
| 06 | Report & Retest          | Dev-ready write-up, executive summary    |
|    |                          | and a retest once the fixes land.        |
+----+--------------------------+------------------------------------------+
| scope: every engagement is authorized in writing before any test         |
|=[ EOF ]=-----------------------------------------------------------------|
root@v1r4l3xpl017:~# cat arsenal.txt
#                                                     
#       ▄▄   ▄▄▄▄▄   ▄▄▄▄  ▄▄▄▄▄▄ ▄▄   ▄   ▄▄   ▄     
#       ██   █   ▀█ █▀   ▀ █      █▀▄  █   ██   █     
#      █  █  █▄▄▄▄▀ ▀█▄▄▄  █▄▄▄▄▄ █ █▄ █  █  █  █     
#      █▄▄█  █   ▀▄     ▀█ █      █  █ █  █▄▄█  █     
#     █    █ █    ▀ ▀▄▄▄█▀ █▄▄▄▄▄ █   ██ █    █ █▄▄▄▄▄
#                                                     
#                                                     

|=[ 0x04 ]=[ arsenal.txt ]=------------------------------------------------|
+------------+-------------------------------------------------------------+
| GROUP      | ITEMS                                                       |
+============+=============================================================+
| SKILLS     | [Penetration Testing] [Web / API Security]                  |
|            | [Active Directory] [Wi-Fi Security] [Bug Bounty]            |
|            | [Secure Code Review] [CTF Player]                           |
+------------+-------------------------------------------------------------+
| TOOLS      | [Burp Suite] [Nmap] [Metasploit] [Kali Linux] [BloodHound]  |
|            | [Aircrack-ng]                                               |
+------------+-------------------------------------------------------------+
| LANGUAGES  | [TypeScript] [Node.js] [Go] [Ruby] [Python] [Bash] [SQL]    |
+------------+-------------------------------------------------------------+
| INFRA      | [AWS] [Kubernetes] [Docker] [Terraform] [Ansible] [Linux]   |
+------------+-------------------------------------------------------------+
|=[ EOF ]=-----------------------------------------------------------------|
root@v1r4l3xpl017:~# cat disclosure.txt
#                                                                          
#     ▄▄▄▄   ▄▄▄▄▄   ▄▄▄▄    ▄▄▄  ▄       ▄▄▄▄   ▄▄▄▄  ▄    ▄ ▄▄▄▄▄  ▄▄▄▄▄▄
#     █   ▀▄   █    █▀   ▀ ▄▀   ▀ █      ▄▀  ▀▄ █▀   ▀ █    █ █   ▀█ █     
#     █    █   █    ▀█▄▄▄  █      █      █    █ ▀█▄▄▄  █    █ █▄▄▄▄▀ █▄▄▄▄▄
#     █    █   █        ▀█ █      █      █    █     ▀█ █    █ █   ▀▄ █     
#     █▄▄▄▀  ▄▄█▄▄  ▀▄▄▄█▀  ▀▄▄▄▀ █▄▄▄▄▄  █▄▄█  ▀▄▄▄█▀ ▀▄▄▄▄▀ █    ▀ █▄▄▄▄▄
#                                                                          
#                                                                          
|=[ 0x05 ]=[ disclosure.txt ]=---------------------------------------------|
+--------------------------------------------------------------------------+
| Reports stay private until the vendor has had time to fix.               |
|                                                                          |
| Policy and templates:                                                    |
| https://github.com/V1r4l3xpl017/security-advisories                      |
+--------------------------------------------------------------------------+
|=[ EOF ]=-----------------------------------------------------------------|
root@v1r4l3xpl017:~# 
```
