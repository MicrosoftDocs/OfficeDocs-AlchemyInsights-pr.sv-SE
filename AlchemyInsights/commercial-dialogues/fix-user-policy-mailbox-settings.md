---
title: Åtgärda inställningar för användarprincip/postlåda
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: ca998c453fcb0905b122436f0eea384a9b8a9992
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 03/11/2021
ms.locfileid: "50750564"
---
# <a name="fix-user-policymailbox-settings"></a>Åtgärda inställningar för användarprincip/postlåda

Skräppostinställningarna på postlådan påverkade det här meddelandet. Gör så här om du vill granska inställningarna:

1. Starta Exchange Management Shell. Mer information finns i [Öppna Exchange Management Shell.](https://go.microsoft.com/fwlink/?linkid=2101432)
2. Kör det här kommandot (med användarens  **e-postadress): get-mailboxjunkmailconfiguration -identity "user@domain.com"**
3. Kontrollera om avsändarens e-postadress är en del av **TrustedSendersAndDomains** eller **BlockedSendersAndDomains.** Om e-postadressen finns i en av listorna kan du behöva ta bort den. Mer information finns i [Set-MailboxJunkEmailConfiguration](https://go.microsoft.com/fwlink/?linkid=2101047).
