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
**1) Ticket created**
<img width="1533" height="662" alt="ticket created" src="https://github.com/user-attachments/assets/943f7663-fb1a-4107-8b78-57ff505ffa91" />

**2) Used IPCONFIG /RELEASE and IPCONFIG /RENEW**
<img width="1112" height="619" alt="used IPCONFIG RELEASE" src="https://github.com/user-attachments/assets/be4ad22d-23c4-483d-a19e-29db8eff3345" />
<img width="1107" height="638" alt="used IPCONFIG RENEW" src="https://github.com/user-attachments/assets/e21edda8-a09b-47b8-992b-100154a8b833" />

**3) Used IPCONFIG ALL**
<img width="1028" height="931" alt="used IPCONFIG ALL" src="https://github.com/user-attachments/assets/e4a1c3fd-1508-4fe9-9c51-9379d1e82197" />

**4) Closed ticket**
<img width="1522" height="674" alt="closed the ticket" src="https://github.com/user-attachments/assets/48d6ccc1-e429-43b9-9f27-96ca20173339" />

