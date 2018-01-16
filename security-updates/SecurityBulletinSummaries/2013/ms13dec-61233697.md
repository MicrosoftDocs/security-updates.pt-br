---
TOCTitle: 'MS13-DEC'
Title: Microsoft   for December 2013
ms:assetid: 'ms13-dec'
ms:contentKeyID: 61233697
ms:mtpsurl: 'https://technet.microsoft.com/pt-BR/library/ms13-dec(v=Security.10)'
---

Microsoft   for December 2013
=====================================================

Published: December 10, 2013

**Version:** 1.0

This bulletin summary lists security bulletins released for December 2013.

With the release of the security bulletins for December 2013, this bulletin summary replaces the bulletin advance notification originally issued December 5, 2013. For more information about the bulletin advance notification service, see [Microsoft Security Bulletin Advance Notification](http://go.microsoft.com/fwlink/?linkid=217213).

For information about how to receive automatic notifications whenever Microsoft security bulletins are issued, visit [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft is hosting a webcast to address customer questions on these bulletins on December 11, 2013, at 11:00 AM Pacific Time (US & Canada). [Register now for the December Security Bulletin Webcast](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557386&culture=en-us).

Microsoft also provides information to help customers prioritize monthly security updates with any non-security updates that are being released on the same day as the monthly security updates. Please see the section, **Other Information**.

Executive Summaries
-------------------

 
The following table summarizes the security bulletins for this month in order of severity.

For details on affected software, see the next section, **Affected Software**.

 
<p></p>

<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletin ID</strong></td>
<td style="border:1px solid black;"><strong>Bulletin Title and Executive Summary</strong></td>
<td style="border:1px solid black;"><strong>Maximum Severity Rating and Vulnerability Impact</strong></td>
<td style="border:1px solid black;"><strong>Restart Requirement</strong></td>
<td style="border:1px solid black;"><strong>Affected Software</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344108">MS13-096</a></td>
<td style="border:1px solid black;"><strong>Vulnerability in Microsoft Graphics Component Could allow Remote Code Execution (2908005)</strong><br />
<br />
This security update resolves a publicly disclosed vulnerability in Microsoft Windows, Microsoft Office, and Microsoft Lync. The vulnerability could allow remote code execution if a user views content that contains specially crafted TIFF files.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Critical</a> <br />
Remote Code Execution</td>
<td style="border:1px solid black;">May require restart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office,<br />
Microsoft Lync</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;"><strong>Cumulative Security Update for Internet Explorer (2898785)</strong><br />
<br />
This security update resolves seven privately reported vulnerabilities in Internet Explorer. The most severe vulnerabilities could allow remote code execution if a user views a specially crafted webpage using Internet Explorer. An attacker who successfully exploited the most severe of these vulnerabilities could gain the same user rights as the current user. Users whose accounts are configured to have fewer user rights on the system could be less impacted than users who operate with administrative user rights.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Critical</a> <br />
Remote Code Execution</td>
<td style="border:1px solid black;">Requires restart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325389">MS13-098</a></td>
<td style="border:1px solid black;"><strong>Vulnerability in Windows Could Allow Remote Code Execution (2893294)</strong><br />
<br />
This security update resolves a privately reported vulnerability in Microsoft Windows. The vulnerability could allow remote code execution if a user or application runs or installs a specially crafted, signed portable executable (PE) file on an affected system.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Critical</a> <br />
Remote Code Execution</td>
<td style="border:1px solid black;">Requires restart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344112">MS13-099</a></td>
<td style="border:1px solid black;"><strong>Vulnerability in Microsoft Scripting Runtime Object Library Could Allow Remote Code Execution (2909158)</strong><br />
<br />
This security update resolves a privately reported vulnerability in Microsoft Windows. The vulnerability could allow remote code execution if an attacker convinces a user to visit a specially crafted website or a website that hosts specially crafted content. An attacker who successfully exploited this vulnerability could gain the same user rights as the local user. Users whose accounts are configured to have fewer user rights on the system could be less impacted than users who operate with administrative user rights.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Critical</a> <br />
Remote Code Execution</td>
<td style="border:1px solid black;">May require restart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilities in Microsoft Exchange Server Could Allow Remote Code Execution (2915705)</strong><br />
<br />
This security update resolves three publicly disclosed vulnerabilities and one privately reported vulnerability in Microsoft Exchange Server. The most severe of these vulnerabilities exist in the WebReady Document Viewing and Data Loss Prevention features of Microsoft Exchange Server. These vulnerabilities could allow remote code execution in the security context of the LocalService account if an attacker sends an email message containing a specially crafted file to a user on an affected Exchange server. The LocalService account has minimum privileges on the local system and presents anonymous credentials on the network.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Critical</a> <br />
Remote Code Execution</td>
<td style="border:1px solid black;">Does not require restart</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329771">MS13-100</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilities in Microsoft SharePoint Server Could Allow Remote Code Execution (2904244)</strong><br />
<br />
This security update resolves multiple privately reported vulnerabilities in Microsoft Office server software. These vulnerabilities could allow remote code execution if an authenticated attacker sends specially crafted page content to a SharePoint server. An attacker who successfully exploited these vulnerabilities could run arbitrary code in the security context of the W3WP service account on the target SharePoint site.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Important</a> <br />
Remote Code Execution</td>
<td style="border:1px solid black;">May require restart</td>
<td style="border:1px solid black;">Microsoft SharePoint</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;"><strong>Vulnerabilities in Windows Kernel-Mode Drivers Could Allow Elevation of Privilege (2880430)</strong><br />
<br />
This security update resolves five privately reported vulnerabilities in Microsoft Windows. The more severe of these vulnerabilities could allow elevation of privilege if an attacker logs on to a system and runs a specially crafted application. An attacker must have valid logon credentials and be able to log on locally to exploit this vulnerability.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Important</a> <br />
Elevation of Privilege</td>
<td style="border:1px solid black;">Requires restart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344110">MS13-102</a></td>
<td style="border:1px solid black;"><strong>Vulnerability in LRPC Client Could Allow Elevation of Privilege (2898715)</strong><br />
<br />
This security update resolves a privately reported vulnerability in Microsoft Windows. The vulnerability could allow elevation of privilege if an attacker spoofs an LRPC server and sends a specially crafted LPC port message to any LRPC client. An attacker who successfully exploited the vulnerability could then install programs; view, change, or delete data; or create new accounts with full administrator rights. An attacker must have valid logon credentials and be able to log on locally to exploit this vulnerability.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Important</a> <br />
Elevation of Privilege</td>
<td style="border:1px solid black;">Requires restart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329969">MS13-103</a></td>
<td style="border:1px solid black;"><strong>Vulnerability in ASP.NET SignalR Could Allow Elevation of Privilege (2905244)</strong><br />
<br />
This security update resolves a privately reported vulnerability in ASP.NET SignalR. The vulnerability could allow elevation of privilege if an attacker reflects specially crafted JavaScript back to the browser of a targeted user.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Important</a> <br />
Elevation of Privilege</td>
<td style="border:1px solid black;">Does not require restart</td>
<td style="border:1px solid black;">Microsoft Developer Tools</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=330934">MS13-104</a></td>
<td style="border:1px solid black;"><strong>Vulnerability in Microsoft Office Could Allow Information Disclosure (2909976)</strong><br />
<br />
This security update resolves one privately reported vulnerability in Microsoft Office that could allow information disclosure if a user attempts to open an Office file hosted on a malicious website. An attacker who successfully exploited this vulnerability could ascertain access tokens used to authenticate the current user on a targeted SharePoint or other Microsoft Office server site.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Important</a> <br />
Information Disclosure</td>
<td style="border:1px solid black;">May require restart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329967">MS13-106</a></td>
<td style="border:1px solid black;"><strong>Vulnerability in a Microsoft Office Shared Component Could Allow Security Feature Bypass<br />
(2905238)</strong><br />
<br />
This security update resolves one publicly disclosed vulnerability in a Microsoft Office shared component that is currently being exploited. The vulnerability could allow security feature bypass if a user views a specially crafted webpage in a web browser capable of instantiating COM components, such as Internet Explorer. In a web-browsing attack scenario, an attacker who successfully exploited this vulnerability could bypass the Address Space Layout Randomization (ASLR) security feature, which helps protect users from a broad class of vulnerabilities. The security feature bypass by itself does not allow arbitrary code execution. However, an attacker could use this ASLR bypass vulnerability in conjunction with another vulnerability, such as a remote code execution vulnerability that could take advantage of the ASLR bypass to run arbitrary code.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Important</a> <br />
Security Feature Bypass</td>
<td style="border:1px solid black;">May require restart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>

<p></p>

  
 
  
Exploitability Index  
--------------------
  
 
The following table provides an exploitability assessment of each of the vulnerabilities addressed this month. The vulnerabilities are listed in order of bulletin ID then CVE ID. Only vulnerabilities that have a severity rating of Critical or Important in the bulletins are included.
  
**How do I use this table?**  
  
Use this table to learn about the likelihood of code execution and denial of service exploits within 30 days of security bulletin release, for each of the security updates that you may need to install. Review each of the assessments below, in accordance with your specific configuration, to prioritize your deployment of this month's updates. For more information about what these ratings mean, and how they are determined, please see [Microsoft Exploitability Index](http://technet.microsoft.com/security/cc998259).
  
In the columns below, "Latest Software Release" refers to the subject software, and "Older Software Releases" refers to all older, supported releases of the subject software, as listed in the "Affected Software" and "Non-Affected Software" tables in the bulletin.
  
<p></p>

<table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletin ID</strong></td>
<td style="border:1px solid black;"><strong>Vulnerability Title</strong></td>
<td style="border:1px solid black;"><strong>CVE ID</strong></td>
<td style="border:1px solid black;"><strong>Exploitability Assessment for Latest Software Release</strong></td>
<td style="border:1px solid black;"><strong>Exploitability Assessment for Older Software Release</strong></td>
<td style="border:1px solid black;"><strong>Denial of Service Exploitability Assessment</strong></td>
<td style="border:1px solid black;"><strong>Key Notes</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344108">MS13-096</a></td>
<td style="border:1px solid black;">Microsoft Graphics Component Memory Corruption Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3906">CVE-2013-3906</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">This vulnerability has been publicly disclosed.<br />
<br />
Microsoft is aware of targeted attacks that attempt to exploit this vulnerability in Microsoft Office products.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer Elevation of Privilege Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5045">CVE-2013-5045</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer Elevation of Privilege Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5046">CVE-2013-5046</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer Memory Corruption Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5047">CVE-2013-5047</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer Memory Corruption Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5048">CVE-2013-5048</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer Memory Corruption Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5049">CVE-2013-5049</a></td>
<td style="border:1px solid black;">Not affected</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer Memory Corruption Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5051">CVE-2013-5051</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Exploit code unlikely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - Exploit code would be difficult to build</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer Memory Corruption Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5052">CVE-2013-5052</a></td>
<td style="border:1px solid black;">Not affected</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325389">MS13-098</a></td>
<td style="border:1px solid black;">WinVerifyTrust Signature Validation Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3900">CVE-2013-3900</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">Microsoft is aware of targeted attacks that attempt to exploit this vulnerability.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344112">MS13-099</a></td>
<td style="border:1px solid black;">Use-After-Free Vulnerability in Microsoft Scripting Runtime Object Library</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5056">CVE-2013-5056</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329771">MS13-100</a></td>
<td style="border:1px solid black;">SharePoint Page Content Vulnerabilities</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5059">CVE-2013-5059</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Win32k Memory Corruption Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3899">CVE-2013-3899</a></td>
<td style="border:1px solid black;">Not affected</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - Exploit code would be difficult to build</td>
<td style="border:1px solid black;">Permanent</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Win32k Use After Free Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3902">CVE-2013-3902</a></td>
<td style="border:1px solid black;">Not affected</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Permanent</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">TrueType Font Parsing Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3903">CVE-2013-3903</a></td>
<td style="border:1px solid black;">Not affected</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Exploit code unlikely</td>
<td style="border:1px solid black;">Permanent</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Port-Class Driver Double Fetch Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3907">CVE-2013-3907</a></td>
<td style="border:1px solid black;">Not affected</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - Exploit code would be difficult to build</td>
<td style="border:1px solid black;">Permanent</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Win32k Integer Overflow Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5058">CVE-2013-5058</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Exploit code unlikely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Exploit code unlikely</td>
<td style="border:1px solid black;">Permanent</td>
<td style="border:1px solid black;">This is a denial of service vulnerability.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=344110">MS13-102</a></td>
<td style="border:1px solid black;">LRPC Client Buffer Overrun Vulnerability </td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3878">CVE-2013-3878</a></td>
<td style="border:1px solid black;">Not affected</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Permanent</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329969">MS13-103</a></td>
<td style="border:1px solid black;">SignalR XSS Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5042">CVE-2013-5042</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=330934">MS13-104</a></td>
<td style="border:1px solid black;">Token Hijacking Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5054">CVE-2013-5054</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Exploit code unlikely</td>
<td style="border:1px solid black;">Not affected</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">This is an information disclosure vulnerability.<br />
<br />
Microsoft is aware of limited, targeted attacks that attempt to exploit this vulnerability.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;">MAC Disabled Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1330">CVE-2013-1330</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">1</a> - Exploit code likely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">This vulnerability has been publicly disclosed.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;">Oracle Outside In Contains Multiple Exploitable Vulnerabilities</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5763">CVE-2013-5763</a><br />
<br />
and<br />
<br />
<a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5791">CVE-2013-5791</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - Exploit code would be difficult to build</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">2</a> - Exploit code would be difficult to build</td>
<td style="border:1px solid black;">Permanent</td>
<td style="border:1px solid black;">These vulnerabilities have been publicly disclosed.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;">OWA XSS Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5072">CVE-2013-5072</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Exploit code unlikely</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/cc998259">3</a> - Exploit code unlikely</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">(None)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=329967">MS13-106</a></td>
<td style="border:1px solid black;">HXDS ASLR Vulnerability</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5057">CVE-2013-5057</a></td>
<td style="border:1px solid black;">Not affected</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">Not applicable</td>
<td style="border:1px solid black;">This is a security feature bypass vulnerability.<br />
<br />
This vulnerability has been publicly disclosed.<br />
<br />
Microsoft is aware of limited, targeted attacks that attempt to exploit this vulnerability.</td>
</tr>
</tbody>
</table>

<p></p>

 

 

Affected Software
-----------------

 
The following tables list the bulletins in order of major software category and severity.

**How do I use these tables?**  

Use these tables to learn about the security updates that you may need to install. You should review each software program or component listed to see whether any security updates pertain to your installation. If a software program or component is listed, then the severity rating of the software update is also listed.

**Note** You may have to install several security updates for a single vulnerability. Review the whole column for each bulletin identifier that is listed to verify the updates that you have to install, based on the programs or components that you have installed on your system.

### Windows Operating System and Components

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(Critical)  
Internet Explorer 7   
(2898785)  
(Critical)  
Internet Explorer 8   
(2898785)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.7  
(2892075)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2893984)  
(Important)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2898715)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(Critical)  
Internet Explorer 7   
(2898785)  
(Critical)  
Internet Explorer 8   
(2898785)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.6  
(2892076)  
(Critical)  
Windows Script 5.7   
(2892075)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2893984)  
(Important)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2898715)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(Moderate)  
Internet Explorer 7  
(2898785)  
(Important)  
Internet Explorer 8  
(2898785)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
(Critical)  
Windows Script 5.7   
(2892075)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2893984)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2898715)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(Moderate)  
Internet Explorer 7  
(2898785)  
(Important)  
Internet Explorer 8  
(2898785)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
(Critical)  
Windows Script 5.7   
(2892075)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2893984)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2898715)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(Moderate)  
Internet Explorer 7  
(2898785)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
(Critical)  
Windows Script 5.7   
(2892075)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2893984)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2898715)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2901674)  
(Critical)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(Critical)  
Internet Explorer 8  
(2898785)  
(Critical)  
Internet Explorer 9   
(2898785)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2893984)  
(Moderate)  
Windows Vista Service Pack 2  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2901674)  
(Critical)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(Critical)  
Internet Explorer 8  
(2898785)  
(Critical)  
Internet Explorer 9   
(2898785)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2893984)  
(Moderate)  
Windows Vista x64 Edition Service Pack 2  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2901674)  
(Critical)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(Important)  
Internet Explorer 8  
(2898785)  
(Important)  
Internet Explorer 9   
(2898785)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2893984)  
(Moderate)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2901674)  
(Critical)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(Important)  
Internet Explorer 8  
(2898785)  
(Important)  
Internet Explorer 9   
(2898785)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2893984)  
(Moderate)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2901674)  
(Critical)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2893984)  
(Moderate)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(Critical)  
Internet Explorer 9   
(2898785)  
(Critical)  
Internet Explorer 10   
(2898785)  
(Critical)  
Internet Explorer 11   
(2898785)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2893984)  
(Important)  
Windows 7 for 32-bit Systems Service Pack 1  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(Critical)  
Internet Explorer 9   
(2898785)  
(Critical)  
Internet Explorer 10   
(2898785)  
(Critical)  
Internet Explorer 11   
(2898785)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2893984)  
(Important)  
Windows 7 for x64-based Systems Service Pack 1  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(Important)  
Internet Explorer 9   
(2898785)  
(Important)  
Internet Explorer 10   
(2898785)  
(Important)  
Internet Explorer 11   
(2898785)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2893984)  
(Important)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2893984)  
(Important)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 and Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2893984)  
(Moderate)  
Windows 8 for 32-bit Systems  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2893984)  
(Moderate)  
Windows 8 for x64-based Systems  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2893984)  
(Moderate)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2893984)  
(Moderate)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 and Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2893984)  
(Moderate)  
Windows Server 2012  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(Important)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2893984)  
(Moderate)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT and Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows RT  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows RT  
(2893984)  
(Moderate)  
Windows RT  
(2887069)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2893984)  
(Moderate)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core installation option**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](http://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](http://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](http://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](http://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](http://go.microsoft.com/fwlink/?linkid=344110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core installation)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core installation)  
(2901674)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core installation)  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core installation)  
(2893984)  
(Moderate)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core installation)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core installation)  
(2901674)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core installation)  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core installation)  
(2893984)  
(Moderate)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core installation)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core installation)  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core installation)  
(2893984)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core installation)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core installation)  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core installation)  
(2893984)  
(Moderate)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core installation)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core installation)  
(2893294)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(Critical)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core installation)  
(2893984)  
(Moderate)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
</table>

