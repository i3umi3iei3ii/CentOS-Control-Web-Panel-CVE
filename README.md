## CentOS Control Web Panel (version 0.9.8.836 - 0.9.8.847)
On June 29, 2019 our team started to find vulnerability on CentOS Control Web Panel (CWP) version 0.9.8.836, and we found some critical vulnerabilites. Some of the vulnerabilities we found can be chained to compromise the server from anonymous user to be root user. After our team reported to CWP, they responsed us quickly.

Finally, all of vulnerabilities are mentioned here have been fixed on CWP version 0.9.8.848

<br>

<i>"
This repository is purely intended for educational and research purposes only. We do NOT want anyone to use any information from this repository to attack or do illegal  thing (refer to the laws in your country). So that, any actions and or activities related to the materials from this repository is solely your responsibility. If you don’t agree, you are not allowed to access this repository, leave this repository immediately "
</i>

<br>

## Vulnerabilities List

[CVE-2019-13359](https://github.com/i3umi3iei3ii/CentOS-Control-Web-Panel-CVE/blob/master/CVE-2019-13359.md) - Root Privilege Escalation

[CVE-2019-13360](https://github.com/i3umi3iei3ii/CentOS-Control-Web-Panel-CVE/blob/master/CVE-2019-13360.md) - User panel bypass Login #1

[CVE-2019-13605](https://github.com/i3umi3iei3ii/CentOS-Control-Web-Panel-CVE/blob/master/CVE-2019-13605.md) - User panel bypass Login #2

[CVE-2019-13383](https://github.com/i3umi3iei3ii/CentOS-Control-Web-Panel-CVE/blob/master/CVE-2019-13383.md) - User Enumeration via HTTP response message

[CVE-2019-13385](https://github.com/i3umi3iei3ii/CentOS-Control-Web-Panel-CVE/blob/master/CVE-2019-13385.md) - Active User Enumeration via login.log

[CVE-2019-13386](https://github.com/i3umi3iei3ii/CentOS-Control-Web-Panel-CVE/blob/master/CVE-2019-13386.md) - Command Execution

[CVE-2019-13387](https://github.com/i3umi3iei3ii/CentOS-Control-Web-Panel-CVE/blob/master/CVE-2019-13387.md) - Reflected Cross Site Scripting

CVE-2019-XXXXX Coming soon...

<br>

<i>The software is seperated to be 2 parts, root panel and user panel. If you try to install the old version by changing software version in the installation script, you will get install previous version of root panel but the user panel is only available for the lastest version (cannot specific version to download)</i>

<br>

## Discovered by
```
Pongtorn Angsuchotmetee
Nissana Sirijirakal
Narin Boonwasanarak
```
