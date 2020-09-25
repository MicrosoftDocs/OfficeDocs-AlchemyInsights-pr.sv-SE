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
# <a name="troubleshoot-content-search-errors"></a><span data-ttu-id="6a2b3-102">Felsöka problem med innehålls sökning</span><span class="sxs-lookup"><span data-stu-id="6a2b3-102">Troubleshoot Content Search errors</span></span>

<span data-ttu-id="6a2b3-103">Har du problem med innehålls sökning eller får du fel när du exporterar Sök Resultat?</span><span class="sxs-lookup"><span data-stu-id="6a2b3-103">Are you experiencing problems with Content Search or getting failures when you export search results?</span></span>

<span data-ttu-id="6a2b3-104">Får du till exempel följande när du kör sökningar?</span><span class="sxs-lookup"><span data-stu-id="6a2b3-104">For example, are you receiving the following when running searches?</span></span>

- <span data-ttu-id="6a2b3-105">CS008-eller CS012-fel</span><span class="sxs-lookup"><span data-stu-id="6a2b3-105">CS008 or CS012 errors</span></span>

- <span data-ttu-id="6a2b3-106">Upptaget/timeout-fel på servern</span><span class="sxs-lookup"><span data-stu-id="6a2b3-106">Server busy/timeout errors</span></span>

- <span data-ttu-id="6a2b3-107">Program fel uppstod</span><span class="sxs-lookup"><span data-stu-id="6a2b3-107">Application error occurred</span></span>

<span data-ttu-id="6a2b3-108">Eller när du söker efter eller exporterar resultat från ett stort antal post lådor (över 100 000-postlådor) får du bara exportera fel?</span><span class="sxs-lookup"><span data-stu-id="6a2b3-108">Or when searching or exporting results from a large number of mailboxes (over 100,000 mailboxes), are you getting export errors?</span></span>

<span data-ttu-id="6a2b3-109">För de här fel typerna kan du försöka med att söka efter innehålls platserna som har misslyckats.</span><span class="sxs-lookup"><span data-stu-id="6a2b3-109">For these types of errors, retry the search for the content locations that have failed.</span></span> <span data-ttu-id="6a2b3-110">Mer information finns i  [den här artikeln](https://docs.microsoft.com/microsoft-365/compliance/retry-failed-content-search) .</span><span class="sxs-lookup"><span data-stu-id="6a2b3-110">See  [this article](https://docs.microsoft.com/microsoft-365/compliance/retry-failed-content-search) for more information.</span></span>

<span data-ttu-id="6a2b3-111">Om du exporterar fler än 100K-postlådor måste du använda följande PowerShell för att ladda ned export resultaten:  [Exportera resultat från fler än 100K-postlådor](https://docs.microsoft.com/microsoft-365/compliance/export-search-results?view=o365-worldwide%23exporting-results-from-more-than-100000-mailboxes).</span><span class="sxs-lookup"><span data-stu-id="6a2b3-111">If you are exporting more than 100K mailboxes, you will need to use the following Powershell to download the Export results:  [Exporting results from more than 100K mailboxes](https://docs.microsoft.com/microsoft-365/compliance/export-search-results?view=o365-worldwide%23exporting-results-from-more-than-100000-mailboxes).</span></span>
