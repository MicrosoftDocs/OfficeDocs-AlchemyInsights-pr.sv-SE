---
title: Teams Tillåt eller inaktivera IP-video
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
- "9002537"
- "5617"
ms.openlocfilehash: cf2d67170f846db1d5d2f1ca8c8b50902e200e45
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 09/14/2020
ms.locfileid: "47670202"
---
# <a name="teams-allow-or-disable-ip-video"></a><span data-ttu-id="ee587-102">Teams Tillåt eller inaktivera IP-video</span><span class="sxs-lookup"><span data-stu-id="ee587-102">Teams allow or disable IP video</span></span>

<span data-ttu-id="ee587-103">**Ändra eller skapa en Mötes princip**</span><span class="sxs-lookup"><span data-stu-id="ee587-103">**Change or create a meeting policy**</span></span>

<span data-ttu-id="ee587-104">Om du vill ändra eller skapa en Mötes princip går du till **administrations centret för Microsoft team >-möten > Mötes principer**.</span><span class="sxs-lookup"><span data-stu-id="ee587-104">To change or create a meeting policy, go to the **Microsoft Teams admin center > Meetings > Meeting policies**.</span></span> <span data-ttu-id="ee587-105">Välj en princip från listan eller klicka på **Lägg till**.</span><span class="sxs-lookup"><span data-stu-id="ee587-105">Select a policy from the list or click **Add**.</span></span> <span data-ttu-id="ee587-106">Om du skapar en ny princip kan du lägga till ett namn och en beskrivning.</span><span class="sxs-lookup"><span data-stu-id="ee587-106">If you're creating a new policy, add a name and description.</span></span> <span data-ttu-id="ee587-107">Namnet får inte innehålla specialtecken eller vara längre än 64 tecken.</span><span class="sxs-lookup"><span data-stu-id="ee587-107">The name can't contain special characters or be longer than 64 characters.</span></span> <span data-ttu-id="ee587-108">Välj önskade inställningar och klicka på **OK**.</span><span class="sxs-lookup"><span data-stu-id="ee587-108">Choose your settings, and then click **Save**.</span></span>

<span data-ttu-id="ee587-109">Säg till exempel att du har många användare och vill begränsa hur mycket bandbredd som ska krävas för mötet.</span><span class="sxs-lookup"><span data-stu-id="ee587-109">For example, say you have many users and you want to limit the amount of bandwidth that their meeting would require.</span></span> <span data-ttu-id="ee587-110">Du kan skapa en ny anpassad princip med namnet "Begränsad bandbredd" och inaktivera följande inställningar:</span><span class="sxs-lookup"><span data-stu-id="ee587-110">You would create a new custom policy named "Limited bandwidth" and disable the following settings:</span></span>

<span data-ttu-id="ee587-111">Under **Ljud och video**:</span><span class="sxs-lookup"><span data-stu-id="ee587-111">Under **Audio & video**:</span></span>

- <span data-ttu-id="ee587-112">Inaktivera Tillåt molninspelning.</span><span class="sxs-lookup"><span data-stu-id="ee587-112">Turn off Allow cloud recording.</span></span>
- <span data-ttu-id="ee587-113">Inaktivera Tillåt IP-video.</span><span class="sxs-lookup"><span data-stu-id="ee587-113">Turn off Allow IP video.</span></span>

<span data-ttu-id="ee587-114">Tilldela sedan principen till användarna.</span><span class="sxs-lookup"><span data-stu-id="ee587-114">Then assign the policy to the users.</span></span>

<span data-ttu-id="ee587-115">**Tilldela en mötespolicy till användare**</span><span class="sxs-lookup"><span data-stu-id="ee587-115">**Assign a meeting policy to users**</span></span>

1. <span data-ttu-id="ee587-116">I den vänstra navigeringen i administrationscentret för Microsoft Teams går du till **Användare**och klicka sedan på användaren.</span><span class="sxs-lookup"><span data-stu-id="ee587-116">In the left navigation of the Microsoft Teams admin center, go to **Users**, and then click the user.</span></span>
2. <span data-ttu-id="ee587-117">Markera användaren genom att klicka till vänster om användarnamnet och sedan klicka på **Redigera inställningar**.</span><span class="sxs-lookup"><span data-stu-id="ee587-117">Select the user by clicking to the left of the user name, and then click **Edit settings**.</span></span>
3. <span data-ttu-id="ee587-118">Under **Mötes princip**väljer du den princip som du vill tilldela och klickar sedan på **Använd**.</span><span class="sxs-lookup"><span data-stu-id="ee587-118">Under **Meeting policy**, select the policy you want to assign and then click **Apply**.</span></span>

<span data-ttu-id="ee587-119">Mer information finns i [Hantera Mötes principer i Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span><span class="sxs-lookup"><span data-stu-id="ee587-119">For more information, see [Manage meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span></span>