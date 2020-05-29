---
title: Microsoft 検索ページをカスタマイズする
ms.author: jypal6
author: jypal
manager: jeffkizn
ms.audience: Admin
ms.topic: article
ms.service: mssearch
localization_priority: Normal
search.appverid:
- BFB160
- MET150
- MOE150
description: 検索垂直を追加して検索結果をカスタマイズする
ms.openlocfilehash: 97a43e057297712baef3bf91ac8b3b2fa80975ac
ms.sourcegitcommit: c22e8c3dcc53857da677db98a1a2b7d5ca2c6170
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/04/2020
ms.locfileid: "41721770"
---
# <a name="customize-the-search-results-page"></a><span data-ttu-id="1e04e-103">検索結果ページをカスタマイズする</span><span class="sxs-lookup"><span data-stu-id="1e04e-103">Customize the search results page</span></span>

<span data-ttu-id="1e04e-104">検索の業種と結果の種類を作成することで、 [Bing](https://Bing.com)で[SharePoint](http://sharepoint.com/)、 [microsoft Office](https://Office.com)、microsoft search を検索するときに表示される検索結果をカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-104">By creating search verticals and result types, you can customize the search results that are shown to users when they search in [SharePoint](http://sharepoint.com/), [Microsoft Office](https://Office.com), and Microsoft Search in [Bing](https://Bing.com).</span></span> <span data-ttu-id="1e04e-105">各業種では、ユーザーが表示するアクセス許可が付与されている情報を簡単に見つけられるようにします。</span><span class="sxs-lookup"><span data-stu-id="1e04e-105">Verticals make it easier for users to find the information they’ve got permission to see.</span></span> <span data-ttu-id="1e04e-106">たとえば、マーケティング部門のユーザーのために、サードパーティ製のソフトウェアからマーケティング分析データの検索を縦に作成できます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-106">For example, you can create a search vertical for marketing analysis data from third-party software for your users in the marketing department.</span></span> <span data-ttu-id="1e04e-107">また、検索結果の種類を定義し、このデータのレイアウトをカスタマイズすることもできます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-107">You can also define result types and customize the layout for this data.</span></span>  

<span data-ttu-id="1e04e-108">次のレベルで、業種と結果の種類を作成できます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-108">You can create verticals and result types at these levels:</span></span>

- <span data-ttu-id="1e04e-109">**組織レベル**–縦型を組織レベルで追加すると、ユーザーが[SharePoint](http://sharepoint.com/)スタートページ、 [Office](https://Office.com)、および[Bing](https://Bing.com)で検索を実行したときに、検索結果ページに表示されます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-109">**Organization level** – When you add a vertical at the organization level, it appears on the search results page when users search from their [SharePoint](http://sharepoint.com/) start page, on [Office](https://Office.com), and on [Bing](https://Bing.com).</span></span>
- <span data-ttu-id="1e04e-110">**サイトレベル**–たとえば、顧客サービスの従業員が**重要度 1**のインシデントを部門の SharePoint サイトから直接検索できるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-110">**Site level** – For example, you might want to allow your customer service employees to search for **Severity 1** incidents directly from their department’s SharePoint site.</span></span>

## <a name="search-verticals-explained"></a><span data-ttu-id="1e04e-111">検索業種の説明</span><span class="sxs-lookup"><span data-stu-id="1e04e-111">Search Verticals Explained</span></span>

<span data-ttu-id="1e04e-112">[Microsoft Search results] ページの上部には、検索業界であるタブの行があります。</span><span class="sxs-lookup"><span data-stu-id="1e04e-112">At the top of the Microsoft Search results page is a row of tabs that are the search verticals.</span></span> <span data-ttu-id="1e04e-113">検索垂直では、特定の種類の結果または特定のコンテンツのみが表示されます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-113">A search vertical only shows results of a certain type or from certain content.</span></span> <span data-ttu-id="1e04e-114">例として、ファイルまたはニュースのみが挙げられます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-114">An example is only files or news.</span></span> <span data-ttu-id="1e04e-115">Microsoft Search では、既定で、**すべて**の業種、**人**、**ファイル**、**サイト**、および**ニュース**が表示されます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-115">By default, Microsoft Search shows the verticals **All**, **People**, **Files**, **Sites**, and **News**.</span></span>  

<span data-ttu-id="1e04e-116">組織に関連する検索業種を追加することができます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-116">You can add search verticals that are relevant to your organization.</span></span> <span data-ttu-id="1e04e-117">これらは、 [SharePoint](http://sharepoint.com/)、 [Office](https://Office.com)、および[Bing](https://Bing.com)の Microsoft 検索結果ページに表示されます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-117">These will appear on the Microsoft Search results page in [SharePoint](http://sharepoint.com/), [Office](https://Office.com), and [Bing](https://Bing.com).</span></span> <span data-ttu-id="1e04e-118">たとえば、各グループに必要な情報の種類に基づいて、マーケティング関連のコンテンツ用に1つの垂直線を作成し、売り上げに対して別のものを作成することができます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-118">For example, you could create one vertical for marketing-related content and another for sales, based on the type of information that each group would want to have.</span></span> <span data-ttu-id="1e04e-119">すべての業種を追加して、コネクタ経由でインデックスが作成されたコンテンツからの結果のみを表示することができます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-119">You can add verticals to show results only from content indexed via connectors.</span></span>  

<span data-ttu-id="1e04e-120">**免責事項:** 各業種および結果の種類は、Microsoft Graph のコネクタプレビューの一部として現在プレビュー段階にあります。</span><span class="sxs-lookup"><span data-stu-id="1e04e-120">**DISCLAIMER:** Verticals and result types are currently in preview as a part of the Microsoft Graph connectors preview.</span></span> <span data-ttu-id="1e04e-121">[SharePoint](http://sharepoint.com/)内にあるコンテンツまたは[ファイル共有コネクタ](file-share-connector.md)によってインデックスが作成されたコンテンツに対して、垂直方向を作成することはできません。</span><span class="sxs-lookup"><span data-stu-id="1e04e-121">You can't create a vertical for content residing in [SharePoint](http://sharepoint.com/) or from content indexed by the [file share connector](file-share-connector.md).</span></span> <span data-ttu-id="1e04e-122">プレビューの詳細については、「[コネクタプレビュー](connectors-preview.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1e04e-122">To find out more about the preview, see [Connectors Preview](connectors-preview.md).</span></span> <span data-ttu-id="1e04e-123">プレビューに参加するには、最初に[Microsoft Graph Connector preview のサインアップフォーム](https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbRxWYgu82J_RFnMMATAS6_chUNVYwNU1CMDNZUDBSSDZKWVo2RDJDRjRLQi4u)を送信する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1e04e-123">To participate in the preview, you must first submit the [Microsoft Graph Connectors Preview Signup form](https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbRxWYgu82J_RFnMMATAS6_chUNVYwNU1CMDNZUDBSSDZKWVo2RDJDRjRLQi4u).</span></span>

## <a name="things-to-consider"></a><span data-ttu-id="1e04e-124">考慮事項</span><span class="sxs-lookup"><span data-stu-id="1e04e-124">Things to consider</span></span>

<span data-ttu-id="1e04e-125">開始する前に、コネクタにインデックスが作成されていることを確認してください。</span><span class="sxs-lookup"><span data-stu-id="1e04e-125">Before you start, make sure the connector has been indexed.</span></span> <span data-ttu-id="1e04e-126">ファイルサイズに応じて、最大48時間かかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="1e04e-126">It can take up to 48 hours, depending on the file size.</span></span>

<span data-ttu-id="1e04e-127">[SharePoint](http://sharepoint.com/)内にあるコンテンツまたは[ファイル共有コネクタ](file-share-connector.md)によってインデックスが作成されたコンテンツに対して、垂直方向を作成することはできません。</span><span class="sxs-lookup"><span data-stu-id="1e04e-127">You can’t create a vertical for content residing in [SharePoint](http://sharepoint.com/) or from content indexed by the [file share connector](file-share-connector.md).</span></span> <span data-ttu-id="1e04e-128">[コンテンツにインデックス](configure-connector.md)を作成する方法について説明します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-128">Learn how to [index content](configure-connector.md).</span></span>

<span data-ttu-id="1e04e-129">高レベルでは、次の3つの主要な手順を使用して垂直方向を追加します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-129">At a high level, there are three main steps for adding a vertical:</span></span>

1. <span data-ttu-id="1e04e-130">垂直方向のを作成します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-130">Create the vertical.</span></span> <span data-ttu-id="1e04e-131">この手順では、検索するコンテンツの縦の名前、コンテンツソース、および範囲を定義します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-131">In this step, you define the vertical’s name, content source, and scope of the content to search.</span></span>
2. <span data-ttu-id="1e04e-132">この垂直方向の結果がどのように表示されるかを定義します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-132">Define what the results for this vertical will look like.</span></span>  
3. <span data-ttu-id="1e04e-133">垂直リストページから、垂直 (表示する) を有効にします。</span><span class="sxs-lookup"><span data-stu-id="1e04e-133">Enable the vertical (to be displayed) from the vertical list page.</span></span>

## <a name="step-1-create-the-search-vertical"></a><span data-ttu-id="1e04e-134">手順 1: 検索垂直を作成する</span><span class="sxs-lookup"><span data-stu-id="1e04e-134">STEP 1: Create the search vertical</span></span>

<span data-ttu-id="1e04e-135">ウィザードを開始した後、検索するコンテンツの縦の名前、コンテンツソース、および範囲を定義する手順について説明しています。</span><span class="sxs-lookup"><span data-stu-id="1e04e-135">After you start the wizard, you're guided through the steps to define the vertical's name, content source, and scope of the content that it will search.</span></span> <span data-ttu-id="1e04e-136">垂直は無効な状態で作成されます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-136">The vertical is created in a disabled state.</span></span> <span data-ttu-id="1e04e-137">後で垂直方向を有効にします。</span><span class="sxs-lookup"><span data-stu-id="1e04e-137">You'll enable the vertical later.</span></span>

<span data-ttu-id="1e04e-138">[キーワードクエリ言語 (KQL)](https://docs.microsoft.com/sharepoint/dev/general-development/keyword-query-language-kql-syntax-reference)の限定されたセットを使用して、スコープを絞り込むことができます。また、ページに使用可能なプロパティの一覧が表示されます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-138">You can use a limited set of the [Keyword Query Language (KQL)](https://docs.microsoft.com/sharepoint/dev/general-development/keyword-query-language-kql-syntax-reference) to narrow down the scope, and the page lists the properties available to you.</span></span> <span data-ttu-id="1e04e-139">KQL を作成するには、ブール演算子と共に free text-キーワードおよびプロパティ制限を使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="1e04e-139">We recommend using free text-keywords and property restrictions with boolean operators for creating the KQL.</span></span>

### <a name="create-a-vertical-at-the-organization-level"></a><span data-ttu-id="1e04e-140">組織レベルで垂直線を作成する</span><span class="sxs-lookup"><span data-stu-id="1e04e-140">Create a vertical at the organization level</span></span>

<span data-ttu-id="1e04e-141">[SharePoint](http://sharepoint.com/) Home、 [Office](https://Office.com)、または[Bing](https://Bing.com)で Microsoft Search に垂直にするには、次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-141">To create the vertical on Microsoft Search in [SharePoint](http://sharepoint.com/) home, [Office](https://Office.com), or [Bing](https://Bing.com), follow these steps:</span></span>

1. <span data-ttu-id="1e04e-142">Microsoft 365 [管理センター](https://admin.microsoft.com)で、[ **microsoft Search** > の **設定** >] に移動**します。**</span><span class="sxs-lookup"><span data-stu-id="1e04e-142">In the Microsoft 365 [admin center](https://admin.microsoft.com), go to **Settings** > **Microsoft Search** > **Verticals**.</span></span>
1. <span data-ttu-id="1e04e-143">開始するには、[ **追加**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-143">Select **Add** to get started.</span></span>  

### <a name="create-a-vertical-at-the-site-level"></a><span data-ttu-id="1e04e-144">サイトレベルで垂直方向のを作成する</span><span class="sxs-lookup"><span data-stu-id="1e04e-144">Create a vertical at the site level</span></span>

1. <span data-ttu-id="1e04e-145">垂直方向を作成する[SharePoint](http://sharepoint.com/)サイトで、[**設定**] に移動します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-145">On the [SharePoint](http://sharepoint.com/) site where you want to create the vertical, go to **Settings**.</span></span>
1. <span data-ttu-id="1e04e-146">[**サイト情報**] を選択し、[**すべてのサイト設定**] を表示します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-146">Select **Site information** and then **View all site settings**.</span></span>
1. <span data-ttu-id="1e04e-147">[ **Microsoft search** ] セクションを探し、[**このサイトコレクションの Microsoft Search を構成する**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-147">Look for the **Microsoft Search** section, and then select **Configure Microsoft Search for this site collection**.</span></span>
1. <span data-ttu-id="1e04e-148">ナビゲーションウィンドウで、[ **ユーザー設定の操作**] に移動し、[**垂直**] タブを選択します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-148">In the navigation pane, go to **Custom experience**, and then select the **Verticals** tab.</span></span>
1. <span data-ttu-id="1e04e-149">垂直方向を追加するには、[ **追加**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-149">To add a vertical, select **Add**.</span></span>  
<span data-ttu-id="1e04e-150">または</span><span class="sxs-lookup"><span data-stu-id="1e04e-150">OR</span></span>  
<span data-ttu-id="1e04e-151">垂直方向を編集するには、一覧から縦に選択します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-151">To edit a vertical, select it in the list.</span></span>

<span data-ttu-id="1e04e-152">各業種は無効な状態で作成されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="1e04e-152">Remember, verticals are created in a disabled state.</span></span> <span data-ttu-id="1e04e-153">ユーザーが各業種を表示できるようにするには、それらを有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="1e04e-153">You still need to enable them before users can see the verticals.</span></span>

## <a name="step-2-create-the-result-types"></a><span data-ttu-id="1e04e-154">手順 2: 検索結果の種類を作成する</span><span class="sxs-lookup"><span data-stu-id="1e04e-154">STEP 2: Create the result types</span></span>

<span data-ttu-id="1e04e-155">結果の種類を使用してレイアウトを設計することで、結果を垂直に表示する方法を定義できます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-155">You can define how results are displayed in the vertical by designing the layout using result types.</span></span> <span data-ttu-id="1e04e-156">結果のレイアウトを使用すると、検索結果に重要な情報を直接表示することができます。したがって、ユーザーが探しているものが見つかったかどうかを確認するために、各結果を選択する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="1e04e-156">The result layout lets you show important information directly in the search results, so that users don't have to select each result to see if they've found what they're looking for.</span></span>

<span data-ttu-id="1e04e-p112">検索結果の種類とは、検索結果のタイプの違いに応じて表示方法を変えるルールのことです。このルールは、次のような構成になっています。</span><span class="sxs-lookup"><span data-stu-id="1e04e-p112">A search result type is a rule that causes distinct kinds of search results to be displayed in different ways. It consists of the following:</span></span>

- <span data-ttu-id="1e04e-159">検索結果のコンテンツソースなど、各検索結果を比較する**1 つまたは複数の条件**。</span><span class="sxs-lookup"><span data-stu-id="1e04e-159">**One or more conditions** to compare each search result against, such as the content source of the search result.</span></span>  
- <span data-ttu-id="1e04e-160">条件に一致する検索結果に使用する**結果レイアウト**。</span><span class="sxs-lookup"><span data-stu-id="1e04e-160">A **result layout** to use for search results that meet the conditions.</span></span> <span data-ttu-id="1e04e-161">結果レイアウトは、条件を満たすすべての結果が検索結果ページに表示され、動作する方法を制御します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-161">The result layout controls the way in which all results that meet the conditions appear and behave on a search results page.</span></span>

<span data-ttu-id="1e04e-162">**結果を垂直に表示するには、少なくとも1つの結果の種類を作成する必要があります。**</span><span class="sxs-lookup"><span data-stu-id="1e04e-162">**You must create at least one result type for results to display on the vertical.**</span></span> <span data-ttu-id="1e04e-163">垂直方向に複数の検索結果の種類を作成できます。これにより、さまざまな種類の結果に異なるレイアウトを使用できます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-163">You can create multiple result types for each vertical, which allows you to use different layouts for different type of results.</span></span> <span data-ttu-id="1e04e-164">たとえば、重大度**1**のインシデントをカスタマイズして、**重要度 3**のインシデントに比べて目立つ色とより大きいフォントを設定することができます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-164">For example, you can customize **Severity 1** incidents to have more prominent colors and a larger font compared to **Severity 3** incidents.</span></span>

<span data-ttu-id="1e04e-165">ウィザードを開始した後、検索結果の種類の名前、コンテンツソース、および条件を定義する手順について説明しています。</span><span class="sxs-lookup"><span data-stu-id="1e04e-165">After you start the wizard, you're guided through the steps to define the name, content source, and conditions for the result type.</span></span> <span data-ttu-id="1e04e-166">リストビューから検索結果の種類の優先度を定義できます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-166">You can define the priority of the result type from the list view.</span></span>
  
### <a name="create-a-result-type-at-the-organization-level"></a><span data-ttu-id="1e04e-167">組織レベルで結果の種類を作成する</span><span class="sxs-lookup"><span data-stu-id="1e04e-167">Create a result type at the organization level</span></span>

1. <span data-ttu-id="1e04e-168">[管理センター](https://admin.microsoft.com)で、[**Microsoft Search**の**設定** > ] に移動し、[**結果の種類**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-168">In the [admin center](https://admin.microsoft.com), go to **Setting** > **Microsoft Search**, and then select **Result type**.</span></span>
1. <span data-ttu-id="1e04e-169">**検索結果の種類**を追加するには、[ **追加**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-169">To add a **Result type**, select **Add**.</span></span> <span data-ttu-id="1e04e-170">検索結果の種類を編集するには、関連するリストで結果の種類を選択します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-170">To edit a result type, select the result type in the relevant list.</span></span>

### <a name="create-a-results-type-at-the-site-level"></a><span data-ttu-id="1e04e-171">サイトレベルで結果の種類を作成する</span><span class="sxs-lookup"><span data-stu-id="1e04e-171">Create a results type at the site level</span></span>

1. <span data-ttu-id="1e04e-172">検索結果の種類を作成する[SharePoint](http://sharepoint.com/)サイトで、[**設定**] に移動します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-172">On the [SharePoint](http://sharepoint.com/) site where you want to create the result type, go to **Settings**.</span></span>
1. <span data-ttu-id="1e04e-173">[**サイト情報**] を選択し、[**すべてのサイト設定**] を表示します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-173">Select **Site information** and then **View all site settings**.</span></span>
1. <span data-ttu-id="1e04e-174">[Microsoft Search] セクションを探し、[**このサイトコレクションの Microsoft search を構成する**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-174">Look for the Microsoft Search section, and then select **Configure Microsoft Search for this site collection**.</span></span>
1. <span data-ttu-id="1e04e-175">ナビゲーションウィンドウで、[ **ユーザー設定の操作**] に移動し、[**結果の種類**] タブを選択します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-175">In the navigation pane, go to **Custom experience**, and then select **Result type** tab.</span></span>
1. <span data-ttu-id="1e04e-176">検索結果の種類を追加するには、[ **追加**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-176">To add a result type, select **Add**.</span></span>  
<span data-ttu-id="1e04e-177">または</span><span class="sxs-lookup"><span data-stu-id="1e04e-177">OR</span></span>  
<span data-ttu-id="1e04e-178">検索結果の種類を編集するには、リストで結果の種類を選択します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-178">To edit a result type, select the result type in the list.</span></span>

### <a name="view-the-vertical-after-enabling"></a><span data-ttu-id="1e04e-179">垂直方向の表示を有効にした後</span><span class="sxs-lookup"><span data-stu-id="1e04e-179">View the vertical after enabling</span></span>

<span data-ttu-id="1e04e-180">垂直方向を有効にした後は、表示する前にしばらく時間がかかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="1e04e-180">After you enable the vertical, it might take a while before you can view it.</span></span>
<span data-ttu-id="1e04e-181">有効にした後に待機しない場合は、 **cacheClear = true**を[SharePoint](http://sharepoint.com/)および[Office](https://Office.com)の URL に追加して、すぐに垂直方向を表示することができます。</span><span class="sxs-lookup"><span data-stu-id="1e04e-181">If you do not want to wait after enabling it, you can append **cacheClear=true** to the URL in [SharePoint](http://sharepoint.com/) and [Office](https://Office.com) to view the vertical immediately.</span></span>

## <a name="troubleshooting"></a><span data-ttu-id="1e04e-182">トラブルシューティング</span><span class="sxs-lookup"><span data-stu-id="1e04e-182">Troubleshooting</span></span>

<span data-ttu-id="1e04e-183">発生する可能性のある一般的な問題と、それらを修正するためのアクションを次に示します。</span><span class="sxs-lookup"><span data-stu-id="1e04e-183">Here's a list of common issues you might encounter and actions for fixing them.</span></span>

|<span data-ttu-id="1e04e-184">Error</span><span class="sxs-lookup"><span data-stu-id="1e04e-184">Error</span></span>  |<span data-ttu-id="1e04e-185">Action</span><span class="sxs-lookup"><span data-stu-id="1e04e-185">Action</span></span>  |
|---------|---------|
|<span data-ttu-id="1e04e-186">垂直方向に*何らか*のエラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="1e04e-186">I see a *Something went wrong* error on the vertical.</span></span> |   <span data-ttu-id="1e04e-187">セットアップを完了するには、垂直および結果の種類の両方が必要です。</span><span class="sxs-lookup"><span data-stu-id="1e04e-187">Both vertical and result types are needed to complete the setup.</span></span> <span data-ttu-id="1e04e-188">同じコンテンツソースに対して両方の作成が完了していることを確認してください。</span><span class="sxs-lookup"><span data-stu-id="1e04e-188">Make sure you have created both for the same content source.</span></span>      |
|<span data-ttu-id="1e04e-189">結果のレイアウトが表示されないのはなぜですか?</span><span class="sxs-lookup"><span data-stu-id="1e04e-189">Why don't I see my result layout, although I have created one?</span></span> | <span data-ttu-id="1e04e-190">これらの設定は通常キャッシュされるため、検索結果の種類を使用するのに数分かかります。</span><span class="sxs-lookup"><span data-stu-id="1e04e-190">It takes a few minutes for result types to be used as these settings are generally cached.</span></span> <span data-ttu-id="1e04e-191">数分待ってから、もう一度実行してください。</span><span class="sxs-lookup"><span data-stu-id="1e04e-191">Wait for a few minutes and try again.</span></span>        |
|<span data-ttu-id="1e04e-192">[垂直または結果の種類] ページにコンテンツソースが表示されません。</span><span class="sxs-lookup"><span data-stu-id="1e04e-192">I don't see any content sources on the vertical or result type page.</span></span>     |      <span data-ttu-id="1e04e-193">コネクタとインデックスデータが構成されていることを確認してください。</span><span class="sxs-lookup"><span data-stu-id="1e04e-193">Make sure you have configured connectors and indexed data.</span></span>   |

## <a name="next-steps"></a><span data-ttu-id="1e04e-194">次のステップ</span><span class="sxs-lookup"><span data-stu-id="1e04e-194">Next steps</span></span>

[<span data-ttu-id="1e04e-195">手順 3: 結果のレイアウトをカスタマイズする</span><span class="sxs-lookup"><span data-stu-id="1e04e-195">STEP 3: Customize the results layout</span></span>](customize-results-layout.md)
