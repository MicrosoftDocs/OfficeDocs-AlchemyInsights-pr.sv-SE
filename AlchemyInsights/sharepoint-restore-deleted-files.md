---
title: Återställa en borttagen fil eller mapp
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: ba1573a5-9f44-482b-8082-6f648f169449
ms.openlocfilehash: 1672f425719597b93b8ef05865797714c3b19e42
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 06/07/2019
ms.locfileid: "34758923"
---
# <a name="restore-a-deleted-file-or-folder"></a><span data-ttu-id="52c37-102">Återställa en borttagen fil eller mapp</span><span class="sxs-lookup"><span data-stu-id="52c37-102">Restore a deleted file or folder</span></span>

<span data-ttu-id="52c37-103">SharePoint Online behåller säkerhetskopior av allt innehåll för 14 ytterligare dagar utöver faktiska borttagning.</span><span class="sxs-lookup"><span data-stu-id="52c37-103">SharePoint Online retains backups of all content for 14 additional days beyond actual deletion.</span></span> <span data-ttu-id="52c37-104">Om innehållet inte kan återställas via Papperskorgen eller återställa filer, kan en administratör kontakta Microsoft Support för att få en återställningspunkt som helst i fönstret 14 dagar.</span><span class="sxs-lookup"><span data-stu-id="52c37-104">If content cannot be restored via the Recycle Bin or Files Restore, an administrator can contact Microsoft Support to request a restore any time inside the 14 day window.</span></span> <span data-ttu-id="52c37-105">Återställningar från säkerhetskopior kan bara utföras för webbplatssamlingar eller underwebbplatser, inte för enskilda filer, listor eller bibliotek.</span><span class="sxs-lookup"><span data-stu-id="52c37-105">Restorations from backups can only be completed for site collections or sub-sites, not for specific files, lists, or libraries.</span></span>

<span data-ttu-id="52c37-106">När du tar bort ett objekt eller en webbplats från Sharepoint är inte den omedelbart bort.</span><span class="sxs-lookup"><span data-stu-id="52c37-106">When you delete an item or site from Sharepoint, it isn't immediately removed.</span></span> <span data-ttu-id="52c37-107">Borttagna objekt går du till papperskorgen för en viss tidsperiod.</span><span class="sxs-lookup"><span data-stu-id="52c37-107">Deleted items go into the recycle bin for a period of time.</span></span> <span data-ttu-id="52c37-108">Under den tiden kan du återställa de objekt som du tagit bort till deras ursprungliga plats.</span><span class="sxs-lookup"><span data-stu-id="52c37-108">During that time, you can restore the items you deleted to their original location.</span></span> <span data-ttu-id="52c37-109">Mer information finns på länkarna nedan.</span><span class="sxs-lookup"><span data-stu-id="52c37-109">For more information, please visit the links below.</span></span>

<span data-ttu-id="52c37-110">[Återställa objekt i Papperskorgen på SharePoint-webbplatsen](https://support.office.com/article/restore-deleted-items-from-the-site-collection-recycle-bin-5fa924ee-16d7-487b-9a0a-021b9062d14b?ui=en-US&amp;rs=en-US&amp;ad=US).</span><span class="sxs-lookup"><span data-stu-id="52c37-110">[Restore items in the Recycle Bin of a SharePoint site](https://support.office.com/article/restore-deleted-items-from-the-site-collection-recycle-bin-5fa924ee-16d7-487b-9a0a-021b9062d14b?ui=en-US&amp;rs=en-US&amp;ad=US).</span></span>

[<span data-ttu-id="52c37-111">Återställa borttagna filer eller mappar i OneDrive</span><span class="sxs-lookup"><span data-stu-id="52c37-111">Restore deleted files or folders in OneDrive</span></span>](https://support.office.com/article/Restore-deleted-files-or-folders-in-OneDrive-949ada80-0026-4db3-a953-c99083e6a84f)

[<span data-ttu-id="52c37-112">Återställa borttagna webbplatssamlingen (inklusive grupp, kommunikation och andra webbplatser)</span><span class="sxs-lookup"><span data-stu-id="52c37-112">Restore a deleted site collection (Including group, communication and other sites)</span></span>](https://docs.microsoft.com/sharepoint/restore-deleted-site-collection)

[<span data-ttu-id="52c37-113">Återställa en borttagen OneDrive webbplats</span><span class="sxs-lookup"><span data-stu-id="52c37-113">Restore a deleted OneDrive site</span></span>](https://docs.microsoft.com/onedrive/restore-deleted-onedrive)

<span data-ttu-id="52c37-114">För återvinning lagerplats massåtgärder, kan administratörer kan du använda [Sharepoint Online PNP](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps).</span><span class="sxs-lookup"><span data-stu-id="52c37-114">For bulk recycle bin actions, admins may consider using [Sharepoint Online PNP](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps).</span></span>

<span data-ttu-id="52c37-115">**Funktionen för återställning av filer**</span><span class="sxs-lookup"><span data-stu-id="52c37-115">**Files Restore feature**</span></span>

<span data-ttu-id="52c37-116">Om partier av OneDrive eller SharePoint-filer få bort, över, skadad eller infekterad med skadlig kod, kan du återställa hela biblioteket OneDrive eller SharePoint till en tidigare tidpunkt med hjälp av funktionen Återställ filer.</span><span class="sxs-lookup"><span data-stu-id="52c37-116">If lots of your OneDrive or SharePoint files get deleted, overwritten, corrupted, or infected by malware, you can restore your entire OneDrive or SharePoint library to a previous time using the files restore feature.</span></span>

[<span data-ttu-id="52c37-117">Återställa ett bibliotek med OneDrive</span><span class="sxs-lookup"><span data-stu-id="52c37-117">Restore a OneDrive library</span></span>](https://support.office.com/article/restore-your-onedrive-fa231298-759d-41cf-bcd0-25ac53eb8a15)

[<span data-ttu-id="52c37-118">Återställa ett dokumentbibliotek</span><span class="sxs-lookup"><span data-stu-id="52c37-118">Restore a Document library</span></span>](https://support.office.com/article/restore-a-document-library-317791c3-8bd0-4dfd-8254-3ca90883d39a?ui=en-US&amp;rs=en-US&amp;ad=US.)
