---
title: Skapa AIP
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "4539"
- "9002266"
ms.openlocfilehash: bef170d8e38dcc91094b95604aeb1968d5c57fca
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 09/14/2020
ms.locfileid: "47732193"
---
# <a name="creating-aip-label-policies"></a><span data-ttu-id="1aadb-102">Skapa AIP</span><span class="sxs-lookup"><span data-stu-id="1aadb-102">Creating AIP Label Policies</span></span>

<span data-ttu-id="1aadb-103">AIP-etiketter (Azure information Protection) kan användas med hela data mängden som en organisation vanligt vis skapar och lagrar från den lägsta klassificeringen av person uppgifter till den högsta klassificeringen av mycket konfidentiell information.</span><span class="sxs-lookup"><span data-stu-id="1aadb-103">Azure Information Protection(AIP) labels can be used with the full range of data that an organization typically creates and stores, from the lowest classification of personal data, to the highest classification of highly confidential data.</span></span> <span data-ttu-id="1aadb-104">Azure information Protection policy gäller för Azure information Protection (AIP) Classic-klienten och inte  [AIP Unified Labeling-klienten](https://docs.microsoft.com/azure/information-protection/rms-client/unifiedlabelingclient-version-release-history).</span><span class="sxs-lookup"><span data-stu-id="1aadb-104">Azure Information Protection Policies apply to the Azure Information Protection(AIP) classic client and not the  [AIP Unified Labeling client](https://docs.microsoft.com/azure/information-protection/rms-client/unifiedlabelingclient-version-release-history).</span></span> <span data-ttu-id="1aadb-105">Du kan konfigurera flera element i en AIP policy, till exempel:</span><span class="sxs-lookup"><span data-stu-id="1aadb-105">You can configure multiple elements in an AIP policy, including options like:</span></span>

- <span data-ttu-id="1aadb-106">Alternativ för vilken etikett gör det möjligt för administratörer eller användare att klassificera och lösenordsskydda dokument och e-postmeddelanden</span><span class="sxs-lookup"><span data-stu-id="1aadb-106">Option for which label will let administrators or user classify and protection(optional) documents and emails</span></span>
- <span data-ttu-id="1aadb-107">Alternativ för att tvinga klassificering när användare sparar dokument och skickar e-post</span><span class="sxs-lookup"><span data-stu-id="1aadb-107">Option to enforce classification when users save documents and send email</span></span>
- <span data-ttu-id="1aadb-108">Alternativ för att automatiskt märka ett e-postmeddelande, baserat på bifogade filer.</span><span class="sxs-lookup"><span data-stu-id="1aadb-108">Option to automatically label an email message, based on its attachments.</span></span>
- <span data-ttu-id="1aadb-109">Alternativ för att kontrol lera om informations skydds fältet visas i Office-program</span><span class="sxs-lookup"><span data-stu-id="1aadb-109">Option to control whether the Information Protection bar is displayed in Office applications</span></span>

<span data-ttu-id="1aadb-110">Ytterligare alternativ och information om Azure information Protection-principer finns i: [Översikt över Azure policy för informations skydd](https://docs.microsoft.com/azure/information-protection/overview-policy).</span><span class="sxs-lookup"><span data-stu-id="1aadb-110">For additional options and information on Azure Information Protection policies, see: [Overview of the Azure Information Protection policy](https://docs.microsoft.com/azure/information-protection/overview-policy).</span></span>  

<span data-ttu-id="1aadb-111">Andra användbara resurser angående AIP policys finns i:</span><span class="sxs-lookup"><span data-stu-id="1aadb-111">For other helpful resources regarding AIP policies, see:</span></span>

- [<span data-ttu-id="1aadb-112">Själv studie kurs: Konfigurera princip inställningar för Azure information Protection och skapa en ny etikett</span><span class="sxs-lookup"><span data-stu-id="1aadb-112">Tutorial: Configure Azure Information Protection policy settings and create a new label</span></span>](https://docs.microsoft.com/azure/information-protection/infoprotect-quick-start-tutorial)  
- [<span data-ttu-id="1aadb-113">Konfigurera Azure information Protection policy</span><span class="sxs-lookup"><span data-stu-id="1aadb-113">Configuring the Azure Information Protection policy</span></span>](https://docs.microsoft.com/azure/information-protection/configure-policy)  
- [<span data-ttu-id="1aadb-114">Skapa och konfigurera känslighetsetiketter och deras principer</span><span class="sxs-lookup"><span data-stu-id="1aadb-114">Create and configure sensitivity labels and their policies</span></span>](https://docs.microsoft.com/microsoft-365/compliance/create-sensitivity-labels)  
- [<span data-ttu-id="1aadb-115">Instruktions guider för vanliga scenarier som använder Azure information Protection</span><span class="sxs-lookup"><span data-stu-id="1aadb-115">How-to guides for common scenarios that use Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/how-to-guides)  
- [<span data-ttu-id="1aadb-116">Granska dokumentationen för Azure information Protection</span><span class="sxs-lookup"><span data-stu-id="1aadb-116">Review Azure Information Protection documentation</span></span>](https://docs.microsoft.com/azure/information-protection/what-is-information-protection)  
- [<span data-ttu-id="1aadb-117">Krav för Azure information Protection</span><span class="sxs-lookup"><span data-stu-id="1aadb-117">Requirements for Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/get-started/requirements)  
- [<span data-ttu-id="1aadb-118">Snabb starts själv studie kurs för Azure information Protection</span><span class="sxs-lookup"><span data-stu-id="1aadb-118">Quick start tutorial for Azure Information Protection</span></span>](https://docs.microsoft.com/azure/information-protection/get-started/infoprotect-quick-start-tutorial)  
- [<span data-ttu-id="1aadb-119">Ladda ned Azure information Protection-klient</span><span class="sxs-lookup"><span data-stu-id="1aadb-119">Download Azure Information Protection client</span></span>](https://www.microsoft.com/download/details.aspx?id=53018)