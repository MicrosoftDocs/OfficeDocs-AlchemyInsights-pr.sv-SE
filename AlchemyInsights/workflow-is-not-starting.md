---
title: Arbets flödet startar inte
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: e3b8777ed74b812b31338784999eea43a95d3456
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 09/15/2020
ms.locfileid: "47794785"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="f579b-102">Arbets flödet startar inte</span><span class="sxs-lookup"><span data-stu-id="f579b-102">Workflow is not starting</span></span>

- <span data-ttu-id="f579b-103">SharePoint 2010-och SharePoint 2013-arbets flöden startas inte.</span><span class="sxs-lookup"><span data-stu-id="f579b-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    - <span data-ttu-id="f579b-104">Om arbets flödet inte startas kan det finnas ett tillfälligt tjänst problem där användarna kan uppleva fördröjningar med arbets flödes status.</span><span class="sxs-lookup"><span data-stu-id="f579b-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="f579b-105">Kontrol lera [instrument panelen för tjänstens hälsa](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) för att se om din organisation påverkas.</span><span class="sxs-lookup"><span data-stu-id="f579b-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    - <span data-ttu-id="f579b-106">Om det inte finns mer än 24 timmar sedan du först såg det här problemet, logga in ett support ärende.</span><span class="sxs-lookup"><span data-stu-id="f579b-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="f579b-107">I många fall jobbar vi redan med en lösning.</span><span class="sxs-lookup"><span data-stu-id="f579b-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="f579b-108">Ange minst 24 timmar för att slutföra en lösning.</span><span class="sxs-lookup"><span data-stu-id="f579b-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="f579b-109">SharePoint 2010-arbets flöden fördröjs vid start.</span><span class="sxs-lookup"><span data-stu-id="f579b-109">SharePoint 2010 workflows delayed on start.</span></span>

    - <span data-ttu-id="f579b-110">Detta inträffar om arbets flödet utlöses i stora grupper.</span><span class="sxs-lookup"><span data-stu-id="f579b-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="f579b-111">(när flera objekt läggs till samtidigt).</span><span class="sxs-lookup"><span data-stu-id="f579b-111">(for example, when several items are added at once).</span></span>

    - <span data-ttu-id="f579b-112">Arbets flöden är inte avsedda att köras i real tid, så en fördröjning är by-design.</span><span class="sxs-lookup"><span data-stu-id="f579b-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

   -  <span data-ttu-id="f579b-113">Om arbets flödet är ett komplext Extensible Object Markup Language (XMOL) kan kompileringen bli långsam.</span><span class="sxs-lookup"><span data-stu-id="f579b-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="f579b-114">Kontrol lera [den här](https://support.microsoft.com//kb/3043697) artikeln.</span><span class="sxs-lookup"><span data-stu-id="f579b-114">Check [this](https://support.microsoft.com//kb/3043697) article.</span></span>

    - <span data-ttu-id="f579b-115">Du bör förenkla arbets flödet eller omkonstruera det med hjälp av plattforms typen Microsoft SharePoint 2013 Workflow.</span><span class="sxs-lookup"><span data-stu-id="f579b-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    - <span data-ttu-id="f579b-116">Om arbets flödes historiken är stor kanske du vill ta bort objekten eller skapa en ny historik lista.</span><span class="sxs-lookup"><span data-stu-id="f579b-116">If your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

        <span data-ttu-id="f579b-117">Mer information: [ta bort arbets flödes historik](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="f579b-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="f579b-118">Relaterade ämnen</span><span class="sxs-lookup"><span data-stu-id="f579b-118">Related topics</span></span>
<span data-ttu-id="f579b-119">Vill du prova Microsoft Flow i SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="f579b-119">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="f579b-120">Skapa flöde</span><span class="sxs-lookup"><span data-stu-id="f579b-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="f579b-121">SharePoint och flöde</span><span class="sxs-lookup"><span data-stu-id="f579b-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


