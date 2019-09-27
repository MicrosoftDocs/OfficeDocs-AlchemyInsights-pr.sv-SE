---
title: Inte ta emot SharePoint-och OneDrive-aviseringar
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/25/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: 80423791ad558fc414d50608c73f823036432e14
ms.sourcegitcommit: 5e6a805fb0b41d714ca1cf90e23b8e2daa90f90e
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 09/26/2019
ms.locfileid: "37205559"
---
# <a name="not-receiving-sharepoint-and-onedrive-alerts"></a><span data-ttu-id="1f6ab-102">Inte ta emot SharePoint-och OneDrive-aviseringar</span><span class="sxs-lookup"><span data-stu-id="1f6ab-102">Not receiving SharePoint and OneDrive alerts</span></span>

<span data-ttu-id="1f6ab-103">Kontrollera först skräppostmappen i din e-post.</span><span class="sxs-lookup"><span data-stu-id="1f6ab-103">First check the Junk or Spam folder in your email.</span></span>

<span data-ttu-id="1f6ab-104">Bestäm sedan om **alla aviseringar inte levereras** eller om **en enskild avisering** från en viss fil eller ett visst bibliotek inte levereras.</span><span class="sxs-lookup"><span data-stu-id="1f6ab-104">Then determine if **all alerts are not delivered** or if **an individual alert** from a specific file or library is not delivered.</span></span>

- <span data-ttu-id="1f6ab-105">Om **alla aviseringar från flera filer eller bibliotek inte levereras**kan du gå till [instrumentpanelen för tjänstens hälsa](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fadmin.microsoft.com%2FAdminPortal%2FHome%23%2Fservicehealth&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) för att kontrollera om det finns några bulletiner/incidenter som kanske inträffar med SharePoint eller Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f6ab-105">If **all alerts from multiple files or libraries are not delivered**, visit the [Service Health dashboard](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fadmin.microsoft.com%2FAdminPortal%2FHome%23%2Fservicehealth&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="1f6ab-106">Problemet kan vara med SharePoint alert-funktionen eller fördröjningar i e-postmeddelanden via Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f6ab-106">The issue might be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="1f6ab-107">Observera också om andra e-post levereras-om inte, är problemet sannolikt med Exchange förseningar.</span><span class="sxs-lookup"><span data-stu-id="1f6ab-107">Also note whether other email is being delivered—if not, the issue is likely with Exchange delays.</span></span>
- <span data-ttu-id="1f6ab-108">Om **en enskild avisering från en viss fil eller ett visst bibliotek inte levereras**försöker du ta bort den och återskapa den.</span><span class="sxs-lookup"><span data-stu-id="1f6ab-108">If **an individual alert from a specific file or library is not delivered**, attempt to delete and recreate it.</span></span> <span data-ttu-id="1f6ab-109">Se [Hantera, Visa eller ta bort SharePoint-aviseringar](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsupport.office.com%2Farticle%2Fmanage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2%3Fui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax%2Fepn3E%3D&reserved=0) för att återskapa aviseringen.</span><span class="sxs-lookup"><span data-stu-id="1f6ab-109">See [Manage, view, or delete SharePoint alerts](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsupport.office.com%2Farticle%2Fmanage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2%3Fui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax%2Fepn3E%3D&reserved=0) to recreate the alert.</span></span>

> [!NOTE]
> - <span data-ttu-id="1f6ab-110">Aviseringar kan inte skickas till en distributionsgrupp.</span><span class="sxs-lookup"><span data-stu-id="1f6ab-110">Alerts cannot be sent to a Distribution Group.</span></span> <span data-ttu-id="1f6ab-111">Endast säkerhets-och O365-grupper stöds.</span><span class="sxs-lookup"><span data-stu-id="1f6ab-111">Only Security and O365 groups are supported.</span></span>
> - <span data-ttu-id="1f6ab-112">Du kan inte anpassa e-postmallar för notifieringar.</span><span class="sxs-lookup"><span data-stu-id="1f6ab-112">You cannot customize alert email templates.</span></span> <span data-ttu-id="1f6ab-113">Du måste använda Microsoft Flow eller SharePoint Designer-arbetsflöde för att uppnå dessa.</span><span class="sxs-lookup"><span data-stu-id="1f6ab-113">You must use Microsoft Flow or SharePoint Designer Workflow to achieve those.</span></span>
