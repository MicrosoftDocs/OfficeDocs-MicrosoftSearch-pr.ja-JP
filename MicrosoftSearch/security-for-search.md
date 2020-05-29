---
title: Bing での Microsoft Search のセキュリティとプライバシー
ms.author: jeffkizn
author: jeffkizn
manager: parulm
ms.audience: Admin
ms.topic: article
ms.service: mssearch
localization_priority: Normal
search.appverid:
- BFB160
- MET150
- MOE150
description: Bing で Microsoft Search を使用して、承認されたユーザーに情報を提供しながら、会社のデータとエンドユーザーを保護する
ms.openlocfilehash: 1cc00a3b14b1918903c9aa34a24f13b1761b64b6
ms.sourcegitcommit: 5946fe6aad2331c023bedda8faf826c0248651f8
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/04/2020
ms.locfileid: "41711755"
---
# <a name="security-and-privacy-for-microsoft-search-in-bing"></a><span data-ttu-id="84946-103">Bing での Microsoft Search のセキュリティとプライバシー</span><span class="sxs-lookup"><span data-stu-id="84946-103">Security and Privacy for Microsoft Search in Bing</span></span>

<span data-ttu-id="84946-104">高度なプライバシーとセキュリティ対策により、Bing での Microsoft Search は、ユーザーおよび workplace データを保護します。</span><span class="sxs-lookup"><span data-stu-id="84946-104">With enhanced privacy and security measures, Microsoft Search in Bing helps protect your users and workplace data.</span></span>

## <a name="secure-by-default"></a><span data-ttu-id="84946-105">既定のセキュリティ保護</span><span class="sxs-lookup"><span data-stu-id="84946-105">Secure by default</span></span>

<span data-ttu-id="84946-106">Bing 要求での Microsoft Search は HTTPS を介して行われます。</span><span class="sxs-lookup"><span data-stu-id="84946-106">Microsoft Search in Bing requests are made over HTTPS.</span></span> <span data-ttu-id="84946-107">接続は、セキュリティを強化するためにエンドツーエンドで暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="84946-107">The connection is encrypted end-to-end for enhanced security.</span></span>
  
## <a name="authentication-and-authorization-with-azure-active-directory"></a><span data-ttu-id="84946-108">Azure Active Directory による認証と承認</span><span class="sxs-lookup"><span data-stu-id="84946-108">Authentication and authorization with Azure Active Directory</span></span>