<p></p>

 
**Note for MS13-096**

This bulletin spans more than one software category. See the other tables in this section for additional affected software.

 

### Microsoft Office Suites and Software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](http://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](http://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3 (2850047)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](http://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](http://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2817641)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2850022)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](http://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](http://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32-bit editions)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32-bit editions)  
(2817670)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32-bit editions)  
(2850016)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-bit editions)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-bit editions)  
(2817670)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-bit editions)  
(2850016)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64-bit editions)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64-bit editions)  
(2817670)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64-bit editions)  
(2850016)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-bit editions)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-bit editions)  
(2817670)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-bit editions)  
(2850016)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](http://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](http://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (32-bit editions)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (32-bit editions)  
(2850064)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (64-bit editions)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (64-bit editions)  
(2850064)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2850064)  
(Important)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Other Office Software**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](http://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](http://go.microsoft.com/fwlink/?linkid=329967)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3  
(2817641)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2850047)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2817641)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer Service Pack 1  
(2817670)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer Service Pack 2  
(2817670)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
</table>

<p></p>

 
**Note for MS13-096**

This bulletin spans more than one software category. See the other tables in this section for additional affected software.

 

### Microsoft Server Software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-105**](http://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
**None**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Not applicable

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 (coreserverloc)  
(2850058)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-105**](http://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(2903911)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-105**](http://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2  
(2903903)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(2905616)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-105**](http://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Critical**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**None**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Cumulative Update 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Cumulative Update 2  
(2880833)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Cumulative Update 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Cumulative Update 3  
(2880833)  
(Critical)

</td>
<td style="border:1px solid black;">
Not applicable

</td>
</tr>
</table>

<p></p>

 
**Note for MS13-100**

This bulletin spans more than one software category. See the other tables in this section for additional affected software.

 

### Microsoft Office Services and Web Apps

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2553298)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2553298)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2837629)  
(Important)  
Excel Services  
(2837631)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-100**](http://go.microsoft.com/fwlink/?linkid=329771)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2910228)  
(Important)

</td>
</tr>
</table>

<p></p>

 
**Note for MS13-100**

This bulletin spans more than one software category. See the other tables in this section for additional affected software.

 

### Microsoft Communication Platforms and Software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32-bit)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32-bit)  
(2899397)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-bit)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-bit)  
(2899397)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(user level install)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(user level install)  
(2899393)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(admin level install)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(admin level install)  
(2899395)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-096**](http://go.microsoft.com/fwlink/?linkid=344108)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32-bit)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32-bit)  
(2850057)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32-bit)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32-bit)  
(2850057)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64-bit)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64-bit)  
(2850057)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64-bit)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013  
(64-bit)  
(2850057)  
(Important)

