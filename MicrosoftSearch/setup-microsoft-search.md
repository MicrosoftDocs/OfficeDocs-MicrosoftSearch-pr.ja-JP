---
title: Microsoft Search のセットアップ
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
description: Microsoft Search を初めてセットアップする。
ms.openlocfilehash: 37b5f33fe7b49a11c4558debac5b9acae4cc40cd
ms.sourcegitcommit: aa48b6510883e1617aa13a50b1056fb149c47586
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/15/2020
ms.locfileid: "44256639"
---
# <a name="set-up-microsoft-search"></a><span data-ttu-id="1e3a8-103">Microsoft Search のセットアップ</span><span class="sxs-lookup"><span data-stu-id="1e3a8-103">Set up Microsoft Search</span></span>

<span data-ttu-id="1e3a8-104">Microsoft Search では、ユーザーフレンドリなインターフェイスを使用して、ファイルやドキュメント、内部サイトとビジネスツール、ユーザーとグループ、場所と方法、会話、および回答などの情報を検索できます。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-104">Microsoft Search provides a user-friendly interface to help users find information like files and documents, internal sites and business tools, people and groups, locations and directions, conversations and answers.</span></span> <span data-ttu-id="1e3a8-105">これは、電子メール、ファイル、SharePoint ファイル、OneDrive コンテンツ、その他の共有リソースなど、すべてのデータソースに安全にアクセスすることによって行われます。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-105">It does this by securely accessing all data sources, including emails, files, SharePoint files, OneDrive content, and other shared resources as well.</span></span> <span data-ttu-id="1e3a8-106">Bing で Microsoft Search を使用すると、インターネットからも検索結果を取得できます。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-106">With Microsoft Search in Bing you can get search results from the internet as well.</span></span>

