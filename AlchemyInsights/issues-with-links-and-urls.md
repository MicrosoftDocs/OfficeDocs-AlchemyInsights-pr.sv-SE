---
title: 'Problem med länkar och URL: er'
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/15/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7720"
- "9004329"
ms.openlocfilehash: 24885d873d6471a72ae66581ad1ceb0a19b664f7
ms.sourcegitcommit: 029c4697b77ce996d41ca74c4fa86de1bb84bd99
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 01/25/2021
ms.locfileid: "49974755"
---
# <a name="issues-with-links-and-urls"></a><span data-ttu-id="1070c-102">Problem med länkar och URL: er</span><span class="sxs-lookup"><span data-stu-id="1070c-102">Issues with links and URLs</span></span>

<span data-ttu-id="1070c-103">Omdirigera URI/Reply URL-adresser (båda uttrycken är utbytbara) är URL-adresser som används av Microsoft Identity Platform för att returnera appen-begärda token.</span><span class="sxs-lookup"><span data-stu-id="1070c-103">Redirect URI/reply URLs (both expressions are interchangeable) are the URLs used by the Microsoft identity platform to return app-requested tokens.</span></span> <span data-ttu-id="1070c-104">Information om dessa URL-adresser finns i följande artiklar:</span><span class="sxs-lookup"><span data-stu-id="1070c-104">For information on these URLs, see the following articles:</span></span>

