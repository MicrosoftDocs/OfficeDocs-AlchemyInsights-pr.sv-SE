---
title: Kryptera vissa e-postmeddelanden i Office 365 automatiskt
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
ms.openlocfilehash: e4b2f4ffcacf03e145b4c6d5ff6e73a75cb7c184
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 03/11/2021
ms.locfileid: "50749446"
---
# <a name="automatically-encrypt-certain-office-365-email-messages"></a>Kryptera vissa e-postmeddelanden i Office 365 automatiskt

Du kan automatiskt kryptera meddelanden som användare skickar till vissa externa personer eller organisationer. Gör så här:

1. Välj [E-postflödesregler](https://outlook.office365.com/ecp/)i **administrationscentret för** Exchange > . 
2. Klicka på **ikonen Nytt (+)** och klicka sedan på Tillämpa meddelandekryptering och **rättighetsskydd i Office 365 för meddelanden.**
3. Ange **ett** namn på regeln i Namn, till exempel Kryptera meddelanden *som skickas till DrToniRamos@gmail.com*.
4. I **Använd den här regeln om** väljer du mottagaren > är den här **personen**. 
5. I fönstret **Välj medlemmar** väljer du namnet på den person som du vill att krypteringsregeln ska gälla för och klickar sedan på lägg **till**. 
6. När du har lagt till alla användare klickar du på **OK.**
7. Klicka på **Markera ett bredvid** Gör följande **fält.** 
8. I den **nedrullningsmenyn** för RMS-mallen väljer **du Kryptera** och klickar sedan på **OK.** (Om du inte ser det här alternativet innebär det att din plan inte innehåller automatisk kryptering. Men du kan lägga till den!)
9. Välj valfritt val (i en lista med valfria val som du kan göra i det här läget. Många av dem kan lämnas med standardinställningen för enkelhetens skull).
10. Klicka på **Spara**.

> [!IMPORTANT]
> Du kan alltid gå tillbaka och redigera regeln senare.

Mer information om hur du skapar regler för kryptering finns i [Definiera e-postflödesregler för att kryptera e-postmeddelanden i Office 365.](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)

