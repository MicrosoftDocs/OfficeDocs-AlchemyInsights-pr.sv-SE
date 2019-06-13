---
title: Prestanda problem-SharePoint eller OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 745a62c917c0b94501843332d70609261c6d3b76
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 06/07/2019
ms.locfileid: "34759168"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a><span data-ttu-id="96834-102">SharePoint- eller OneDrive långsam, inte tillgänglig eller inte tillgänglig för flera användare</span><span class="sxs-lookup"><span data-stu-id="96834-102">SharePoint or OneDrive Slow, Inaccessible or Unavailable for Multiple Users</span></span>

<span data-ttu-id="96834-103">Om en OneDrive eller SharePoint-webbplatsen inte är tillgänglig för flera användare som tidigare har haft åtkomst kan det finnas en tillfällig service-problem.</span><span class="sxs-lookup"><span data-stu-id="96834-103">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> <span data-ttu-id="96834-104">[Kontrollera att tjänsten hälsa instrumentpanelen](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="96834-104">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>

<span data-ttu-id="96834-105">Lägg till och licensiera användaren</span><span class="sxs-lookup"><span data-stu-id="96834-105">Add and license the user</span></span>

<span data-ttu-id="96834-106">Se till att du [tilldela licenser till användare i Office 365 för företag](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="96834-106">Ensure that you [Assign licenses to users in Office 365 for business](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span>


<span data-ttu-id="96834-107">**Tilldela behörigheter**</span><span class="sxs-lookup"><span data-stu-id="96834-107">**Assign Permissions**</span></span>

<span data-ttu-id="96834-108">Om användaren har tilldelats en licens för Sharepoint och ändå får meddelandet åtkomst nekad, kontrollera att de har [rätt behörighetsnivå](https://docs.microsoft.com/sharepoint/understanding-permission-levels) tilldelad.</span><span class="sxs-lookup"><span data-stu-id="96834-108">If the user has been assigned a Sharepoint license and is still receiving an access denied message, please ensure they have the [appropriate permission level](https://docs.microsoft.com/sharepoint/understanding-permission-levels) assigned.</span></span>

<span data-ttu-id="96834-109">**Överväg att använda funktionen begäran**</span><span class="sxs-lookup"><span data-stu-id="96834-109">**Consider using the access request feature**</span></span>

<span data-ttu-id="96834-110">[Begäran funktionen](https://support.office.com/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) tillåter att begära åtkomst till innehåll som de inte har behörighet att visa för tillfället.</span><span class="sxs-lookup"><span data-stu-id="96834-110">The [access request feature](https://support.office.com/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) allows people to request access to content that they do not currently have permission to see.</span></span>

<span data-ttu-id="96834-111">**Tillåt anpassade skript kan orsaka åtkomst nekad problem**</span><span class="sxs-lookup"><span data-stu-id="96834-111">**Allow custom script may cause access denied issues**</span></span>

<span data-ttu-id="96834-112">Det finns vissa scenarier där funktionen *Tillåt anpassade skript* kan lyckas förmedla ett åtkomst nekas.</span><span class="sxs-lookup"><span data-stu-id="96834-112">There are certain scenarios where the *Allow custom script* feature may be presenting an access denied.</span></span> <span data-ttu-id="96834-113">För en lista över funktioner som påverkas, säkerhetsaspekter och möjligheten att inaktivera funktionen.</span><span class="sxs-lookup"><span data-stu-id="96834-113">For a list of features affected, security considerations and the ability to disable the feature.</span></span> <span data-ttu-id="96834-114">Besök [Tillåt eller förhindra att skriptet](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="96834-114">Please visit [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span></span>
