---
title: Åtgärda klientprincip (åsidosättning av åtgärder)
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
ms.openlocfilehash: bc7ad8acd86c9d5b2f99ffdc6fe8a8b53e1fcb8b
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 03/11/2021
ms.locfileid: "50748987"
---
# <a name="fix-tenant-policy-action-override"></a>Åtgärda klientprincip (åsidosättning av åtgärder)

En policy för skräppostskydd i klientorganisationen påverkade det här meddelandet. Så här granskar du principen:

1. Gå till [Säkerhets- och & Office 365](https://go.microsoft.com/fwlink/p/?linkid=2077143)och gå sedan **till** Policy för hothantering mot  >    >  [skräppost.](https://go.microsoft.com/fwlink/?linkid=2101518)
2. Kontrollera om **principkällan anger** följande:  **Add-Xheader/ModifySubject/Redirect/Delete/No action/ BCC message**

    I så fall kontrollerar **du inställningarna** för den princip som påverkade meddelandet på fliken Anpassad. Det är möjligt att standardinställningarna **som tillämpats** på alla Exchange Online Protection-kunder påverkade meddelandet.

Mer information om hur du konfigurerar principer för skräppostfilter finns [i Konfigurera principer för skräppostfilter.](https://go.microsoft.com/fwlink/?linkid=2101431)