<span data-ttu-id="1e3a8-107">Microsoft Search の機能の詳細については、「[Microsoft Search の概要](overview-microsoft-search.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-107">To learn more about Microsoft Search features, see [Microsoft Search Overview](overview-microsoft-search.md).</span></span>

## <a name="get-started"></a><span data-ttu-id="1e3a8-108">はじめに</span><span class="sxs-lookup"><span data-stu-id="1e3a8-108">Get Started</span></span>

<span data-ttu-id="1e3a8-109">Microsoft Search は Microsoft 365 の一部であり、この機能をサポートしているすべての Microsoft アプリに対して既定で有効になっています。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-109">Microsoft Search is turned on by default for all Microsoft apps that supports it, as a part of Microsoft 365.</span></span> <span data-ttu-id="1e3a8-110">セットアップは必要ありませんが、いくつかの基本的な管理タスクを通じて Microsoft 検索の全体的な機能を向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-110">There is no setup required, but you can improve the overall Microsoft Search experience through some basic administrative tasks.</span></span>

<span data-ttu-id="1e3a8-111">Microsoft Search の管理は、Microsoft 365 管理センターから行います。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-111">You manage Microsoft Search from Microsoft 365 admin center.</span></span>

1. <span data-ttu-id="1e3a8-112">Microsoft 365 管理センターで、[**設定**]  >  [**Microsoft Search**] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-112">In Microsoft 365 admin center, go to **Settings** > **Microsoft Search**.</span></span>

<span data-ttu-id="1e3a8-113">**注:** [**設定**] の下に [Microsoft Search] が表示されない場合は、管理センター ページの右上隅にある [**プレビューを試す**] スイッチを有効にしてください。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-113">**Note:** If you are NOT seeing Microsoft Search under **Settings**, turn on the **Try the preview** switch in the right top corner of any admin center page.</span></span>

<span data-ttu-id="1e3a8-114">管理者として、効率的でユーザー フレンドリな Microsoft Search の操作性を組織内で実現するために、いくつかの点を考慮する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-114">As an admin you should consider a few things that can make the Microsoft Search experience efficient and user friendly in your organization.</span></span>

## <a name="step-1-assign-search-admin-and-search-editor"></a><span data-ttu-id="1e3a8-115">手順 1: 検索管理者と検索エディターを割り当てる</span><span class="sxs-lookup"><span data-stu-id="1e3a8-115">Step 1: Assign Search admin and Search editor</span></span>

<span data-ttu-id="1e3a8-116">Microsoft Search で組織の検索設定と検索コンテンツを管理するには、ユーザーに次の役割を割り当てます。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-116">In Microsoft Search, you can manage your organization’s search settings and content by assigning these roles to users:</span></span>

1. <span data-ttu-id="1e3a8-117">**Search 管理者:** この役割では、検索結果のコンテンツを作成したり管理したりして、組織内の検索結果を向上させるためのクエリ設定を定義できます。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-117">**Search admin:** This role can create and manage search result content and define query settings for improved search results within the organization.</span></span> <span data-ttu-id="1e3a8-118">Search 管理者は、Microsoft Search の構成を管理し、Search エディターが実行する権限を持つコンテンツ管理タスクをすべて実行できます。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-118">Search admin manages the Microsoft Search configuration and can perform all of the content-management tasks a Search editor can.</span></span>
2. <span data-ttu-id="1e3a8-119">**Search エディター:** Microsoft 365 管理センターで Microsoft Search のコンテンツを作成、管理、および削除します。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-119">**Search editor:** Creates, manages, and deletes content for Microsoft Search in the Microsoft 365 admin center.</span></span> <span data-ttu-id="1e3a8-120">この役割には、よく寄せられる質問や回答、重要な場所や位置、頻繁に検索および使用されるサイトやアプリなどの編集コンテンツを作成および管理する権限があります。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-120">This role can create and manage editorial content, such as frequently asked questions and answers, important places and locations, frequently searched and used sites and apps.</span></span>

<span data-ttu-id="1e3a8-121">現時点では、検索管理者と検索エディターの役割は、全体管理者が割り当てる必要があります。詳細については、「[管理者の役割を割り当てる](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles?view=o365-worldwide)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-121">Currently, the Search admin and Search editor roles must be assigned by a global admin. For more information, see [Assign admin roles](https://docs.microsoft.com/office365/admin/add-users/assign-admin-roles?view=o365-worldwide).</span></span>

<span data-ttu-id="1e3a8-122">Search 管理者は、エンド ユーザーの検索エクスペリエンスに直接影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-122">Search administrators directly influence the search experience for end users.</span></span> <span data-ttu-id="1e3a8-123">これには、ユーザーに表示する結果の種類の選択が含まれます。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-123">This includes choosing the types of results you want to surface to your users.</span></span> <span data-ttu-id="1e3a8-124">ユーザーが組織内で検索するさまざまなトピックに対して、信頼できるコンテンツを 1 人で選択して作成するのは難しい場合があります。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-124">It may be difficult for one person to choose and create authoritative content on many different topics that users search for in an organization.</span></span> <span data-ttu-id="1e3a8-125">内容領域専門家 (SME) や他のユーザーを検索エディターとして追加して、その専門知識や知見を活用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-125">We recommend that you leverage the expertise and knowledge of subject matter experts (SME) and other users by adding them as Search editors.</span></span>

## <a name="step-2-create-answers"></a><span data-ttu-id="1e3a8-126">手順 2: 回答を作成する</span><span class="sxs-lookup"><span data-stu-id="1e3a8-126">Step 2: Create answers</span></span>

<span data-ttu-id="1e3a8-127">Microsoft Search では、ユーザーのために堅牢な検索環境を構築するために使用できるツールを管理者に提供しています。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-127">Microsoft Search provides administrators with tools that they can use to build a robust search experience for their users.</span></span> <span data-ttu-id="1e3a8-128">Microsoft Search では、管理者は3つの異なる検索コンテンツを使用して、より良い検索機能を提供し、コンテンツの "findability" を改善することができます。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-128">In Microsoft Search, administrators have three different search contents that they can create for a better search experience and to improve the "findability" of content:</span></span>

<span data-ttu-id="1e3a8-129">ブックマークは、最も一般的に使用される応答の種類です。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-129">Bookmarks are the most commonly used answer type.</span></span> <span data-ttu-id="1e3a8-130">ユーザーのクエリに対して最適な結果を検索結果の上位に上げ、ユーザーが探しているものを見つけやすいようにします。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-130">They promote the best possible results for your users’ queries to the top of the search results and make it easy for your users to find what they are looking for.</span></span>
<span data-ttu-id="1e3a8-131">すべてのユーザーが利用できる情報コンテンツ。たとえば、会社に関する情報、Windows および Office アプリのヘルプなど。通常、組織内のユーザーが日常業務で検索するコンテンツ。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-131">Informational content that is available for everyone; for example, information about the company, help for Windows and Office apps, etc. Content that people in the organization generally search for in their day-to-day work.</span></span> <span data-ttu-id="1e3a8-132">従業員の福利厚生、時間と経費のレポート、発注書の発行、IT サービスからのヘルプの入手など、業務関連の一般的な検索項目です。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-132">Common work-related searches include employee benefits, time and expense reporting, submitting purchase orders, and getting help from IT services.</span></span>

<span data-ttu-id="1e3a8-133">回答を作成および管理する方法については、「[コンテンツを計画](plan-your-content.md)する」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-133">For creating and managing answers, see [Plan your content](plan-your-content.md).</span></span>

## <a name="next-steps"></a><span data-ttu-id="1e3a8-134">次のステップ</span><span class="sxs-lookup"><span data-stu-id="1e3a8-134">Next steps</span></span>

<span data-ttu-id="1e3a8-135">ユーザーが Microsoft Search を使用する方法の詳細については、次の記事を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1e3a8-135">If you'd like to learn more about how your users will use Microsoft Search, see the following articles:</span></span>

- [<span data-ttu-id="1e3a8-136">Office の Microsoft Search で必要な情報を見つける</span><span class="sxs-lookup"><span data-stu-id="1e3a8-136">Find what you need with Microsoft Search in Office</span></span>](https://support.office.com/article/find-what-you-need-with-microsoft-search-in-office-2457d4d8-48a8-4ad4-ab89-5a0657aa8446)
- [<span data-ttu-id="1e3a8-137">Office 365 トレーニング センター</span><span class="sxs-lookup"><span data-stu-id="1e3a8-137">Office 365 Training Center</span></span>](https://support.office.com/office-training-center)
- [<span data-ttu-id="1e3a8-138">Microsoft Search センター</span><span class="sxs-lookup"><span data-stu-id="1e3a8-138">Microsoft Search Center</span></span>](https://support.office.com/article/-working-title-microsoft-search-center-b8bf5a2c-7515-40a9-9a6a-b8ed382c86bc)