- <span data-ttu-id="1070c-105">[Autentiseringsscheman och program scenarier](https://docs.microsoft.com/azure/active-directory/develop/authentication-flows-app-scenarios) -information om hur du omdirigerar URI: er på **registrerings** sidan för varje scenario.</span><span class="sxs-lookup"><span data-stu-id="1070c-105">[Authentication flows and application scenarios](https://docs.microsoft.com/azure/active-directory/develop/authentication-flows-app-scenarios) - Information about the redirect URIs in the **App registration** page for each scenario.</span></span>
- [<span data-ttu-id="1070c-106">Omdirigera begränsningar och begränsningar för URI/Reply URL</span><span class="sxs-lookup"><span data-stu-id="1070c-106">Redirect URI/reply URL restrictions and limitations</span></span>](https://docs.microsoft.com/azure/active-directory/develop/reply-url)

<span data-ttu-id="1070c-107">**Jag vet inte hur jag registrerar rätt omdirigerande URI/Reply URL för mitt program**</span><span class="sxs-lookup"><span data-stu-id="1070c-107">**I don't know how to register the right redirect URI / reply URL for my app**</span></span>

<span data-ttu-id="1070c-108">När du loggar in med programmet du utvecklar, om dialog rutan inloggning visar **AADSTS50011: svars-URL-adressen som angavs i begäran inte stämmer överens med svar på URL- <your app ID> adresser som har kon figurer ATS för programmet**, måste du lägga till i din program registrering, omdirigerings-URI som används i Tokenbegäran till Microsoft Identity Platform.</span><span class="sxs-lookup"><span data-stu-id="1070c-108">When you sign in with the application you are developing, if the sign-in dialog displays **AADSTS50011: The reply url specified in the request does not match the reply urls configured for the application <your app ID>**, you'll need to add to your application registration, the redirect URI that your code used in the token request to the Microsoft identity platform.</span></span>

<span data-ttu-id="1070c-109">Om du vill lägga till en svars-URL går du till fliken **Verifiera** på din **program registrerings** sida i Azure-portalen och lägger till en post i avsnittet **omdirigera URI: er** .</span><span class="sxs-lookup"><span data-stu-id="1070c-109">To add a reply URL, go to the **Authentication** tab in your **application registration** page in the Azure portal and add an entry in the **Redirect URIs** section.</span></span> <span data-ttu-id="1070c-110">Omdirigera URI: er skrivs (webb eller mobil/stationärt).</span><span class="sxs-lookup"><span data-stu-id="1070c-110">Redirect URIs are typed (Web or mobile/desktop).</span></span> <span data-ttu-id="1070c-111">Det värde du behöver ange beror på vilken typ av program du skapar, enligt beskrivningen nedan:</span><span class="sxs-lookup"><span data-stu-id="1070c-111">The value you need to enter depends on the type of application you're building, as described below:</span></span>

- <span data-ttu-id="1070c-112">För program med en enda sida och webbappar är svars-URL-adressen en URL-adress i programmet.</span><span class="sxs-lookup"><span data-stu-id="1070c-112">For single-page applications and web apps, the reply URL is a URL in your application.</span></span> <span data-ttu-id="1070c-113">Se [program registrering](https://docs.microsoft.com/azure/active-directory/develop/scenario-spa-app-registration#register-a-redirect-uri) för en sida eller [Registrera en Web App-app med Azure Portal](https://docs.microsoft.com/azure/active-directory/develop/scenario-web-app-sign-user-app-registration?tabs=aspnetcore#register-an-app-using-azure-portal)</span><span class="sxs-lookup"><span data-stu-id="1070c-113">See [Single-page application registration](https://docs.microsoft.com/azure/active-directory/develop/scenario-spa-app-registration#register-a-redirect-uri) or [Register a web app app using Azure portal](https://docs.microsoft.com/azure/active-directory/develop/scenario-web-app-sign-user-app-registration?tabs=aspnetcore#register-an-app-using-azure-portal)</span></span>
- <span data-ttu-id="1070c-114">För skrivbordsappar är det värde som du måste välja beror på:</span><span class="sxs-lookup"><span data-stu-id="1070c-114">For desktop apps, the value that you need to choose depends on:</span></span>
    - <span data-ttu-id="1070c-115">plattformen (MacOS skiljer sig från Windows eller Linux)</span><span class="sxs-lookup"><span data-stu-id="1070c-115">the platform (MacOS is different from Windows or Linux)</span></span>
    - <span data-ttu-id="1070c-116">hur du erhåller token (interaktivt, med enhets kod flöde, integrerad Windows-autentisering [IWA] eller med användar namn/lösen ord).</span><span class="sxs-lookup"><span data-stu-id="1070c-116">the way you acquire the token (interactively, with device code flow, with Integrated Windows Authentication [IWA] or with username/password).</span></span>
    <span data-ttu-id="1070c-117">Mer information finns i [Desktop-appar-program registrering-omdirigera URI](https://docs.microsoft.com/azure/active-directory/develop/scenario-desktop-app-registration#redirect-uris)</span><span class="sxs-lookup"><span data-stu-id="1070c-117">For details, see [Desktop apps - App registration - Redirect URi](https://docs.microsoft.com/azure/active-directory/develop/scenario-desktop-app-registration#redirect-uris)</span></span>
- <span data-ttu-id="1070c-118">För mobila program beror omdirigerings-URI på:</span><span class="sxs-lookup"><span data-stu-id="1070c-118">For mobile applications, the redirect URI depends on:</span></span>
    - <span data-ttu-id="1070c-119">plattformen (iOS/Android/UWP)</span><span class="sxs-lookup"><span data-stu-id="1070c-119">the platform (iOS/Android/UWP)</span></span>
    - <span data-ttu-id="1070c-120">informationen som används för att skapa din app, till exempel paket-ID i iOS, samt paket namnet och signatur-hashen för Android din app-registrering i Azure-portalen hjälper dig.</span><span class="sxs-lookup"><span data-stu-id="1070c-120">the information used to build your app, such as the bundle ID in iOS, and the package name and signature hash on Android The Azure portal app registration will help you.</span></span> <span data-ttu-id="1070c-121">För mer information, se [Platform Configuration och omdirigera URI: er](https://docs.microsoft.com/azure/active-directory/develop/scenario-mobile-app-registration#platform-configuration-and-redirect-uris).</span><span class="sxs-lookup"><span data-stu-id="1070c-121">For details, see [Platform configuration and redirect URIs](https://docs.microsoft.com/azure/active-directory/develop/scenario-mobile-app-registration#platform-configuration-and-redirect-uris).</span></span>

> [!NOTE]
> <span data-ttu-id="1070c-122">Webb-API: er och vissa av de tysta sätten att förvärva token (IWA och username) kräver ingen omdirigerings-URI.</span><span class="sxs-lookup"><span data-stu-id="1070c-122">Web APIs and some of the silent ways of acquiring tokens (IWA and username/password) don't require a redirect URI.</span></span>

<span data-ttu-id="1070c-123">**Jag har distribuerat mitt webb program och när jag testar den distribuerade appen får jag ett svar på URL-matchningsfel**</span><span class="sxs-lookup"><span data-stu-id="1070c-123">**I've deployed my web application and when I test the deployed app, I get a reply url mismatch message**</span></span>

<span data-ttu-id="1070c-124">Lägg till omdirigera URI: er för alla platser där du distribuerar webb programmet.</span><span class="sxs-lookup"><span data-stu-id="1070c-124">Add redirect URIs for all the locations at which you are deploying your web application.</span></span> <span data-ttu-id="1070c-125">Mer information finns i [Registrera en Web App-app med Azure Portal](https://docs.microsoft.com/azure/active-directory/develop/scenario-web-app-sign-user-app-registration).</span><span class="sxs-lookup"><span data-stu-id="1070c-125">For more information, see [Register a web app app using Azure portal](https://docs.microsoft.com/azure/active-directory/develop/scenario-web-app-sign-user-app-registration).</span></span>

> [!NOTE]
> <span data-ttu-id="1070c-126">Lägg till Omdirigerad URI för en plats direkt efter att du har distribuerat programmet på den platsen.</span><span class="sxs-lookup"><span data-stu-id="1070c-126">Add redirect URI for a location immediately after you have deployed the application at that location.</span></span>

<span data-ttu-id="1070c-127">**Jag kan inte registrera många svars-URL: er**</span><span class="sxs-lookup"><span data-stu-id="1070c-127">**I can't register enough reply URLs**</span></span>

<span data-ttu-id="1070c-128">Du är en ISV och har en eller flera omdirigerings-URI: er till alla kunder.</span><span class="sxs-lookup"><span data-stu-id="1070c-128">You're an ISV and have one or several redirect URIs for every customer of yours.</span></span> <span data-ttu-id="1070c-129">Du vill migrera från ADAL/Azure AD v 1.0 till MSAL/Microsofts identitets plattform och sedan trycka [maximalt antal omdirigerings-URI: er](https://docs.microsoft.com/azure/active-directory/develop/reply-url#maximum-number-of-redirect-uris).</span><span class="sxs-lookup"><span data-stu-id="1070c-129">You want to migrate from ADAL/Azure AD v1.0 to MSAL/the Microsoft identity platform and you hit the [maximum number of redirect URIs](https://docs.microsoft.com/azure/active-directory/develop/reply-url#maximum-number-of-redirect-uris).</span></span> <span data-ttu-id="1070c-130">Lös problemet genom att [lägga till omdirigera URI: er till tjänstens huvud namn](https://docs.microsoft.com/azure/active-directory/develop/reply-url#add-redirect-uris-to-service-principals) som motsvarar var och en av dina kunder.</span><span class="sxs-lookup"><span data-stu-id="1070c-130">To resolve this, [add redirect URIs to service principals](https://docs.microsoft.com/azure/active-directory/develop/reply-url#add-redirect-uris-to-service-principals) that correspond to each of your customers.</span></span>
