---
title: SharePoint Designer-anslutningsproblem
ms.author: efrene
author: efrene
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 1d3f6ad3128292a9dbcc46cc7da23af59a63fbb4
ms.sourcegitcommit: a285c609319ade038461e090e14a701830031825
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 07/24/2019
ms.locfileid: "35840569"
---
# <a name="sharepoint-designer-connection-issues"></a>SharePoint Designer-anslutningsproblem 

Om SharePoint Designer har uppstått anslutningsproblem med till SharePoint-webbplatser, försök följande vanliga lösningar.

Steg 1: Kontrollera att SharePoint Designer 2013 uppdateras med [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) och [2 augusti 2016 uppdatering för SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).



Steg 2: Rensa lokala cache-filer:

1. Stäng SharePoint Designer 2013.

2. Ta bort alla filer i följande mappar på den lokala datorn.

    - %APPDATA%\Microsoft\Web server Extensions\Cache
    - %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache
    - %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

3. Öppna SharePoint Designer 2013 och ange konto igen för att se om det fungerar.

Steg 3: [Aktivera moderna autentisering för Office 2013 på Windows-enheter](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).

Steg 4: Administratörer måste **Tillåta anpassat skript** i SharePoint Admin Center-inställningar ska tillåta anslutning för SharePoint Designer. Se [Tillåt eller förhindra att skriptet](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) för mer information.


