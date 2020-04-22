---
title: Arbeta med iOS VPP Applications Rule ID 1018
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1018"
- "6700004"
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 88a1ef66bf337b3a0094976c122330591aee77ff
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 04/22/2020
ms.locfileid: "43719975"
---
# <a name="working-with-ios-vpp-applications"></a><span data-ttu-id="72918-102">Arbeta med iOS VPP-program</span><span class="sxs-lookup"><span data-stu-id="72918-102">Working with iOS VPP Applications</span></span>

<span data-ttu-id="72918-103">Läs [så här hanterar du iOS-appar som köpts via ett volymköpsprogram med Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) om du vill veta mer om funktioner, begränsningar och steg för att använda Apple Volume Purchase Program och stödet för det i Microsoft Intune.</span><span class="sxs-lookup"><span data-stu-id="72918-103">Read [How to manage iOS apps purchased through a volume-purchase program with Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) to learn about features, constraints, and steps to make use of the Apple Volume Purchase Program and the support for it in Microsoft Intune.</span></span>
  
 <span data-ttu-id="72918-104">**Vanliga frågor:** "Jag tilldelade en iOS VPP-app till mina användare, men installationen misslyckades."</span><span class="sxs-lookup"><span data-stu-id="72918-104">**Common Issues:** "I assigned an iOS VPP app to my users, but the installation failed."</span></span>
  
- <span data-ttu-id="72918-105">Detta kan inträffa om en enda VPP-token används över flera leverantörer av hantering av mobila enheter.</span><span class="sxs-lookup"><span data-stu-id="72918-105">This can happen if a single VPP token is used across multiple mobile device management providers.</span></span> <span data-ttu-id="72918-106">VPP-tokens från Apple får endast användas hos en leverantör.</span><span class="sxs-lookup"><span data-stu-id="72918-106">VPP tokens from Apple may only be used with one provider.</span></span> <span data-ttu-id="72918-107">Om du använde en VPP-token med flera providers måste du ladda upp token till Intune igen.</span><span class="sxs-lookup"><span data-stu-id="72918-107">If you used a VPP token with multiple providers, you must re-upload the token to Intune.</span></span>

- <span data-ttu-id="72918-108">Installationen kan också misslyckas om det totala antalet installationer överstiger antalet licenser.</span><span class="sxs-lookup"><span data-stu-id="72918-108">The installation can also fail if the total number of installations exceed the number of licenses.</span></span> <span data-ttu-id="72918-109">Om du vill visa en användningsrapport för dina licenser går du till sidan Licenser för **Intune Mobile** \> **apps-appar.**</span><span class="sxs-lookup"><span data-stu-id="72918-109">To view a usage report for your licenses, go to the **Intune Mobile apps** \> **App licenses** page.</span></span> <span data-ttu-id="72918-110">Mer information om hur du återkräver licenser som används finns i [den här artikeln.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span><span class="sxs-lookup"><span data-stu-id="72918-110">To learn how to reclaim licenses in use, see [this article.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span></span>
