# task-4
1. Objective
To configure, test, and remove firewall rules using Windows Defender Firewall.
This demonstrates understanding of inbound/outbound rules and network filtering.

2. Steps Performed

Step 1: Open Firewall Tool
Opened:
Windows Defender Firewall with Advanced Security
Reviewed existing inbound and outbound rules.

Step 2: Create Firewall Rule to Block Port 23 (Telnet)
Created a new Inbound Rule
Type: Port
Protocol: TCP
Port: 23
Action: Block the connection
Profiles: Domain, Private, Public
Name: Block Telnet (Port 23)

Step 3: Test the Rule
Ran this command:
telnet 127.0.0.1 23

Result: Connection failed, confirming the firewall successfully blocked the port.

Step 4: Remove the Rule
After testing, I deleted the “Block Telnet (Port 23)” rule to restore the system.
<img width="1599" height="899" alt="Screenshot 2025-11-25 164120" src="https://github.com/user-attachments/assets/292cd6d3-f3e8-4967-801e-7a60d984c555" />
<img width="1599" height="899" alt="Screenshot 2025-11-25 164154" src="https://github.com/user-attachments/assets/fabde4e7-39de-47f1-9879-5ec1c8b30904" />
<img width="753" height="618" alt="Screenshot 2025-11-25 164455" src="https://github.com/user-attachments/assets/e5f34bb3-7c5c-462f-8d98-304c915da512" />
<img width="735" height="608" alt="Screenshot 2025-11-25 164643" src="https://github.com/user-attachments/assets/06ceae5d-4048-4ac2-96d4-9109f203b94e" />
<img width="636" height="237" alt="Screenshot 2025-11-25 165147" src="https://github.com/user-attachments/assets/d75d6f98-1c85-4788-bc7a-62c217af89e7" />
<img width="1037" height="778" alt="Screenshot 2025-11-25 165311" src="https://github.com/user-attachments/assets/74518142-bfde-45fe-86dd-0a60029ad9ac" />
