---
title: Har användarna fått skadlig e-post
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002907"
- "5594"
- "3100017"
- "2578"
ms.openlocfilehash: 2197e7f195d789193798b80cb092d8046eb6e0be
ms.sourcegitcommit: 3c708a4a349b60b59bc623c44fb78674c685f3c2
ms.translationtype: HT
ms.contentlocale: sv-SE
ms.lasthandoff: 02/18/2021
ms.locfileid: "50291810"
---
# <a name="did-your-users-receive-malicious-email"></a>Har användarna fått skadlig e-post?

- Nu kan du rapportera skadlig e-post till Microsoft med hjälp [Administratörsinlämningar i Säkerhets- och efterlevnadscenter](https://sip.protection.office.com/reportsubmission).

Meddelanden som skickas in [-administratörsinlämningar](https://sip.protection.office.com/reportsubmission) genomsöks och följande resultat visas i **information** som utfälld:

- Om avsändarens e-postautentisering misslyckades vid leveransen.
- Information om politiska träffar som kan ha påverkat eller åsidosatt bedömningen av ett meddelande.
- Aktuella detonationsresultat för att se om webbadresserna eller filerna i meddelandet var skadliga eller inte.
- Feedback från klassare

Om en åsidosättning hittades bör omskanningen slutföras på några minuter. Om det inte uppstod något problem med e-postautentisering eller om leveransen inte påverkades av en åsidosättning, kan det ta upp till en dag för feedbacken från klasserna.

Om du inte håller med den slutliga domen om ett meddelande, URL eller fil (blockerad kontra inte blockerad), skicka meddelandet igen efter en dag för att skanna igen. Sannolikheten är stor för att domen skulle förändras efter att ha skickat meddelandet igen.

Under tiden kan du ta bort skadlig e-post från användarnas inkorgar genom att följa anvisningarna [i den här artikeln](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messages-in-your-organization).

- Kunder med Microsoft Defender för Office 365 kan:
    - använder [Utforskaren för att hitta och ta bort misstänkta e-postmeddelanden](https://docs.microsoft.com/microsoft-365/security/office-365-security/investigate-malicious-email-that-was-delivered)
    - [använder du Säkra länkar för att blockera åtkomst](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-safe-links) till en skadlig URL
    - spåra användare som har klickat på och kommit åt skadliga URL:er: [Visa nätfiske-URL och klicka på bedömningsdata](https://docs.microsoft.com/microsoft-365/security/office-365-security/threat-explorer) & [Get-UrlTrace](https://docs.microsoft.com/powershell/module/exchange/get-urltrace)
    - manuellt [starta en automatiserad undersökning](https://docs.microsoft.com/microsoft-365/security/office-365-security/automated-investigation-response-office)

Du kan också skydda mot skadliga filer och URL-adresser genom att följa anvisningarna i [Skydd mot skadliga URL:er och filer](https://docs.microsoft.com/microsoft-365/security/office-365-security/protect-against-threats).