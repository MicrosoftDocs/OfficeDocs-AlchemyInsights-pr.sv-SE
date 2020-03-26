---
title: Allmän prestandavägledning för migrering
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "3179"
ms.openlocfilehash: 10a0069c41d2e5128b2592425d815364a83b730f
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: sv-SE
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932496"
---
# <a name="general-migration-performance-guidance"></a>Allmän prestandavägledning för migrering

**Viktigt**: många SharePoint Online- och OneDrive-kunder kör företagskritiska applikationer mot den tjänst som körs i bakgrunden. Här ingår lösningar för migrering av innehåll, DLP (skydd mot dataförlust) och säkerhetskopiering. Under dessa tider som saknar motstycke tar vi stegen för att se till att SharePoint Online- och OneDrive-tjänsterna är mycket tillgängliga och tillförlitliga för dina användare som är beroende av tjänsten mer än någonsin i scenarier med distansarbete.

För att stödja det målet har vi genomfört strängare begränsningar för bakgrundsprogram (lösningar för migrering, DLP och säkerhetskopiering) under dagtid på veckodagar. Du bör förvänta dig att programmen kommer att uppnå mycket begränsad genomströmning under dessa tider. Under kvällstid och de dagar som anses som helger i regionen står tjänster redo att ta hand om avsevärt högre volymer med förfrågningar från bakgrundsprogram.

**Prestandavägledning för migrering**

Prestanda för migrering kan påverkas av nätverksinfrastrukturen, filstorlek, migreringstid och begränsning. Att förstå dem hjälper dig att planera och maximera effektiviteten i migreringen.

- [Allmän prestandavägledning för migrering](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)