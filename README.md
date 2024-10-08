<h1>Azure Sentinel-Honeypot Project</h1>
<h2>Description</h2>
<b>The provided PowerShell script is designed to analyze Windows Event Log data in order to detect failed RDP attacks, following which it utilizes a third-party API to gather geographic details about the locations of the attackers.
</b>
<br />
<br />
For this project, I established Azure Sentinel (SIEM) and linked it to a running virtual machine that is functioning as a honeypot. We will be witnessing real-time RDP brute force attacks from various locations globally. With the help of a personalized PowerShell script, I plan to retrieve the geographical details of the attackers and display them on a map within Azure Sentinel.
<br />
<br />


<h2>Languages Used</h2>

- <b>PowerShell:</b> Extracts RDP failed logon logs from Windows Event Viewer

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API


<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

![image](https://github.com/user-attachments/assets/4f4ae2a2-900a-4b6f-8382-0da47689bda5)




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
