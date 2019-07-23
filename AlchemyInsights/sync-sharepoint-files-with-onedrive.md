---
title: Felsök ”Öppna med Utforskaren”-problem i SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 5/17/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 5ad2f1f2-9650-4eb0-b4fa-2f52a09f535a
ms.openlocfilehash: 13149d288336b487441c66521b32406e408911fd
ms.sourcegitcommit: f81c56dd4ae7cb2eedc383dd671b9012f3089286
ms.translationtype: HT
ms.contentlocale: sv-SE
ms.lasthandoff: 07/19/2019
ms.locfileid: "35803056"
---
# <a name="troubleshoot-open-with-explorer-issues-in-sharepoint-online"></a><span data-ttu-id="43a71-102">Felsök ”Öppna med Utforskaren”-problem i Sharepoint Online</span><span class="sxs-lookup"><span data-stu-id="43a71-102">Troubleshoot “Open with Explorer” issues in Sharepoint Online</span></span>

<span data-ttu-id="43a71-103">Kommandot Öppna med Utforskaren öppnar en lokal instans av Utforskaren som visar mappstrukturen på den server som är värd för SharePoint-webbplatsen.</span><span class="sxs-lookup"><span data-stu-id="43a71-103">The Open with Explorer command opens a local instance of Windows Explorer that displays the folder structure on the server that hosts the SharePoint site.</span></span> <span data-ttu-id="43a71-104">Vi rekommenderar att du [synkroniserar SharePoint-filer med den nya OneDrive-synkroniseringsklienten](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88)</a> som tillhandahåller [filer på begäran](https://support.office.com/article/learn-about-onedrive-files-on-demand-0e6860d3-d9f3-4971-b321-7092438fb38e), eftersom det ger lokal åtkomst till dina filer och ger bästa möjliga prestanda.</span><span class="sxs-lookup"><span data-stu-id="43a71-104">This being said, we recommend [syncing SharePoint files with the new OneDrive sync client](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88)</a> which provides [Files On-Demand](https://support.office.com/article/learn-about-onedrive-files-on-demand-0e6860d3-d9f3-4971-b321-7092438fb38e) because it provides local access to your files and offers the best performance.</span></span>


<span data-ttu-id="43a71-105">Om du väljer att använda Utforskarvyn i stället för den nya OneDrive-synkroniseringsklienten ska du vara noga med att följa anvisningarna och metodtipsen i artiklarna nedan:</span><span class="sxs-lookup"><span data-stu-id="43a71-105">If you chose to use Explorer view instead of using the new OneDrive sync client, make sure you follow the steps and best practices in the following articles:</span></span>

- [<span data-ttu-id="43a71-106">Använda kommandot "Öppna med Utforskaren" för felsökning av problem i SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="43a71-106">How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online</span></span>](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4)

- <span data-ttu-id="43a71-107">[Kopiera eller flytta biblioteksfiler med hjälp av Öppna med Utforskaren](https://support.office.com/article/copy-or-move-library-files-by-using-open-with-explorer-aaee7bfb-e2a1-42ee-8fc0-bcc0754f04d2)</span><span class="sxs-lookup"><span data-stu-id="43a71-107">See [Video: Copy or move library files by using Open with Explorer](https://support.office.com/article/copy-or-move-library-files-by-using-open-with-explorer-aaee7bfb-e2a1-42ee-8fc0-bcc0754f04d2).</span></span>

> [!Note]  
> <span data-ttu-id="43a71-108">Knappen **Öppna med Utforskaren** visas inte i den nya biblioteksvyn.</span><span class="sxs-lookup"><span data-stu-id="43a71-108">The **Open with Explorer** button doesn't appear in the new library experience.</span></span> <span data-ttu-id="43a71-109">Välj listrutan **Visa** i det övre högra hörnet (namnet på listrutan ändras beroende på aktuell vy) och välj sedan **Visa i Utforskaren**.</span><span class="sxs-lookup"><span data-stu-id="43a71-109">Select the **View** drop-down in the upper right (the name of the drop-down changes depending on your current view), and then select **View in File Explorer**.</span></span>

 ><span data-ttu-id="43a71-110">Öppna med Utforskaren i SharePoint använder ActiveX-kontroller, så det stöds endast i Internet Explorer 10 eller 11.</span><span class="sxs-lookup"><span data-stu-id="43a71-110">SharePoint Open with Explorer uses ActiveX controls, so it's only supported in Internet Explorer 10 or 11.</span></span> <span data-ttu-id="43a71-111">Öppna med Utforskaren fungerar inte i Windows med Microsoft Edge, Google Chrome, Mozilla Firefox eller på Mac-plattformen.</span><span class="sxs-lookup"><span data-stu-id="43a71-111">Open with Explorer doesn't work in Windows with Microsoft Edge, Google Chrome, Mozilla Firefox, or on the Mac platform.</span></span> <span data-ttu-id="43a71-112">På grund av detta kan alternativet Utforskarvy vara nedtonat.</span><span class="sxs-lookup"><span data-stu-id="43a71-112">Due to this reason, the Explorer View option may be grayed out.</span></span>

> - <span data-ttu-id="43a71-113">[Varför knappar på SharePoints menyflikar inte är tillgängliga](https://support.office.com/article/Why-SharePoint-ribbon-buttons-are-unavailable-48b0939a-2efb-4e79-b5e8-b2c4cb5d04ca).</span><span class="sxs-lookup"><span data-stu-id="43a71-113">[Why SharePoint ribbon buttons are unavailable or grayed out](https://support.office.com/article/Why-SharePoint-ribbon-buttons-are-unavailable-48b0939a-2efb-4e79-b5e8-b2c4cb5d04ca).</span></span>
  

