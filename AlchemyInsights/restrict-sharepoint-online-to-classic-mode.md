---
title: Begränsa SharePoint Online till klassiskt läge
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.custom:
- "1835"
- "1889"
- "9000225"
ms.openlocfilehash: c5ea5d264b62e4c349623bd431776207b38da470
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742487"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="1a0ad-102">Begränsa SharePoint Online till klassiskt läge</span><span class="sxs-lookup"><span data-stu-id="1a0ad-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="1a0ad-103">Vissa organisationer kräver fortfarande upplevelsen av klassiskt läge.</span><span class="sxs-lookup"><span data-stu-id="1a0ad-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="1a0ad-104">Även om det inte finns några planer på att ta bort klassiskt läge på detaljerad nivå, är det inte längre möjligt att begränsa en hel organisation (klient) till klassiskt läge för listor och bibliotek.</span><span class="sxs-lookup"><span data-stu-id="1a0ad-104">While there are no plans to remove classic mode at a granular level, it is no longer possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="1a0ad-105">Administratören har följande alternativ för att hantera enskilda listor och bibliotek i klassiskt läge med hjälp av detaljerade opt-out-växlar som vi tillhandahåller på följande nivåer:</span><span class="sxs-lookup"><span data-stu-id="1a0ad-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

- <span data-ttu-id="1a0ad-106">webbplatssamling</span><span class="sxs-lookup"><span data-stu-id="1a0ad-106">site collection</span></span>
- <span data-ttu-id="1a0ad-107">Webbplats</span><span class="sxs-lookup"><span data-stu-id="1a0ad-107">site</span></span>
- <span data-ttu-id="1a0ad-108">Lista</span><span class="sxs-lookup"><span data-stu-id="1a0ad-108">list</span></span>
- <span data-ttu-id="1a0ad-109">Bibliotek</span><span class="sxs-lookup"><span data-stu-id="1a0ad-109">library</span></span>

<span data-ttu-id="1a0ad-110">Dessutom kommer listor som använder vissa funktioner och anpassningar som inte stöds av moderna fortfarande automatiskt att växlas till klassiskt läge.</span><span class="sxs-lookup"><span data-stu-id="1a0ad-110">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="1a0ad-111">Från och med den 1 april 2019 kommer processen att inaktivera klientnivå välja bort modern lista och bibliotek startar och fortsätter till och med 31 maj 2019.</span><span class="sxs-lookup"><span data-stu-id="1a0ad-111">Beginning April 1, 2019, the process to disable the tenant level opt out of modern list and libraries will start and continue through May 31, 2019.</span></span>  <span data-ttu-id="1a0ad-112">Listorna och biblioteken som är i klassiskt läge som ett resultat av klientanmälan flyttas automatiskt till modernt.</span><span class="sxs-lookup"><span data-stu-id="1a0ad-112">The lists and libraries that are in classic mode as a result of tenant opt-out will automatically be shifted to modern.</span></span>

<span data-ttu-id="1a0ad-113">Om du behöver klassiskt läge kan du se mer information [här](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) och PnP Powershell instruktion [här](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) som beskriver alternativ och verktyg som du kan använda idag för att använda det klassiska läget erfarenhet.</span><span class="sxs-lookup"><span data-stu-id="1a0ad-113">If you require classic mode please see more information [here](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) and PnP Powershell instruction [here](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) that describes options and tools you can use today to use the classic mode experience.</span></span>
