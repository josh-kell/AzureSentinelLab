<h1>Failed RDP to IP Geolocation Information in Azure Sentinel</h1>


<h2>Description</h2>
<b>The repository contains a Powershell script that extracted Windows Event Log data related to unsuccessful RDP attacks and utilized a third-party API to gather geographical details concerning the attackers location.
</b>
<br />
<br />
The purpose of the script is to integrate Azure Sentinel (SIEM) with a virtual machine functioning as a honeypot. By doing so, we can actively monitor real-time RDP brute force attacks originating from various locations worldwide. To accomplish this, a customized PowerShell script will be employed to retrieve geolocation data of the attackers and visualize it on an Azure Sentinel Map.
<br />
<br />

![IPGeolocationsite](https://github.com/josh-kell/images/assets/139269185/23c0226e-8542-41b6-974c-7274b607e1d4)

<h2>Languages Used</h2>

- <b>PowerShell:</b> Used to extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Powershell Script Used and Example of Custom Log Data</h2>

![AzureProject7 2](https://github.com/josh-kell/images/assets/139269185/333e9ece-9e9e-4f60-a83c-43089d158fb4)

![AzureProject7 1](https://github.com/josh-kell/images/assets/139269185/1f39b4a8-b2d7-4f39-a574-342a76bea74b)

<h2>World Map of Incoming Attacks after 6 Hours</h2>

![FailedRDPWorldMap_Final_Country (1)](https://github.com/josh-kell/images/assets/139269185/e5fbf52c-a897-46f2-b990-b0636c4715d5)



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
