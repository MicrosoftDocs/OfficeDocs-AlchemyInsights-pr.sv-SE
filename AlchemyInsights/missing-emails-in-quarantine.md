---
title: Saknade e-postmeddelanden i karantän
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5668"
- "9002625"
ms.openlocfilehash: 61a926c363c62bc7acb5efefe42b834f33c78eb6
ms.sourcegitcommit: 8fdcd2acd31e8a4b9a8a0b91674f397d2f7889c1
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 06/03/2020
ms.locfileid: "44569561"
---
# <a name="missing-emails-in-quarantine"></a>Saknade mejl i karantän"

Administratörer kan [visa, släppa eller ta bort dessa meddelanden.](https://docs.microsoft.com/microsoft-365/security/office-365-security/manage-quarantined-messages-and-files?view=o365-worldwide)

Öppna Säkerhets- & Compliance Center genom att gå till [https://protection.office.com](https://protection.office.com/) . Öppna sidan Karantän direkt går du till [https://protection.office.com/quarantine](https://protection.office.com/quarantine) .  

Du kan söka efter följande värden:  

- **Meddelande-ID**: Meddelandets globalt unika identifierare. Om du markerar ett meddelande i listan visas värdet **Meddelande-ID** i det utfällbara fönstret **Information** som visas. Administratörer kan använda [meddelandespårning](https://docs.microsoft.com/microsoft-365/security/office-365-security/message-trace-scc?view=o365-worldwide) för att söka efter meddelanden med motsvarande värden för meddelande-ID.
- **Avsändarens e-postadress**: En enskild avsändarens e-postadress.
- **Mottagarens e-postadress**: En enskild mottagares e-postadress.
- **Ämne**: Använd meddelandets hela ämne. Sökningen är inte skiftlägeskänslig.

När du har angett sökvillkoren klickar du på ![ Uppdatera knappen ](https://docs.microsoft.com/microsoft-365/media/scc-quarantine-refresh.png?view=o365-worldwide) **Uppdatera** för att filtrera resultaten.  

De cmdlets du använder för att visa och hantera meddelanden och filer i karantän är:
- [Ta bort karantänMessage](https://docs.microsoft.com/powershell/module/exchange/delete-quarantinemessage)
- [Exportera karantänMessage](https://docs.microsoft.com/powershell/module/exchange/export-quarantinemessage)
- [Hämta karantänMessage](https://docs.microsoft.com/powershell/module/exchange/get-quarantinemessage)
- [Preview-QuarantineMessage](https://docs.microsoft.com/powershell/module/exchange/preview-quarantinemessage): Observera att den här cmdleten endast är för meddelanden, inte skadliga programfiler från ATP för SharePoint Online, OneDrive för företag eller Teams.
- [Release-KarantänMessage](https://docs.microsoft.com/powershell/module/exchange/release-quarantinemessage)