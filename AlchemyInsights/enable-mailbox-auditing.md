---
title: Aktivera granskning av post låda
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 404ef9ecd824541f98471bb8797f5f6e025012b7
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806309"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="ced66-102">Aktivera granskning av post låda</span><span class="sxs-lookup"><span data-stu-id="ced66-102">Enable mailbox auditing</span></span>

<span data-ttu-id="ced66-103">Om du vill aktivera granskning av post låda för en enskild användare eller en hel organisation måste följande cmdlets köras från Remote Power Shell:</span><span class="sxs-lookup"><span data-stu-id="ced66-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="ced66-104">**En användare**</span><span class="sxs-lookup"><span data-stu-id="ced66-104">**Single User**</span></span>
  
<span data-ttu-id="ced66-105">Set-Mailbox-Identity "Jennyin"-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="ced66-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="ced66-106">**Organisation**</span><span class="sxs-lookup"><span data-stu-id="ced66-106">**Organization**</span></span>
  
<span data-ttu-id="ced66-107">Get-Mailbox-ResultSize obegränsat-filter {en-EQ "UserMailbox"} | Set-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="ced66-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="ced66-108">Läs mer</span><span class="sxs-lookup"><span data-stu-id="ced66-108">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/enable-mailbox-auditing)
  

