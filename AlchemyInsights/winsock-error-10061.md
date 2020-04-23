---
title: 1554 Winsock fel 10061
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1554"
- "9000079"
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: e8f62d97efc937518ef766b45e1747e83b7f99c3
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766187"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="55940-102">Winsock fel 10061</span><span class="sxs-lookup"><span data-stu-id="55940-102">Winsock error 10061</span></span>

<span data-ttu-id="55940-103">Den här felkoden innebär att Microsoft inte kunde upprätta en TCP-socket (anslutning) med målvärden.</span><span class="sxs-lookup"><span data-stu-id="55940-103">This error code means that Microsoft couldn't establish a TCP socket (connection) with the target host.</span></span> <span data-ttu-id="55940-104">Den troligaste orsaken till det här felet är ett problem med brandväggskonfigurationen.</span><span class="sxs-lookup"><span data-stu-id="55940-104">The most likely cause of this error is a problem with your firewall configuration.</span></span> <span data-ttu-id="55940-105">Kontrollera följande inställningar för att åtgärda problemet:</span><span class="sxs-lookup"><span data-stu-id="55940-105">To fix the problem, check these settings:</span></span>

- <span data-ttu-id="55940-106">Verifiera brandväggskonfigurationen med informationen i [Microsoft 365-URL:er och IP-adressintervall](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span><span class="sxs-lookup"><span data-stu-id="55940-106">Verify your firewall configuration with the information in [Microsoft 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>

- <span data-ttu-id="55940-107">Om felet är specifikt för Exchange Online Protection (EOP) bör du tidigare ha meddelats om en ändring av [EXCHANGE Online Protection IP-adresser](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="55940-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>

- <span data-ttu-id="55940-108">Kontrollera att Internet-leverantören inte blockerar porten.</span><span class="sxs-lookup"><span data-stu-id="55940-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>

- <span data-ttu-id="55940-109">Verifiera inställningarna för den smarta värden och målservern i kontakterna.</span><span class="sxs-lookup"><span data-stu-id="55940-109">Verify the smart host and target server settings in your connectors.</span></span>

<span data-ttu-id="55940-110">Observera att Microsoft 365 inte blockerar *inkommande* anslutningar på detta sätt.</span><span class="sxs-lookup"><span data-stu-id="55940-110">Note that Microsoft 365 doesn't block *incoming* connections in this manner.</span></span>
