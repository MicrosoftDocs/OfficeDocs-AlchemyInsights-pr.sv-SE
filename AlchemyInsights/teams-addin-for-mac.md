---
title: Teams-tillägg för Mac
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 08/10/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6173"
- "9003233"
ms.openlocfilehash: 74bd424f71a59b80a91b960b815363668bee7036
ms.sourcegitcommit: 1361b2b37fd0201502a1a3547084961de284a3fc
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 08/11/2020
ms.locfileid: "46629939"
---
# <a name="teams-add-in-for-mac"></a><span data-ttu-id="f8f78-102">Teams-tillägg för Mac</span><span class="sxs-lookup"><span data-stu-id="f8f78-102">Teams add-in for Mac</span></span>

<span data-ttu-id="f8f78-103">Följ de här anvisningarna om du vill felsöka ett tilläggsprogram för Mac-operativsystem för användare med ett team som saknas:</span><span class="sxs-lookup"><span data-stu-id="f8f78-103">To troubleshoot a missing Teams add-in for Mac operating system users, follow these steps:</span></span>

<span data-ttu-id="f8f78-104">**Steg 1:** Om du har hybrid Exchange lokalt (2016 CU3 eller senare krävs) kan du använda Test-HMA.ps1 verktyget för att bekräfta att hybrid modern verifikation är korrekt konfigurerad.</span><span class="sxs-lookup"><span data-stu-id="f8f78-104">**Step 1:** If you have Hybrid Exchange On-Premises (2016 CU3 or later required), use the Test-HMA.ps1 tool to confirm that Hybrid Modern Authentication is correctly configured.</span></span> <span data-ttu-id="f8f78-105">Mer information finns i [validera hybrid modern konfiguration för Outlook för iOS och Android](https://aka.ms/AA980zq).</span><span class="sxs-lookup"><span data-stu-id="f8f78-105">For more info, see [Validating Hybrid Modern Authentication setup for Outlook for iOS and Android](https://aka.ms/AA980zq).</span></span>  

<span data-ttu-id="f8f78-106">**Obs!** Använda UPN-adress format (till exempel [username@contoso.com](mailto:username@contoso.com)), inte domain\username.</span><span class="sxs-lookup"><span data-stu-id="f8f78-106">**Note** Use the UPN address format (for example, [username@contoso.com](mailto:username@contoso.com)), not domain\username.</span></span> <span data-ttu-id="f8f78-107">Gör detta även för användare med Exchange Online-postlådor.</span><span class="sxs-lookup"><span data-stu-id="f8f78-107">Do this even for users with Exchange Online mailboxes.</span></span>

<span data-ttu-id="f8f78-108">**Steg 2:** Få användaren att gå till **verktyg**  >  **konton**... Leta upp och Välj kontot i Outlook för Mac.</span><span class="sxs-lookup"><span data-stu-id="f8f78-108">**Step 2:** Have the user go to **Tools** > **Accounts**... in Outlook for Mac, and find and select the account.</span></span> <span data-ttu-id="f8f78-109">Bekräfta att username visas i UPN-format (till exempel [username@contoso.com](mailto:username@contoso.com)).</span><span class="sxs-lookup"><span data-stu-id="f8f78-109">Confirm the username listed is in UPN format (for example, [username@contoso.com](mailto:username@contoso.com)).</span></span>

<span data-ttu-id="f8f78-110">**Steg 3:** Bekräfta att användaren är en licensierad Microsoft Teams-användare.</span><span class="sxs-lookup"><span data-stu-id="f8f78-110">**Step 3:** Confirm the user is a licensed Microsoft Teams user.</span></span> <span data-ttu-id="f8f78-111">Användaren måste använda Office 365 för Mac-prenumerationen, produkt version 16,24 eller senare.</span><span class="sxs-lookup"><span data-stu-id="f8f78-111">The user must be using the Office 365 for Mac subscription, product version 16.24 or later.</span></span>