<span data-ttu-id="84946-109">Bing での Microsoft Search の認証は、Azure Active Directory に関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="84946-109">Authentication for Microsoft Search in Bing is tied to Azure Active Directory.</span></span> <span data-ttu-id="84946-110">Microsoft Search ユーザーが Bing にアクセスすると、Bing ヘッダーには Microsoft アカウントと職場または学校のアカウントのサインインオプションが表示されます。</span><span class="sxs-lookup"><span data-stu-id="84946-110">When Microsoft Search users go to Bing, the Bing header will show sign-in options for a Microsoft account as well as a work or school account.</span></span> <span data-ttu-id="84946-111">ユーザーが対象の参加者であるかどうかを Bing が判断できない場合、ユーザーは [ [Microsoft Search の検索](https://www.bing.com/business/explore)] ページに移動し、自動的に組織のサインインページにリダイレクトされます。</span><span class="sxs-lookup"><span data-stu-id="84946-111">If Bing can't determine whether a user is an eligible participant, users can go to the [Explore Microsoft Search](https://www.bing.com/business/explore) page, where they'll be automatically redirected to your organization's sign-in page.</span></span>

<span data-ttu-id="84946-p103">ユーザーは職場または学校のアカウントを使用する場合にのみ Microsoft Search にアクセスできます。SharePoint or Outlook などの Office 365 サービスにアクセスするときに使用するのと同じ資格情報でサインインする必要があります。個人用の Microsoft アカウントを使用して Microsoft Search にサインインすることはできません。</span><span class="sxs-lookup"><span data-stu-id="84946-p103">Users can access Microsoft Search only through a work or school account. They need to sign in with the same credentials they use to access Office 365 services such as SharePoint or Outlook. A personal Microsoft account can't be used to sign in to Microsoft Search.</span></span>

## <a name="single-sign-on"></a><span data-ttu-id="84946-115">シングル サインオン</span><span class="sxs-lookup"><span data-stu-id="84946-115">Single sign-on</span></span>

<span data-ttu-id="84946-116">ユーザーが Outlook や SharePoint などの別のサービスで既に職場または学校のアカウントで認証されている場合は、同じブラウザーで Bing にアクセスすると、同じ職場または学校のアカウントに自動的にサインインします。</span><span class="sxs-lookup"><span data-stu-id="84946-116">If a user is already authenticated with their work or school account in another service, such as Outlook or SharePoint, they'll be automatically signed into the same work or school account when they go to Bing in the same browser.</span></span> <span data-ttu-id="84946-117">また、ユーザーが職場または学校のアカウントからサインアウトすると、そのユーザーは同じブラウザーの他の Microsoft Office サービスから自動的にサインアウトされます。</span><span class="sxs-lookup"><span data-stu-id="84946-117">Also, when the user signs out of their work or school account, they'll be automatically signed out from other Microsoft Office services in the same browser.</span></span>
  
## <a name="communicates-with-the-microsoft-cloud-from-the-browser"></a><span data-ttu-id="84946-118">ブラウザーから Microsoft cloud と通信する</span><span class="sxs-lookup"><span data-stu-id="84946-118">Communicates with the Microsoft cloud from the browser</span></span>

<span data-ttu-id="84946-119">ユーザーが職場または学校のアカウントでサインインすると、Bing は必要なクライアントライブラリをブラウザーにダウンロードして、Microsoft 検索結果を有効にします。</span><span class="sxs-lookup"><span data-stu-id="84946-119">When a user signs in with their work or school account, Bing will download the necessary client libraries to the browser to enable Microsoft Search results.</span></span> <span data-ttu-id="84946-120">その後、ブラウザー内のコードが検索を実行すると、Office 365 cloud を呼び出して作業の結果が得られます。</span><span class="sxs-lookup"><span data-stu-id="84946-120">Then, when they search, the in-browser code calls the Office 365 cloud to get work results.</span></span> <span data-ttu-id="84946-121">これを行うために、Microsoft Search では、SSAE 18 SOC2 Type 1 の制御目標に従って運用されている専用の API を使用します。</span><span class="sxs-lookup"><span data-stu-id="84946-121">To do this, Microsoft Search uses a dedicated API that is operated in accordance with the control objectives of SSAE 18 SOC2 Type 1.</span></span> <span data-ttu-id="84946-122">これは、作業結果自体が Office 365 コアオンラインサービスで処理されたときに、作業の結果自体が影響を受けることはないということです。</span><span class="sxs-lookup"><span data-stu-id="84946-122">This means work results and work data do not flow through Bing systems that are subject to less stringent data processing control objectives than the work results themselves are subject to when processed in Office 365 Core Online Services.</span></span>
  
## <a name="permissions"></a><span data-ttu-id="84946-123">アクセス許可</span><span class="sxs-lookup"><span data-stu-id="84946-123">Permissions</span></span>

<span data-ttu-id="84946-p106">SharePoint や OneDrive for Business などの Office 365 ワークロードから取得した作業結果は、ソースでセキュリティによるトリミングを受けます。ユーザーは、Office 365 で見たりアクセスしたりできない Word ドキュメントや PowerPoint プレゼンテーションなどのリソースを見ることはできません。ユーザーは、ユーザー自身のファイルまたはファイル作成者が SharePoint で明示的または (グループ メンバーシップなどを使用して) 暗黙的にユーザーと共有したファイルのみを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="84946-p106">Work results retrieved from Office 365 workloads such as SharePoint and OneDrive for Business are security trimmed at the source. Users can't see resources such as Word documents or PowerPoint presentations they can't see and access through Office 365. They can only see their own files and files that have been shared with them by the author explicitly or implicitly (through a group membership, for example) in SharePoint.</span></span>

## <a name="microsoft-search-in-bing-protects-workplace-searches"></a><span data-ttu-id="84946-127">Bing での Microsoft Search による workplace の検索の保護</span><span class="sxs-lookup"><span data-stu-id="84946-127">Microsoft Search in Bing protects workplace searches</span></span>

<span data-ttu-id="84946-128">ユーザーが Bing の Microsoft Search で検索クエリを入力すると、次の2つの同時検索要求が発生します。</span><span class="sxs-lookup"><span data-stu-id="84946-128">When a user enters a search query in Microsoft Search in Bing, two simultaneous search requests occur:</span></span>

- <span data-ttu-id="84946-129">組織の内部リソースの検索。</span><span class="sxs-lookup"><span data-stu-id="84946-129">A search of your organization’s internal resources.</span></span>
- <span data-ttu-id="84946-130">Bing.com からの公開結果を個別に検索します。</span><span class="sxs-lookup"><span data-stu-id="84946-130">A separate search of public results from Bing.com.</span></span>

<span data-ttu-id="84946-131">Workplace の検索では機密になる場合があるため、Microsoft Search では、Bing.com からのパブリック結果の個別の検索をどのように処理するかを記述する一連の信頼手段が実装されています。</span><span class="sxs-lookup"><span data-stu-id="84946-131">Because workplace searches might be sensitive, Microsoft Search has implemented a set of trust measures that describe how the separate search of public results from Bing.com is handled.</span></span>

### <a name="logging"></a><span data-ttu-id="84946-132">ログ記録</span><span class="sxs-lookup"><span data-stu-id="84946-132">Logging</span></span>

- <span data-ttu-id="84946-133">Bing トラフィックで Microsoft Search に関連するすべての Bing.com 検索ログは、workplace identity から切り離されます。</span><span class="sxs-lookup"><span data-stu-id="84946-133">All Bing.com search logs that pertain to Microsoft Search in Bing traffic are disassociated from your workplace identity.</span></span>
- <span data-ttu-id="84946-134">クエリが特定の組織に固有ではないという確証を得るために、制限または頻度のしきい値が満たされている場合は、プライバシーに関する[声明](https://privacy.microsoft.com/privacystatement)の「検索と人工知能」セクションの説明に従ってクエリが処理されます。</span><span class="sxs-lookup"><span data-stu-id="84946-134">If a set of restrictions or frequency thresholds are met which give us confidence that the query is not specific to a particular organization, the query will be treated as described in the Search and artificial intelligence section of the [Privacy Statement](https://privacy.microsoft.com/privacystatement).</span></span> <span data-ttu-id="84946-135">たとえば、このようなクエリを使用して、autosuggest や関連する検索などのパブリック機能をモデル化し、トレーニングします。</span><span class="sxs-lookup"><span data-stu-id="84946-135">For example, such queries will be used to model and train public features, such as autosuggest or related searches.</span></span>
- <span data-ttu-id="84946-136">一連の制限または頻度のしきい値を満たしていないクエリは、Microsoft Search 以外のパブリック トラフィックとは別に保存されます。</span><span class="sxs-lookup"><span data-stu-id="84946-136">Queries that do not meet the set of restrictions or frequency thresholds will be stored separately from public, non-Microsoft Search traffic.</span></span>

### <a name="advertising"></a><span data-ttu-id="84946-137">広告</span><span class="sxs-lookup"><span data-stu-id="84946-137">Advertising</span></span>

<span data-ttu-id="84946-138">Workplace search に関連する Bing.com に表示される広告は、検索クエリの内容にのみ関連しています。</span><span class="sxs-lookup"><span data-stu-id="84946-138">Advertising shown on Bing.com in connection with workplace searches is solely related to the content of the search queries.</span></span> <span data-ttu-id="84946-139">広告は、職場 ID に基づいてユーザーをターゲットにすることはありません。</span><span class="sxs-lookup"><span data-stu-id="84946-139">Ads are never targeted to users based on their workplace identity.</span></span>

## <a name="gdpr"></a><span data-ttu-id="84946-140">GDPR</span><span class="sxs-lookup"><span data-stu-id="84946-140">GDPR</span></span>

<span data-ttu-id="84946-141">2018年5月21日、Microsoft からの[ブログ投稿](https://blogs.microsoft.com/on-the-issues/2018/05/21/microsofts-commitment-to-gdpr-privacy-and-putting-customers-in-control-of-their-own-data/)では、GDPR 準拠に対するコミットメントが反映されています。また、microsoft が自社の GDPR コンプライアンスの義務を持つビジネスおよび組織をサポートする方法を紹介しています。</span><span class="sxs-lookup"><span data-stu-id="84946-141">The [May 21, 2018, blog post](https://blogs.microsoft.com/on-the-issues/2018/05/21/microsofts-commitment-to-gdpr-privacy-and-putting-customers-in-control-of-their-own-data/) from Microsoft reflects our commitment to GDPR compliance and how Microsoft helps businesses and organizations with their own GDPR compliance obligations.</span></span> <span data-ttu-id="84946-142">詳細については、Microsoft[セキュリティセンターの FAQ](https://www.microsoft.com/trustcenter/privacy/gdpr/gdpr-faqs)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="84946-142">You can find additional detail in the Microsoft [Trust Center FAQ](https://www.microsoft.com/trustcenter/privacy/gdpr/gdpr-faqs).</span></span>

<span data-ttu-id="84946-143">お客様の内部リソースに対して実行された Microsoft 検索クエリと返される結果は顧客データとみなされるため、[セキュリティセンターの FAQ](https://www.microsoft.com/trustcenter/privacy/gdpr/gdpr-faqs)に示されているように、記事28で概説されているプロセッサのコミットメントにも対応しています。</span><span class="sxs-lookup"><span data-stu-id="84946-143">Microsoft Search queries executed against a customer’s internal resources and results returned are considered Customer Data and, as such, also  meet the processor commitments outlined in Article 28 as reflected in the [Trust Center FAQ](https://www.microsoft.com/trustcenter/privacy/gdpr/gdpr-faqs).</span></span> <span data-ttu-id="84946-144">Microsoft Search からパブリック Bing に移行するクエリに関しては、Microsoft はデータコントローラーとしての GDPR 義務に準拠しています。</span><span class="sxs-lookup"><span data-stu-id="84946-144">With respect to queries from Microsoft Search that go to public Bing, Microsoft complies with its GDPR obligations as a data controller.</span></span>
