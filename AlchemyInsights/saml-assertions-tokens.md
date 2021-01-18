---
title: SAML assertions (tokens)
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
- "9004341"
- "7753"
ms.openlocfilehash: 557e23da09df3ab066c2ad7c0352f5fd904b5490
ms.sourcegitcommit: a61a29dbd0382370fea0be5fa4a61c9a1a9354c7
ms.translationtype: MT
ms.contentlocale: sv-SE
ms.lasthandoff: 01/18/2021
ms.locfileid: "49885677"
---
# <a name="saml-assertions-tokens"></a><span data-ttu-id="24140-102">SAML assertions (tokens)</span><span class="sxs-lookup"><span data-stu-id="24140-102">SAML Assertions (Tokens)</span></span>

1. <span data-ttu-id="24140-103">(Security Assertion Markup Language) token är XML-representationer av anspråk.</span><span class="sxs-lookup"><span data-stu-id="24140-103">Security Assertions Markup Language (SAML) tokens are XML representations of claims.</span></span> <span data-ttu-id="24140-104">Som standard utfärdas tokens för SAML-token Windows Communication Foundation (WCF) i externa säkerhets scenarier.</span><span class="sxs-lookup"><span data-stu-id="24140-104">By default, SAML tokens Windows Communication Foundation (WCF) uses in federated security scenarios are issued tokens.</span></span> <span data-ttu-id="24140-105">Mer information finns i [SAML-token och anspråk](https://docs.microsoft.com/dotnet/framework/wcf/feature-details/saml-tokens-and-claims).</span><span class="sxs-lookup"><span data-stu-id="24140-105">For more information, see [SAML Tokens and Claims](https://docs.microsoft.com/dotnet/framework/wcf/feature-details/saml-tokens-and-claims).</span></span>
2. <span data-ttu-id="24140-106">Microsoft Identity Platform har flera typer av säkerhetstoken i bearbetningen av varje autentiseringspaket.</span><span class="sxs-lookup"><span data-stu-id="24140-106">The Microsoft identity platform emits several types of security tokens in the processing of each authentication flow.</span></span> <span data-ttu-id="24140-107">[Referens för SAML-Tokenbegäran](https://docs.microsoft.com/azure/active-directory/develop/reference-saml-tokens) beskriver format, säkerhets egenskaper och innehållet i SAML 2,0-token.</span><span class="sxs-lookup"><span data-stu-id="24140-107">[SAML token claims reference](https://docs.microsoft.com/azure/active-directory/develop/reference-saml-tokens) describes the format, security characteristics, and contents of SAML 2.0 tokens.</span></span>
3. <span data-ttu-id="24140-108">Följ vägledningen i [konfigurations bara livs längder för token i Microsoft Identity Platform](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes) för att förstå hur du konfigurerar livs längd för token.</span><span class="sxs-lookup"><span data-stu-id="24140-108">Follow the guidance in [Configurable token lifetimes in Microsoft identity platform](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes) to understand how to configure token lifetimes.</span></span>
4. <span data-ttu-id="24140-109">Följ de steg som beskrivs i [den här artikeln](https://docs.microsoft.com/azure/active-directory/manage-apps/howto-saml-token-encryption) för att förstå hur du konfigurerar Azure AD SAML token-kryptering.</span><span class="sxs-lookup"><span data-stu-id="24140-109">Follow the steps outlined in [this article](https://docs.microsoft.com/azure/active-directory/manage-apps/howto-saml-token-encryption) to understand how to configure Azure AD SAML token encryption.</span></span>
5. <span data-ttu-id="24140-110">I Azure AD kan du ställa in alternativ för certifikat signering och algoritm för certifikat signering.</span><span class="sxs-lookup"><span data-stu-id="24140-110">In Azure AD, you can set up certificate signing options and the certificate signing algorithm.</span></span> <span data-ttu-id="24140-111">Mer information finns i [Avancerade alternativ för certifikat signering i SAML-token för Galleri-appar i Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/certificate-signing-options).</span><span class="sxs-lookup"><span data-stu-id="24140-111">For more information, see [Advanced certificate signing options in the SAML token for gallery apps in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/certificate-signing-options).</span></span>
