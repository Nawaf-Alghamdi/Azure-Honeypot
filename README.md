<h1>Azure Sentinel-Honeypot Project</h1>
<h2>Description</h2>
<b>This PowerShell script parses Windows Event Log data for failed RDP attacks and uses a third-party API to retrieve geographic information about the attackers' locations.
</b>
<br />
<br />
In this demonstration, I set up Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honeypot. We'll observe live RDP brute force attacks from around the world. Using a custom PowerShell script, I will look up the attackers' geolocation information and plot it on an Azure Sentinel map.
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
