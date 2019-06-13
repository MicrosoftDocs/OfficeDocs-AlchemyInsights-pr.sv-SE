---
title: 'Felsökning: åtkomst nekad meddelanden'
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: c204f1889e03886fdfd3d1c760a4a2beb82b0836
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760358"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a><span data-ttu-id="c289b-102">Felsökning: åtkomst nekad meddelanden i Sharepoint OneDrive/Admin Center</span><span class="sxs-lookup"><span data-stu-id="c289b-102">Troubleshoot Access Denied messages in Sharepoint/OneDrive Admin Center</span></span>

<span data-ttu-id="c289b-103">Om du får meddelandet åtkomst nekad när du försöker bläddra till en Sharepoint OneDrive/Admin Center, kontrollera att du [tilldela en licens till användaren](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="c289b-103">If you are receiving an access denied message when attempting to browse to a Sharepoint/OneDrive Admin Center, please make sure that you [assign a license to the user](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span> <span data-ttu-id="c289b-104">Om användaren har en licens, bör du försäkra dig om att de är [tilldelade en administratör](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) som kan komma åt admin Center.</span><span class="sxs-lookup"><span data-stu-id="c289b-104">If the user has a license, you should also make sure they are [assigned an administrator role](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) that can access the admin centers.</span></span>

<span data-ttu-id="c289b-105">Det här problemet kan också uppstå när en användare tas bort och återskapas med samma användarhuvudnamn (UPN).</span><span class="sxs-lookup"><span data-stu-id="c289b-105">This issue can also occur when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="c289b-106">Det nya kontot har skapats med ett annat värde PUID (Passport unika ID).</span><span class="sxs-lookup"><span data-stu-id="c289b-106">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="c289b-107">När användaren försöker komma åt en webbplatssamling eller deras OneDrive, har användaren en felaktig PUID.</span><span class="sxs-lookup"><span data-stu-id="c289b-107">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="c289b-108">Andra scenariot innebär katalogsynkronisering med en Active Directory-organisationsenhet (OU).</span><span class="sxs-lookup"><span data-stu-id="c289b-108">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="c289b-109">Om användare har redan inloggad i SharePoint, och har flyttats till en annan Organisationsenhet och resynced med SharePoint, kan problemet uppstå.</span><span class="sxs-lookup"><span data-stu-id="c289b-109">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="c289b-110">Lös det här problemet, bör du återställa den ursprungliga UPN med åtgärderna i artikeln [återställa en användare i Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="c289b-110">To resolve this issue, you should restore the original UPN with the steps in the article, [Restore a user in Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>

<span data-ttu-id="c289b-111">Anmärkning: Om ett OneDrive eller SharePoint Admin center inte är tillgängligt för flera användare som tidigare hade åtkomst, kan det finnas en tillfällig service problem.</span><span class="sxs-lookup"><span data-stu-id="c289b-111">Note: If a OneDrive or SharePoint Admin center is not available to multiple users who previously had access, there may be a temporary service issue.</span></span>  <span data-ttu-id="c289b-112">[Kontrollera att tjänsten hälsa instrumentpanelen](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="c289b-112">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>

