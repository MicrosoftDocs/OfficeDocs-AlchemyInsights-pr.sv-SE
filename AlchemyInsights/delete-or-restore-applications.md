---
title: Ta bort eller återställa program
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004335"
- "7737"
ms.openlocfilehash: 4df9a98644f6bc7a30f9009719c5198db591afc9
ms.sourcegitcommit: eb685eea3ab312d404d55bfd5594a5d6d68811d1
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 01/27/2021
ms.locfileid: "50015019"
---
# <a name="delete-or-restore-applications"></a><span data-ttu-id="0f8ea-102">Ta bort eller återställa program</span><span class="sxs-lookup"><span data-stu-id="0f8ea-102">Delete or restore applications</span></span>

<span data-ttu-id="0f8ea-103">**Så här tar du bort ett program från din Azure AD-klient organisation**:</span><span class="sxs-lookup"><span data-stu-id="0f8ea-103">**To delete an application from your Azure AD tenant**:</span></span>

1. <span data-ttu-id="0f8ea-104">Välj **företags program** i **Azure AD-portalen**.</span><span class="sxs-lookup"><span data-stu-id="0f8ea-104">In the **Azure AD portal**, select **Enterprise applications**.</span></span> <span data-ttu-id="0f8ea-105">Leta sedan reda på och välj det program du vill ta bort.</span><span class="sxs-lookup"><span data-stu-id="0f8ea-105">Then find and select the application you want to delete.</span></span>
2. <span data-ttu-id="0f8ea-106">I avsnittet **Hantera** i det vänstra fönstret väljer du **Egenskaper**.</span><span class="sxs-lookup"><span data-stu-id="0f8ea-106">In the **Manage** section in the left pane, select **Properties**.</span></span>
3. <span data-ttu-id="0f8ea-107">Välj **ta bort** och välj sedan **Ja** för att bekräfta att du vill ta bort appen från din Azure AD-klient.</span><span class="sxs-lookup"><span data-stu-id="0f8ea-107">Select **Delete**, and then select **Yes** to confirm you want to delete the app from your Azure AD tenant.</span></span>

<span data-ttu-id="0f8ea-108">Mer information om hur du tar bort ett program finns i [snabb start: ta bort ett program från din Azure Active Directory-klient organisation](https://docs.microsoft.com/azure/active-directory/manage-apps/delete-application-portal#delete-an-application-from-your-azure-ad-tenant).</span><span class="sxs-lookup"><span data-stu-id="0f8ea-108">For more information on how to delete an app, see [Quickstart: Delete an application from your Azure Active Directory (Azure AD) tenant](https://docs.microsoft.com/azure/active-directory/manage-apps/delete-application-portal#delete-an-application-from-your-azure-ad-tenant).</span></span>

<span data-ttu-id="0f8ea-109">I PowerShell tar [Remove-AzureADApplicationProxyApplication](https://docs.microsoft.com/powershell/module/azuread/remove-azureadapplicationproxyapplication) cmdlet bort programproxy-konfigurationer från ett visst program i Azure Active Directory och kan ta bort programmet helt och hållet.</span><span class="sxs-lookup"><span data-stu-id="0f8ea-109">In PowerShell, the [Remove-AzureADApplicationProxyApplication](https://docs.microsoft.com/powershell/module/azuread/remove-azureadapplicationproxyapplication) cmdlet removes Application Proxy configurations from a specific application in Azure Active Directory, and can delete the application completely if specified.</span></span>

<span data-ttu-id="0f8ea-110">Du kan **återställa ett borttaget program** med PowerShell.</span><span class="sxs-lookup"><span data-stu-id="0f8ea-110">You can **restore a deleted application** using PowerShell.</span></span> <span data-ttu-id="0f8ea-111">När du har identifierat det program du vill återställa kan du återställa det med hjälp av [restore-AzureADDeletedApplication](https://docs.microsoft.com/powershell/module/azuread/restore-azureaddeletedapplication).</span><span class="sxs-lookup"><span data-stu-id="0f8ea-111">Once the application you want to restore has been identified, you can restore it using [Restore-AzureADDeletedApplication](https://docs.microsoft.com/powershell/module/azuread/restore-azureaddeletedapplication).</span></span>
