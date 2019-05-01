---
title: Åtgärda problem med e-post levereras till e-postfunktioner gemensamma mappar
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1956
ms.assetid: ''
ms.openlocfilehash: 45665f900014c52e6a920325b0a3b0f6f79fb72d
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 04/23/2019
ms.locfileid: "32401460"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a>Åtgärda problem med e-post levereras till e-postfunktioner gemensamma mappar

Om externa avsändare kan inte skicka meddelanden till din e-postfunktioner gemensamma mappar och avsändare visas fel: **kunde inte hittas (550 5.4.1)**, verifiera e-domänen för den gemensamma mappen konfigureras som en intern relay domän i stället för en auktoritär domän:

1. Öppna [Exchange administratörscenter (UK)](https://docs.microsoft.com/Exchange/exchange-admin-center).

2. Gå till **e-postflödet** \> **accepterade domäner**, markera accepterade domänen och klicka sedan på **Redigera**.

3. I egenskaperna för sidan som öppnas om typen domän är **auktoritära**, ändra värdet till **interna relay** och klicka på **Spara**.

Om externa avsändare får fel **du inte har behörighet (550 5.7.13)**, kör du följande kommando i [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) Se behörigheter för anonyma användare i den delade mappen:

`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Till exempel `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.

Tillåt externa användare att skicka e-post till mappen genom att lägga till CreateItems access rätt till användaren Anonym. Till exempel `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.