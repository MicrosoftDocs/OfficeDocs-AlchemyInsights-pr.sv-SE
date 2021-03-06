---
title: 1490 – fel sökning – eDiscovery – fel
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1490"
- "3200003"
ms.assetid: ''
ms.openlocfilehash: ff28f96d64ec14980e9a47b630246b394faf4610
ms.sourcegitcommit: fbe6925797cab0b38172386f1b059dc122e452a4
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 09/25/2020
ms.locfileid: "48277844"
---
# <a name="troubleshoot-content-search-errors"></a>Felsöka problem med innehålls sökning

Har du problem med innehålls sökning eller får du fel när du exporterar Sök Resultat?

Får du till exempel följande när du kör sökningar?

- CS008-eller CS012-fel

- Upptaget/timeout-fel på servern

- Program fel uppstod

Eller när du söker efter eller exporterar resultat från ett stort antal post lådor (över 100 000-postlådor) får du bara exportera fel?

För de här fel typerna kan du försöka med att söka efter innehålls platserna som har misslyckats. Mer information finns i  [den här artikeln](https://docs.microsoft.com/microsoft-365/compliance/retry-failed-content-search) .

Om du exporterar fler än 100K-postlådor måste du använda följande PowerShell för att ladda ned export resultaten:  [Exportera resultat från fler än 100K-postlådor](https://docs.microsoft.com/microsoft-365/compliance/export-search-results?view=o365-worldwide%23exporting-results-from-more-than-100000-mailboxes).
