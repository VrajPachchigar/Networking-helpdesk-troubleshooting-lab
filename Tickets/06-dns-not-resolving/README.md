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
<!-- Put your screenshots in the screenshots/ folder, then uncomment and rename the lines below -->
<!-- ![Ticket created](screenshots/01-ticket-created.png) -->
<!-- ![ipconfig output](screenshots/02-ipconfig.png) -->
<!-- ![Ticket closed](screenshots/03-ticket-closed.png) -->
