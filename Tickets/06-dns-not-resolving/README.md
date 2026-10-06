# Ticket 06: DNS Not Resolving

**Platform:** Spiceworks Help Desk  |  **OS:** Windows  |  **Status:** Resolved and closed

## Issue
Websites fail to load because DNS is not resolving.

## Troubleshooting Steps
1. Used `ping`, which failed to establish connectivity
2. Used `ipconfig /all` to get detailed IP address information
3. Used `ipconfig /flushdns` to flush the DNS resolver cache
4. Set Google's DNS in the IPv4 properties under Network Connections
5. Disabled and re-enabled the public firewall

## Resolution
Internet access was restored. Ticket closed in Spiceworks with troubleshooting notes.

## Screenshots
**1) Ticket Created**
<img width="1518" height="703" alt="ticket created" src="https://github.com/user-attachments/assets/0c0cee73-0a9a-4aeb-aac0-5a6cfa84df6a" />

**2) Used PING command**
<img width="580" height="372" alt="used PING command" src="https://github.com/user-attachments/assets/bae7d115-4fb5-4259-b424-b8841a2083e9" />

**3) Used IPCONFIG /ALL**
<img width="963" height="925" alt="used IPCONFIG ALL" src="https://github.com/user-attachments/assets/378c8498-c1a7-4d5b-9725-7fc3ade96bd8" />

**4) Used IPCONFIG /FLUSHDNS**
<img width="535" height="179" alt="used IPCONFIG FLUSH DNS" src="https://github.com/user-attachments/assets/496bb3dd-9a7d-4c48-9b0f-dc2b7bf954f0" />

**5) Set Google's DNS**
<img width="798" height="648" alt="used google&#39;s DNS in IPv4 settings" src="https://github.com/user-attachments/assets/f0dff1a5-848b-4207-a3ec-7f6fa076fd72" />

**6) Toggled Windows Firewall**
<img width="875" height="663" alt="toggled firewall settings" src="https://github.com/user-attachments/assets/ab9ca437-e01e-4592-b051-16b4144755c7" />

**7) Ticket Closed**
<img width="1521" height="690" alt="ticket closed" src="https://github.com/user-attachments/assets/dc79adf5-4e00-4c80-a924-e36e20268368" />

