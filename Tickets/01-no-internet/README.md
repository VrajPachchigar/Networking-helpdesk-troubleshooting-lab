# Ticket 01: No Internet

**Platform:** Spiceworks Help Desk  |  **OS:** Windows  |  **Status:** Resolved and closed

## Issue
User reports no internet access.

## Troubleshooting Steps
1. Checked the physical LAN cable connection
2. Disconnected and reconnected to Wi-Fi on the user's machine
3. Checked the network adapter in Device Manager
4. Used `ping` to test internet connectivity
5. Used `ipconfig` to check the IP configuration
6. Used `ipconfig /release` and `ipconfig /renew` to refresh the IP address from DHCP
7. Ran a network reset from Windows Settings
8. Rebooted the machine

## Resolution
User's internet was up and running. Ticket closed in Spiceworks with troubleshooting notes.

## Screenshots
<!-- Put your screenshots in the screenshots/ folder, then uncomment and rename the lines below -->
![Ticket created](screenshots/no internet ticket created.png)
![ipconfig output](screenshots/02-ipconfig.png)
![Ticket closed](screenshots/03-ticket-closed.png)
