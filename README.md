# NETWORKWALKS-AUWAL-B084-WK1-PM1-WIRESHARK-LABS
# Week 1 - Extra Module: Wireshark SOC Analysis Labs

## Overview
Completed 6 interactive SOC analysis labs investigating network packet captures using Wireshark to analyze traffic, identify attackers, extract hidden data, and inspect VoIP communications.

## Summary of Completed Labs
1. **Lab 3 - Identify the Attacker's IP:** Identified attacker IP `192.168.10.66` targeting server `192.168.10.20` via a 40-port SYN scan.
2. **Lab 4 - Follow TCP Stream 1:** Analyzed unencrypted office chat on port 5000 (Stream 5) between Ali (`192.168.10.45`) and the server.
3. **Lab 5 - Follow TCP Stream (Part 2):** Discovered a hidden HTML comment in `/staff.html` (Stream 7) containing access code `Falcon-9921` and backup server IP `192.168.10.77`.
4. **Lab 6 - HTTP Plain Text Credentials:** Extracted cleartext login credentials from HTTP POST requests.
5. **Lab 7 - Catch the Brute Force Attacker:** Identified repeated unauthorized authentication attempts against target services.
6. **Lab 8 - VoIP Call Replay:** Reconstructed SIP call setup and RTP audio streams (PCMU codec) to identify caller Ali Raza (`ext 101`) and desk operator Sara.

## Lab Completion Evidence
- **Lab 3:** https://github.com/Azzurmawiy/NETWORKWALKS-AUWAL-B084-WK1-PM1-WIRESHARK-LABS/blob/main/Lab%203%20Result%20-%20Auwal%20Usman.png
- **Lab 4:** https://github.com/Azzurmawiy/NETWORKWALKS-AUWAL-B084-WK1-PM1-WIRESHARK-LABS/blob/main/Lab%204%20Result%20-%20Auwal%20Usman.png
- **Lab 5:** https://github.com/Azzurmawiy/NETWORKWALKS-AUWAL-B084-WK1-PM1-WIRESHARK-LABS/blob/main/Lab%205%20Result%20-%20Auwal%20Usman.png
- **Lab 6:** https://github.com/Azzurmawiy/NETWORKWALKS-AUWAL-B084-WK1-PM1-WIRESHARK-LABS/blob/main/Lab%206%20Result%20-%20Auwal%20Usman.png
- **Lab 7:** https://github.com/Azzurmawiy/NETWORKWALKS-AUWAL-B084-WK1-PM1-WIRESHARK-LABS/blob/main/Lab%207%20Result%20-%20Auwal%20Usman.png
- **Lab 8:** https://github.com/Azzurmawiy/NETWORKWALKS-AUWAL-B084-WK1-PM1-WIRESHARK-LABS/blob/main/Lab%208%20Result%20-%20Auwal%20Usman.png
