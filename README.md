# SentinelLab
This lab idea was created by Josh Madakor.

<h2>Description</h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
</b>
<br />
<br />
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />
<br />
<h2>Languages Used</h2>
- <b>Microsoft Azure:</b> Sentinel, Log Analytics Workspace, and Virtual Machine were used to log the failed login attempts and map the data to a global map <br />
- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer <br />

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API