</td>
</tr>
</table>

<p></p>

 
**Note for MS13-096**

This bulletin spans more than one software category. See the other tables in this section for additional affected software.

### Microsoft Developer Tools and Software

 
<p></p>

<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**ASP.NET**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-103**](http://go.microsoft.com/fwlink/?linkid=329969)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET SignalR

</td>
<td style="border:1px solid black;">
ASP.NET SignalR 1.1.x   
(2903919)  
(Important)  
ASP.NET SignalR 2.0.x   
(2903919)  
(Important)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Visual Studio Team Foundation Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bulletin Identifier**

</td>
<td style="border:1px solid black;">
[**MS13-103**](http://go.microsoft.com/fwlink/?linkid=329969)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Aggregate Severity Rating**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2013   
(2903566)  
(Important)

</td>
</tr>
</table>

<p></p>

 
 

Detection and Deployment Tools and Guidance
-------------------------------------------

 
Several resources are available to help administrators deploy security updates.

-   Microsoft Baseline Security Analyzer (MBSA) lets administrators scan local and remote systems for missing security updates and common security misconfigurations.
-   Windows Server Update Services (WSUS), Systems Management Server (SMS), and System Center Configuration Manager help administrators distribute security updates.
-   The Update Compatibility Evaluator components included with Application Compatibility Toolkit aid in streamlining the testing and validation of Windows updates against installed applications.

For information about these and other tools that are available, see [Security Tools for IT Pros](http://technet.microsoft.com/security/cc297183). 

Acknowledgments
---------------

 
Microsoft [thanks](http://go.microsoft.com/fwlink/?linkid=21127) the following for working with us to help protect customers:

**MS13-096**

-   Haifei Li of McAfee Labs IPS Team for reporting the Microsoft Graphics Component Memory Corruption Vulnerability (CVE-2013-3906)

**MS13-097**

-   James Forshaw of Context Information Security for reporting the Internet Explorer Elevation of Privilege Vulnerability (CVE-2013-5045)
-   James Forshaw of Context Information Security for reporting the Internet Explorer Elevation of Privilege Vulnerability (CVE-2013-5046)
-   Abdul-Aziz Hariri of [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/) for reporting the Internet Explorer Memory Corruption Vulnerability (CVE-2013-5047)
-   An anonymous researcher, working with [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/), for reporting the Internet Explorer Memory Corruption Vulnerability (CVE-2013-5048)
-   Jose Antonio Vazquez Gonzalez, working with [HP's](http://www.hpenterprisesecurity.com/products)[Zero Day Initiative](http://www.zerodayinitiative.com/), for reporting the Internet Explorer Memory Corruption Vulnerability (CVE-2013-5049)
-   Atte Kettunen of [OUSPG](https://www.ee.oulu.fi/research/ouspg/) for reporting the Internet Explorer Memory Corruption Vulnerability (CVE-2013-5051)
-   Bo Qu of [Palo Alto Networks](http://www.paloaltonetworks.com/) for reporting the Internet Explorer Memory Corruption Vulnerability (CVE-2013-5052)
-   Alex Inführ for working with us on defense-in-depth changes to the Internet Explorer XSS Filter included in this bulletin

**MS13-098**

-   Kingsoft Internet Security Center @ [Kingsoft Internet Security Software Co. Ltd](http://www.ijinshan.com/) for reporting the WinVerifyTrust Signature Validation Vulnerability (CVE-2013-3900)

**MS13-101**

-   Renguang Yuan of [Qihoo](http://www.360.cn/) for reporting the Win32k Memory Corruption Vulnerability (CVE-2013-3899)
-   An anonymous researcher, working with [VeriSign iDefense Labs](http://labs.idefense.com/) for reporting the Win32k Memory Corruption Vulnerability (CVE-2013-3899)
-   Ling Chuan Lee of [F13 Laboratory](http://www.f13-labs.net/) for reporting the TrueType Font Parsing Vulnerability (CVE-2013-3903)
-   Nicolas Economou of [Core Security Technologies](http://www.coresecurity.com/) for reporting the Win32k Integer Overflow Vulnerability (CVE-2013-5058)

**MS13-102**

-   Renguang Yuan of [Qihoo](http://www.360.cn/) for reporting the LRPC Client Buffer Overrun Vulnerability (CVE-2013-3878)

**MS13-104**

-   Noam Liran of [Adallom](http://www.adallom.com/) for reporting the Token Hijacking Vulnerability (CVE-2013-5054)

**MS13-105**

-   [Minded Security](https://www.mindedsecurity.com/), on behalf of [Criteo](http://www.criteo.com/), for reporting the OWA XSS Vulnerability (CVE-2013-5072)

Other Information
-----------------

 
### Microsoft Windows Malicious Software Removal Tool

For the bulletin release that occurs on the second Tuesday of each month, Microsoft has released an updated version of the Microsoft Windows Malicious Software Removal Tool on Windows Update, Microsoft Update, Windows Server Update Services, and the Download Center. No updated version of the Microsoft Windows Malicious Software Removal Tool is available for out-of-band security bulletin releases.

### Non-Security Updates on MU, WU, and WSUS

For information about non-security releases on Windows Update and Microsoft Update, please see:

-   [Microsoft Knowledge Base Article 894199](https://support.microsoft.com/kb/894199): Description of Software Update Services and Windows Server Update Services changes in content. Includes all Windows content.
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/wsus/bb456965). Displays all new, revised, and rereleased updates for Microsoft products other than Microsoft Windows.

### Microsoft Active Protections Program (MAPP)

To improve security protections for customers, Microsoft provides vulnerability information to major security software providers in advance of each monthly security update release. Security software providers can then use this vulnerability information to provide updated protections to customers via their security software or devices, such as antivirus, network-based intrusion detection systems, or host-based intrusion prevention systems. To determine whether active protections are available from security software providers, please visit the active protections websites provided by program partners listed in [Microsoft Active Protections Program (MAPP) Partners](http://go.microsoft.com/fwlink/?linkid=215201).

### Security Strategies and Community

**Update Management Strategies**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) provides additional information about Microsoft’s best-practice recommendations for applying security updates.

**Obtaining Other Security Updates**

Updates for other security issues are available from the following locations:

-   Security updates are available from [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). You can find them most easily by doing a keyword search for "security update".
-   Updates for consumer platforms are available from [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
-   You can obtain the security updates offered this month on Windows Update, from Download Center on Security and Critical Releases ISO CD Image files. For more information, see [Microsoft Knowledge Base Article 913086](https://support.microsoft.com/kb/913086).

**IT Pro Security Community**

Learn to improve security and optimize your IT infrastructure, and participate with other IT Pros on security topics in [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164).

### Support

The affected software listed has been tested to determine which versions are affected. Other versions are past their support life cycle. To determine the support life cycle for your software version, visit [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742).

Security solutions for IT professionals: [TechNet Security Troubleshooting and Support](http://technet.microsoft.com/security/bb980617)

Help protect your computer that is running Windows from viruses and malware: [Virus Solution and Security Center](http://support.microsoft.com/contactus/cu_sc_virsec_master)

Local support according to your country: [International Support](http://support.microsoft.com/common/international.aspx)

### Disclaimer

The information provided in the Microsoft Knowledge Base is provided "as is" without warranty of any kind. Microsoft disclaims all warranties, either express or implied, including the warranties of merchantability and fitness for a particular purpose. In no event shall Microsoft Corporation or its suppliers be liable for any damages whatsoever including direct, indirect, incidental, consequential, loss of business profits or special damages, even if Microsoft Corporation or its suppliers have been advised of the possibility of such damages. Some states do not allow the exclusion or limitation of liability for consequential or incidental damages so the foregoing limitation may not apply.

### Revisions

-   V1.0 (December 10, 2013): Bulletin Summary published.

 

*Page generated 2014-05-09 17:27Z-07:00.*
