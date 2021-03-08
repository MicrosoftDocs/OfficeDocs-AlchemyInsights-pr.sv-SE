---
title: Konfigurera meddelandekryptering för en hybridmiljö
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
ms.openlocfilehash: 22c2468b7639680b447b6464431a79b69f7198c3
ms.sourcegitcommit: c202c0df2d141e63f4f7eb13a56efbfc2f57348f
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 03/05/2021
ms.locfileid: "50526603"
---
# <a name="configure-message-encryption-for-a-hybrid-environment"></a><span data-ttu-id="d2f49-102">Konfigurera meddelandekryptering för en hybridmiljö</span><span class="sxs-lookup"><span data-stu-id="d2f49-102">Configure message encryption for a hybrid environment</span></span>

<span data-ttu-id="d2f49-103">För hybridmiljöer av Exchange kan lokala användare skicka krypterad e-post med hjälp av Meddelandekryptering i Office (OME) endast om e-post dirigeras via Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="d2f49-103">For hybrid Exchange environments, on-premises users can send encrypted email using Office Message Encryption (OME) only if email is routed through Exchange Online.</span></span>

<span data-ttu-id="d2f49-104">Så här krypterar du e-postmeddelanden med OME:</span><span class="sxs-lookup"><span data-stu-id="d2f49-104">To encrypt emails using OME, perform the following steps:</span></span>

1. <span data-ttu-id="d2f49-105">Använd [hybridkonfigurationsguiden för](https://docs.microsoft.com/Exchange/hybrid-configuration-wizard) att konfigurera hybridmiljön.</span><span class="sxs-lookup"><span data-stu-id="d2f49-105">Use the [Hybrid Configuration wizard](https://docs.microsoft.com/Exchange/hybrid-configuration-wizard) to set up your hybrid environment.</span></span> <span data-ttu-id="d2f49-106">Inga särskilda steg krävs för att konfigurera kryptering.</span><span class="sxs-lookup"><span data-stu-id="d2f49-106">No special steps are required for setting up encryption.</span></span>
2. <span data-ttu-id="d2f49-107">[Konfigurera e-postflödesregler för kryptering på](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email) samma sätt som vanligt.</span><span class="sxs-lookup"><span data-stu-id="d2f49-107">[Set up your mail flow rules for encryption](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email) like you normally would.</span></span>


