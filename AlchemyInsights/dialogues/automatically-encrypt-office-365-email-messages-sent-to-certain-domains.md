---
title: Kryptera e-postmeddelanden i Office 365 automatiskt som skickas till vissa domäner
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: 7fb96a30cd1922bd39a4b99a7ecd869622f3a466
ms.sourcegitcommit: c202c0df2d141e63f4f7eb13a56efbfc2f57348f
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 03/05/2021
ms.locfileid: "50526699"
---
# <a name="automatically-encrypt-office-365-email-messages-sent-to-certain-domains"></a><span data-ttu-id="66afb-102">Kryptera e-postmeddelanden i Office 365 automatiskt som skickas till vissa domäner</span><span class="sxs-lookup"><span data-stu-id="66afb-102">Automatically encrypt Office 365 email messages sent to certain domains</span></span>

1. <span data-ttu-id="66afb-103">I [administrationscentret för Exchange väljer](https://outlook.office365.com/ecp/)du **e-postflöde > regler.**</span><span class="sxs-lookup"><span data-stu-id="66afb-103">From the [Exchange admin center](https://outlook.office365.com/ecp/), choose **mail flow > rules**.</span></span> 
2. <span data-ttu-id="66afb-104">Klicka på **ikonen Ny (+)** och sedan på Använd meddelandekryptering **i Office 365 och rättighetsskydd för meddelanden.**</span><span class="sxs-lookup"><span data-stu-id="66afb-104">Click the **New (+)** icon, and then click **Apply Office 365 Message Encryption and rights protection to messages**.</span></span>
3. <span data-ttu-id="66afb-105">Ange **ett** namn på regeln i Namn, till exempel Kryptera meddelanden *som skickas till contoso.com.*</span><span class="sxs-lookup"><span data-stu-id="66afb-105">In **Name**, enter a name for the rule, such as *Encrypt messages sent to contoso.com*.</span></span>
4. <span data-ttu-id="66afb-106">I **Använd den här regeln om** väljer du > domän **är.**</span><span class="sxs-lookup"><span data-stu-id="66afb-106">In **Apply this rule if**, choose **The recipient > domain is**.</span></span> 
5. <span data-ttu-id="66afb-107">Ange namnet på domänen, till exempel **contoso.com.**</span><span class="sxs-lookup"><span data-stu-id="66afb-107">Enter the name of the domain, such as **contoso.com**.</span></span>
6. <span data-ttu-id="66afb-108">Klicka på **ikonen Lägg till (+)** och sedan på **OK.**</span><span class="sxs-lookup"><span data-stu-id="66afb-108">Click the **Add (+)** icon, and then click **OK**.</span></span>
7. <span data-ttu-id="66afb-109">Klicka på **Markera ett fält bredvid** Gör följande **fält.**</span><span class="sxs-lookup"><span data-stu-id="66afb-109">Next to the **Do the following** field, click **Select one**.</span></span> 
8. <span data-ttu-id="66afb-110">I den **nedrullningsmenyn** för RMS-mallen väljer **du** Kryptera och klickar sedan på **OK.**</span><span class="sxs-lookup"><span data-stu-id="66afb-110">In the **RMS template** drop-down menu, select **Encrypt**, and then click **OK**.</span></span> <span data-ttu-id="66afb-111">(Om du inte ser det här alternativet innebär det att ditt abonnemang inte innehåller automatisk kryptering.</span><span class="sxs-lookup"><span data-stu-id="66afb-111">(If you don't see this option, it means your plan doesn't include automatic encryption.</span></span> <span data-ttu-id="66afb-112">Men du kan lägga till den!)</span><span class="sxs-lookup"><span data-stu-id="66afb-112">But you can add it!)</span></span>
9. <span data-ttu-id="66afb-113">Välj valfritt (i en lista med valfria val som du kan göra i det här läget, många av dem kan lämnas kvar med standardinställningen för enkelhetens skull).</span><span class="sxs-lookup"><span data-stu-id="66afb-113">Choose any optional selection (from a list of optional selections that you can make at this point, many of which can be left with the default setting for simplicity).</span></span>
10. <span data-ttu-id="66afb-114">Klicka på **Spara**.</span><span class="sxs-lookup"><span data-stu-id="66afb-114">Click **Save**.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="66afb-115">Du kan alltid gå tillbaka och redigera regeln senare.</span><span class="sxs-lookup"><span data-stu-id="66afb-115">You can always come back and edit this rule later.</span></span>

<span data-ttu-id="66afb-116">Mer information om hur du skapar krypteringsregler finns i [Definiera e-postflödesregler för att kryptera e-postmeddelanden i Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)</span><span class="sxs-lookup"><span data-stu-id="66afb-116">For more information about creating rules for encryption, see [Define mail flow rules to encrypt email messages in Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)</span></span>