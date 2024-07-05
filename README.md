# CVE-2024-30088-Windows-poc
该漏洞存在于 NtQueryInformationToken 函数中，特别是在处理AuthzBasepCopyoutInternalSecurityAttributes 函数时，该漏洞源于内核在操作对象时对锁定机制的不当管理，这一失误可能导致恶意实体意外提升权限。
![Windows 10 x64 - VMware Workstation 2024_7_5 23_55_20](https://github.com/Zombie-Kaiser/CVE-2024-30088-Windows-poc/assets/141570642/419420ad-6df9-49b2-a54c-8cbf7abf6ba8)
提权因为需要条件竞争，所以需要耐心等待一会.
