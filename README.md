# MS12-020
CVE -2012-0152

Windows Remote Desktop Protocol Bugs Let Remote Users Deny Service and Execute Arbitrary Code 
SecurityTracker Alert ID:  1026790
SecurityTracker URL:  http://securitytracker.com/id/1026790
CVE Reference:   CVE-2012-0002, CVE-2012-0152   (Links to External Site)
Updated:  Jun 13 2012
Original Entry Date:  Mar 13 2012 
Impact:   Denial of service via network, Execution of arbitrary code via network, User access via network
Fix Available:  Yes  Vendor Confirmed:  Yes  

Description:   Two vulnerabilities were reported in Windows Remote Desktop. A remote user can execute arbitrary code on the target system. A remote user can cause denial of service conditions.

The system does not properly access an object in memory that has been improperly initialized or has been deleted [CVE-2012-0002]. A remote user can send a series of specially crafted RDP protocol data to execute arbitrary code on the target system.

If Network Level Authentication is enabled, the remote user must first authenticate to Remote Desktop Services.

Luigi Auriemma (via TippingPoint's Zero Day Initiative) reported this vulnerability.

A remote user can send a series of specially crafted RDP protocol data to cause the RDP service to stop responding [CVE-2012-0152].
Impact:   A remote user can execute arbitrary code on the target system.

A remote user can cause the RDP service to stop responding.
Solution:   The vendor has issued the following fixes:

Windows XP Service Pack 3:

http://www.microsoft.com/downloads/details.aspx?familyid=18a1fe48-1318-4b93-afad-206950bb1ae5

Windows XP Professional x64 Edition Service Pack 2:

http://www.microsoft.com/downloads/details.aspx?familyid=eccf865d-399a-4862-b26f-f35580419875

Windows Server 2003 Service Pack 2:

http://www.microsoft.com/downloads/details.aspx?familyid=b69b4b9b-c0a1-4c1e-b081-8529eaf1536a

Windows Server 2003 x64 Edition Service Pack 2:

http://www.microsoft.com/downloads/details.aspx?familyid=8081e67f-288c-4714-bff8-e0ff9777692f

Windows Server 2003 with SP2 for Itanium-based Systems:

http://www.microsoft.com/downloads/details.aspx?familyid=521baa02-5d7a-4cba-8a1a-2af1b6e4cbe4

Windows Vista Service Pack 2:

http://www.microsoft.com/downloads/details.aspx?familyid=39abdf7b-ea9d-4b95-a28d-4140374d531d

Windows Vista x64 Edition Service Pack 2:

http://www.microsoft.com/downloads/details.aspx?familyid=e5970daf-4440-42fa-8efc-e6190c6a22aa

Windows Server 2008 for 32-bit Systems Service Pack 2:

http://www.microsoft.com/downloads/details.aspx?familyid=fef2c1d7-2004-43d7-aa49-673c6f374670

Windows Server 2008 for x64-based Systems Service Pack 2:

http://www.microsoft.com/downloads/details.aspx?familyid=4ffae13f-3432-4849-a2da-a76f96d7ceb3

Windows Server 2008 for Itanium-based Systems Service Pack 2:

http://www.microsoft.com/downloads/details.aspx?familyid=67581250-50fd-4f4c-a3cc-45ce2662b0c3

Windows 7 for 32-bit Systems and Windows 7 for 32-bit Systems Service Pack 1:

http://www.microsoft.com/downloads/details.aspx?familyid=16b0195c-84d3-4c08-8b98-ff2c80d144e1

Windows 7 for x64-based Systems and Windows 7 for x64-based Systems Service Pack 1:

http://www.microsoft.com/downloads/details.aspx?familyid=40b62d08-d2a2-4900-b01c-46fc761973d0

Windows Server 2008 R2 for x64-based Systems and Windows Server 2008 R2 for x64-based Systems Service Pack 1:

http://www.microsoft.com/downloads/details.aspx?familyid=7c1774cc-e00c-47f3-97a2-bc90de857793

Windows Server 2008 R2 for Itanium-based Systems and Windows Server 2008 R2 for Itanium-based Systems Service Pack 1:

http://www.microsoft.com/downloads/details.aspx?familyid=6a07f99c-8ab4-4e44-8d48-6ac787dd2b51

A restart is required.

[Editor's note: On June 12, 2012, Microsoft reissued MS12-020 to reoffer security update KB2667402 on all supported editions of Windows 7 and Windows Server 2008 R2. Customers using Windows 7 or Windows Server 2008 R2 should install the reofferred update, including those who have already successfully installed the original update.]

The Microsoft advisory is available at:

http://technet.microsoft.com/en-us/security/bulletin/ms12-020
Vendor URL:  technet.microsoft.com/en-us/security/bulletin/ms12-020 (Links to External Site) 
Cause:   Access control error
Underlying OS:  Windows (2003), Windows (2008), Windows (7), Windows (Vista), Windows (XP)
Underlying OS Comments:  XP SP3, 2003 SP2, 2008 R2 SP1, Vista SP2, 7 SP1, 2008 SP2; and prior service packs
