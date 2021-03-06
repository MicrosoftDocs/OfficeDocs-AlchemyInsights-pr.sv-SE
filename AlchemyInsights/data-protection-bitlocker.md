---
title: DataProtection-BitLocker
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1802"
- "9000220"
ms.openlocfilehash: 482c08b31e4d97ca5cc9ec6e35e309cb7536036d
ms.sourcegitcommit: 58ac31a58c956a4d74f66bd4151a2311dc361b78
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 01/07/2021
ms.locfileid: "49778211"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a>Aktivera BitLocker-kryptering med Intune

Intune Endpoint Protection policy kan användas för att konfigurera BitLocker-krypterings inställningar för Windows-enheter. Mer information finns i [Windows 10 (och senare) inställningar för att skydda enheter med Intune](https://docs.microsoft.com/intune/endpoint-protection-windows-10#windows-encryption).

Utöver policyn för Endpoint Protection finns det också en krypterings rapport som ger en mer detaljerad vy av krypterings statusen för enheter. Den här rapporten kan nås från MEM-portalen under **enheter > Monitor** och sedan under **konfiguration** Välj [krypterings rapport](https://endpoint.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/DevicesMonitorMenu/encryptionReport).

Om du upptäcker att det inte går att aktivera BitLocker som förväntat eller att den profil som används för att aktivera BitLocker inte är i fel tillstånd, bör du granska krypterings rapporten för att få en bättre förståelse för varför beteendet inträffar.

Information om hur du tolkar rapporten, inklusive olika krypterings status värden, finns i [övervaka enhets kryptering med Intune](https://docs.microsoft.com/mem/intune/protect/encryption-monitor).

Du bör vara medveten om att många nyare enheter som kör Windows 10 stöder automatisk BitLocker-kryptering, som aktive ras utan tillämpning av MDM-principer. Det här kan påverka tillämpningen av policy om icke-standardinställningar konfigureras. Se följande vanliga frågor för mer information.

Information om hur du felsöker problem med BitLocker finns i [Felsöka BitLocker-principer i Microsoft Intune](https://docs.microsoft.com/intune/protect/troubleshoot-bitlocker-policies).
 
 
**FAQ**

F: vilka versioner av Windows stöder enhets kryptering med Endpoint Protection policy?<br>
A: inställningarna i policyn för Endpoint Protection för Intune implementeras med hjälp av [BitLocker-CSP](https://docs.microsoft.com/windows/client-management/mdm/bitlocker-csp). Inte alla versioner av Windows har stöd för BitLocker CSP. <br><br>

F: Hur kan BitLocker aktive ras på enheter utan slutanvändarens medverkan?<br>
A: så länge nödvändiga förutsättningar är uppfyllda är det möjligt att aktivera BitLocker "tyst kryptering" genom Intune. Se informationen om enhets kraven och exempel princip inställningar för att aktivera tyst kryptering i följande dokument: [Aktivera BitLocker-kryptering tyst](https://docs.microsoft.com/mem/intune/protect/encrypt-devices#silently-enable-bitlocker-on-devices). <br><br>

F: om en enhet redan är krypterad med BitLocker med hjälp av OS-standardinställningarna för krypterings metod och chiffrering (XTS-AES-128) ska en princip med olika inställningar aktive ras automatiskt för åter kryptering av enheten med de nya inställningarna?<br>
S: nej. För att använda de nya krypterings inställningarna måste enheten först avkrypteras.<br><br>
**Obs!** För enheter som är registrerade med autopilot utlöses inte den automatiska krypteringen som skulle inträffa under OOBE förrän Intune-principen utvärderas, vilket gör att de principbaserade inställningarna kan användas i stället för OS-standardinställningarna.
 
F: om en enhet är krypterad som ett resultat av en Intune-princip kommer den att avkrypteras när den principen tas bort?<br>
A: det går inte att dekryptera de enheter som har kon figurer ATS genom att ta bort krypterings princip.
 
F: Varför visar policyn för Intune-efterlevnaden att min enhet inte har BitLocker aktiverat, trots att den är?<br>
A: inställningen "BitLocker är aktive rad" i Intune policyn använder DHA-klienten (Windows Device Health attestering). Denna klient mäter bara enhetens tillstånd vid start. Om en enhet inte har startats om sedan BitLocker-krypteringen har slutförts, rapporterar inte DHA klient tjänsten att aktive ras.
 
 