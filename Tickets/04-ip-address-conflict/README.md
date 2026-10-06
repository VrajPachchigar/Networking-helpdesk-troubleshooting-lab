# Ticket 04: IP Address Conflict

**Platform:** Spiceworks Help Desk  |  **OS:** Windows  |  **Status:** Resolved and closed

## Issue
Machine reports an IP address conflict on the network.

## Troubleshooting Steps
1. Used `ipconfig /release` and `ipconfig /renew` to get a new IP address from DHCP
2. Used `ipconfig /all` to identify the DHCP server's address
3. Reconnected to the Wi-Fi network
4. Rebooted the computer to get a fresh IP from the DHCP server

## Resolution
Machine obtained a fresh IP address and the conflict was cleared. Ticket closed in Spiceworks with troubleshooting notes.

## Screenshots
<!-- Put your screenshots in the screenshots/ folder, then uncomment and rename the lines below -->
<!-- ![Ticket created](screenshots/01-ticket-created.png) -->
<!-- ![ipconfig output](screenshots/02-ipconfig.png) -->
<!-- ![Ticket closed](screenshots/03-ticket-closed.png) -->
