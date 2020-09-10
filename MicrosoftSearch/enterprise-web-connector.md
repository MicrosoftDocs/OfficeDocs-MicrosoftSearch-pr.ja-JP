---
title: Microsoft Search のエンタープライズ Web サイトコネクタ
ms.author: monaray
author: monaray97
manager: jameslau
ms.audience: Admin
ms.topic: article
ms.service: mssearch
localization_priority: Normal
search.appverid:
- BFB160
- MET150
- MOE150
description: Microsoft Search のエンタープライズ web サイトコネクタを設定する
ms.openlocfilehash: 4fb80ce4e3dbc77638e3b7db9c2ebd3c39d5a6d8
ms.sourcegitcommit: 988c37610e71f9784b486660400aecaa7bed40b0
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/09/2020
ms.locfileid: "47422957"
---
<!-- markdownlint-disable no-inline-html -->
# <a name="enterprise-websites-connector"></a><span data-ttu-id="8329b-103">エンタープライズ web サイトコネクタ</span><span class="sxs-lookup"><span data-stu-id="8329b-103">Enterprise websites connector</span></span>

<span data-ttu-id="8329b-104">エンタープライズ web サイトコネクタを使用すると、組織は **内部に接続している web サイトの**記事とコンテンツにインデックスを作成できます。</span><span class="sxs-lookup"><span data-stu-id="8329b-104">With the Enterprise websites connector, your organization can index articles and **content from its internal-facing websites**.</span></span> <span data-ttu-id="8329b-105">コネクタを構成し、web サイトからコンテンツを同期すると、エンドユーザーは任意の Microsoft 検索クライアントからそのコンテンツを検索できるようになります。</span><span class="sxs-lookup"><span data-stu-id="8329b-105">After you configure the connector and sync content from the website, end users can search for that content from any Microsoft Search client.</span></span>

<span data-ttu-id="8329b-106">この記事は、 [Microsoft 365](https://www.microsoft.com/microsoft-365) 管理者またはエンタープライズ websites コネクタを構成、実行、および監視するユーザーを対象としています。</span><span class="sxs-lookup"><span data-stu-id="8329b-106">This article is for [Microsoft 365](https://www.microsoft.com/microsoft-365) administrators or anyone who configures, runs, and monitors an Enterprise websites connector.</span></span> <span data-ttu-id="8329b-107">コネクタとコネクタの機能、制限事項、およびトラブルシューティングの手法を構成する方法について説明します。</span><span class="sxs-lookup"><span data-stu-id="8329b-107">It explains how to configure your connector and connector capabilities, limitations, and troubleshooting techniques.</span></span>  

## <a name="connect-to-a-data-source"></a><span data-ttu-id="8329b-108">データソースへの接続</span><span class="sxs-lookup"><span data-stu-id="8329b-108">Connect to a data source</span></span>

<span data-ttu-id="8329b-109">データソースに接続するには、 [Azure Active Directory (AZURE AD)](https://docs.microsoft.com/azure/active-directory/)を使用して、ルート URL と認証の形式 (None、Basic Authentication、OAuth 2.0) が必要です。</span><span class="sxs-lookup"><span data-stu-id="8329b-109">To connect to your data source, you need your root URL and a form of authentication: None, Basic Authentication, or OAuth 2.0 with [Azure Active Directory (Azure AD)](https://docs.microsoft.com/azure/active-directory/).</span></span>

### <a name="authentication"></a><span data-ttu-id="8329b-110">認証</span><span class="sxs-lookup"><span data-stu-id="8329b-110">Authentication</span></span>

<span data-ttu-id="8329b-111">基本認証には、ユーザー名とパスワードが必要です。</span><span class="sxs-lookup"><span data-stu-id="8329b-111">Basic Authentication requires a username and password.</span></span> <span data-ttu-id="8329b-112">[Microsoft 365 管理センター](https://admin.microsoft.com)を使用して、この bot アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="8329b-112">Create this bot account by using the [Microsoft 365 admin center](https://admin.microsoft.com).</span></span>

<span data-ttu-id="8329b-113">[AZURE AD](https://docs.microsoft.com/azure/active-directory/)を使用する OAuth 2.0 には、リソース ID、クライアント ID、およびクライアントシークレットが必要です。</span><span class="sxs-lookup"><span data-stu-id="8329b-113">OAuth 2.0 with [Azure AD](https://docs.microsoft.com/azure/active-directory/) requires a resource ID, Client ID, and Client Secret.</span></span>

<span data-ttu-id="8329b-114">詳細については、「 [OAuth 2.0 コード付与フローを使用して Azure Active Directory web アプリケーションへのアクセスを承認する](https://docs.microsoft.com/azure/active-directory/develop/v1-protocols-oauth-code)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8329b-114">For more information, see [Authorize access to Azure Active Directory web applications using OAuth 2.0 code grant flow](https://docs.microsoft.com/azure/active-directory/develop/v1-protocols-oauth-code).</span></span> <span data-ttu-id="8329b-115">次の値を使用して登録します。</span><span class="sxs-lookup"><span data-stu-id="8329b-115">Register with the following values:</span></span>

<span data-ttu-id="8329b-116">**Name:** Microsoft Search</span><span class="sxs-lookup"><span data-stu-id="8329b-116">**Name:** Microsoft Search</span></span> <br/>
<span data-ttu-id="8329b-117">**Redirect_URI:**`https://gcs.office.com/v1.0/admin/oauth/callback`</span><span class="sxs-lookup"><span data-stu-id="8329b-117">**Redirect_URI:** `https://gcs.office.com/v1.0/admin/oauth/callback`</span></span>

<span data-ttu-id="8329b-118">リソース、client_id、client_secret の値を取得するには、「承認コードを使用して、リダイレクト URL web ページで **アクセストークンを要求** する」に移動します。</span><span class="sxs-lookup"><span data-stu-id="8329b-118">To get the values for the resource, client_id, and client_secret, go to **Use the authorization code to request an access token** on the redirect URL webpage.</span></span>

<span data-ttu-id="8329b-119">詳細については、「 [クイックスタート: アプリケーションを Microsoft identity platform に登録する](https://docs.microsoft.com/azure/active-directory/develop/quickstart-register-app)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8329b-119">For even more information, see [Quickstart: Register an application with the Microsoft identity platform](https://docs.microsoft.com/azure/active-directory/develop/quickstart-register-app).</span></span>

### <a name="root-url"></a><span data-ttu-id="8329b-120">ルート URL</span><span class="sxs-lookup"><span data-stu-id="8329b-120">Root URL</span></span>

<span data-ttu-id="8329b-121">ルート URL は、クロールを開始するもので、認証に使用されます。</span><span class="sxs-lookup"><span data-stu-id="8329b-121">The root URL is what initiates the crawl and is used for authentication.</span></span> <span data-ttu-id="8329b-122">クロールする web サイトのホームページから URL を取得できます。</span><span class="sxs-lookup"><span data-stu-id="8329b-122">You can get the URL from the home page of the website you want to crawl.</span></span>

## <a name="select-the-source-properties"></a><span data-ttu-id="8329b-123">ソースのプロパティを選択する</span><span class="sxs-lookup"><span data-stu-id="8329b-123">Select the source properties</span></span>

<span data-ttu-id="8329b-124">ソースのプロパティは、エンタープライズ web サイトのデータ形式に基づいて定義されます。</span><span class="sxs-lookup"><span data-stu-id="8329b-124">Source properties are defined based on the data format of the enterprise website.</span></span> <span data-ttu-id="8329b-125">ただし、コンテンツに機密がある場合やクロール価値がない場合は、一部の Url をクロール対象から除外する除外 **リスト** を作成できます。</span><span class="sxs-lookup"><span data-stu-id="8329b-125">However, you can create an **Exclusion list** to exclude some URLs from getting crawled if that content is sensitive or not worth crawling.</span></span> <span data-ttu-id="8329b-126">除外リストを作成するには、ルート URL を参照します。</span><span class="sxs-lookup"><span data-stu-id="8329b-126">To create an exclusion list, browse through the root URL.</span></span> <span data-ttu-id="8329b-127">構成プロセス中に、除外された Url をリストに追加するオプションがあります。</span><span class="sxs-lookup"><span data-stu-id="8329b-127">You have the option to add the excluded URLs to the list during the configuration process.</span></span>

## <a name="manage-search-permissions"></a><span data-ttu-id="8329b-128">検索アクセス許可を管理する</span><span class="sxs-lookup"><span data-stu-id="8329b-128">Manage search permissions</span></span>

<span data-ttu-id="8329b-129">アクセス制御リスト (Acl) はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="8329b-129">There's no support for Access Control Lists (ACLs).</span></span> <span data-ttu-id="8329b-130">そのため、組織内のすべてのユーザーに表示される web サイトのみを接続することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="8329b-130">Thus, we recommend connecting only the websites that are visible to any user within your organization.</span></span>

## <a name="set-the-refresh-schedule"></a><span data-ttu-id="8329b-131">更新スケジュールを設定する</span><span class="sxs-lookup"><span data-stu-id="8329b-131">Set the refresh schedule</span></span>

<span data-ttu-id="8329b-132">エンタープライズ web サイトコネクタは、フルクロールのみをサポートします。</span><span class="sxs-lookup"><span data-stu-id="8329b-132">The Enterprise websites connector only supports a full crawl.</span></span> <span data-ttu-id="8329b-133">これは、すべてのクロール中にコネクタがすべての web サイトのコンテンツを読み取ることを意味します。</span><span class="sxs-lookup"><span data-stu-id="8329b-133">This means that the connector reads all the website's content during every crawl.</span></span> <span data-ttu-id="8329b-134">コネクタがコンテンツを読み取るのに十分な時間をかけるようにするには、更新のスケジュール間隔を大きくすることをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="8329b-134">To make sure the connector gets enough time to read the content, we recommend that you set a large refresh schedule interval.</span></span> <span data-ttu-id="8329b-135">スケジュールされた更新は、1週間から2週間の間で行うことをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="8329b-135">We recommend a scheduled refresh between one and two weeks.</span></span>

## <a name="troubleshooting"></a><span data-ttu-id="8329b-136">トラブルシューティング</span><span class="sxs-lookup"><span data-stu-id="8329b-136">Troubleshooting</span></span>

<span data-ttu-id="8329b-137">Web サイトのコンテンツを読み取るときに、以下の詳細なエラーコードで示されているソースエラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="8329b-137">When reading the website's content, the crawl may encounter some source errors which are represented by the detailed error codes below.</span></span> <span data-ttu-id="8329b-138">エラーの種類に関する詳細を確認するには、接続を選択した後、[ **エラーの詳細** ] ページに移動します。</span><span class="sxs-lookup"><span data-stu-id="8329b-138">To get more information on the types of errors, go to the **error details** page after selecting the connection.</span></span> <span data-ttu-id="8329b-139">**エラーコード**をクリックして、より詳細なエラーを表示します。</span><span class="sxs-lookup"><span data-stu-id="8329b-139">Click on the **error code** to see more detailed errors.</span></span> <span data-ttu-id="8329b-140">詳細については [、「コネクタの管理](https://docs.microsoft.com/microsoftsearch/manage-connector) 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8329b-140">Also refer to [Manage your connector](https://docs.microsoft.com/microsoftsearch/manage-connector) to learn more.</span></span>

 <span data-ttu-id="8329b-141">詳細なエラーコード</span><span class="sxs-lookup"><span data-stu-id="8329b-141">Detailed Error code</span></span> | <span data-ttu-id="8329b-142">エラー メッセージ</span><span class="sxs-lookup"><span data-stu-id="8329b-142">Error message</span></span>
 --- | ---
 <span data-ttu-id="8329b-143">6001</span><span class="sxs-lookup"><span data-stu-id="8329b-143">6001</span></span> | <span data-ttu-id="8329b-144">インデックスを作成しようとしているサイトに到達できない</span><span class="sxs-lookup"><span data-stu-id="8329b-144">The site that is being tried to index is not reachable</span></span>
 <span data-ttu-id="8329b-145">6005</span><span class="sxs-lookup"><span data-stu-id="8329b-145">6005</span></span> | <span data-ttu-id="8329b-146">インデックスを作成しようとしているソースページは robots.txt 構成ごとにブロックされています。</span><span class="sxs-lookup"><span data-stu-id="8329b-146">The source page that is being tried to index has been blocked by as per robots.txt configuration.</span></span>
 <span data-ttu-id="8329b-147">6008</span><span class="sxs-lookup"><span data-stu-id="8329b-147">6008</span></span> | <span data-ttu-id="8329b-148">DNS を解決できない</span><span class="sxs-lookup"><span data-stu-id="8329b-148">Unable to resolve the DNS</span></span>
 <span data-ttu-id="8329b-149">6009</span><span class="sxs-lookup"><span data-stu-id="8329b-149">6009</span></span> | <span data-ttu-id="8329b-150">すべてのクライアント側エラー (HTTP 404、408を除く) については、「HTTP 4xx エラーコード」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8329b-150">For all client side errors (Except HTTP 404, 408), please refer to HTTP 4xx error codes for details.</span></span>
 <span data-ttu-id="8329b-151">6013</span><span class="sxs-lookup"><span data-stu-id="8329b-151">6013</span></span> | <span data-ttu-id="8329b-152">インデックスを作成しようとしているソースページが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="8329b-152">The source page that is being tried to index could not be found.</span></span> <span data-ttu-id="8329b-153">(HTTP 404 エラー)</span><span class="sxs-lookup"><span data-stu-id="8329b-153">(HTTP 404 error)</span></span>
 <span data-ttu-id="8329b-154">6018</span><span class="sxs-lookup"><span data-stu-id="8329b-154">6018</span></span> | <span data-ttu-id="8329b-155">ソースページが応答していないため、要求がタイムアウトしました。(HTTP 408 エラー)</span><span class="sxs-lookup"><span data-stu-id="8329b-155">The source page is not responding, and the request has timed out. (HTTP 408 error)</span></span>
 <span data-ttu-id="8329b-156">6021</span><span class="sxs-lookup"><span data-stu-id="8329b-156">6021</span></span> | <span data-ttu-id="8329b-157">インデックスを作成しようとしているソースページには、ページ上にテキストコンテンツがありません。</span><span class="sxs-lookup"><span data-stu-id="8329b-157">The source page that is being tried to index has no textual content on the page.</span></span>
 <span data-ttu-id="8329b-158">6023</span><span class="sxs-lookup"><span data-stu-id="8329b-158">6023</span></span> | <span data-ttu-id="8329b-159">インデックスを作成しようとしているソースページはサポートされていません (HTML ページではありません)。</span><span class="sxs-lookup"><span data-stu-id="8329b-159">The source page that is being tried to index is unsupported (not a HTML page)</span></span>
 <span data-ttu-id="8329b-160">6024</span><span class="sxs-lookup"><span data-stu-id="8329b-160">6024</span></span> | <span data-ttu-id="8329b-161">インデックスを作成しようとしているソースページに、サポートされていないコンテンツがあります。</span><span class="sxs-lookup"><span data-stu-id="8329b-161">The source page that is being tried to index has unsupported content.</span></span>

* <span data-ttu-id="8329b-162">エラー6001-6013 は、ネットワークの問題が原因でデータソースに到達できない場合、またはデータソース自体が削除、移動、または名前変更された場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="8329b-162">Errors 6001-6013 occur when the data source is not reachable due to a network issue or when the data source itself is deleted, moved, or renamed.</span></span> <span data-ttu-id="8329b-163">指定したデータソースの詳細が有効であるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="8329b-163">Check if the data source details provided are still valid.</span></span>
* <span data-ttu-id="8329b-164">エラー6021-6024 データソースにページ上にテキスト以外のコンテンツが含まれている場合、またはページが HTML ではない場合にエラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="8329b-164">Errors 6021-6024 error occur when the data source contains non-textual content on the page or when the page is not an HTML.</span></span> <span data-ttu-id="8329b-165">データソースを確認し、このページを除外リストに追加するか、エラーを無視してください。</span><span class="sxs-lookup"><span data-stu-id="8329b-165">Please check the data source and add this page in exclusion list or ignore the error.</span></span>

## <a name="limitations"></a><span data-ttu-id="8329b-166">制限事項</span><span class="sxs-lookup"><span data-stu-id="8329b-166">Limitations</span></span>

<span data-ttu-id="8329b-167">エンタープライズ web サイトコネクタは、 **動的 web ページ**上のデータの検索をサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="8329b-167">The Enterprise websites connector doesn't support searching data on **dynamic webpages**.</span></span> <span data-ttu-id="8329b-168">これらの web ページの例は、コンテンツ管理システム ( [Confluence](https://www.atlassian.com/software/confluence) 、 [Unily](https://www.unily.com/) 、web サイトのコンテンツを格納するデータベースなど) に存在します。</span><span class="sxs-lookup"><span data-stu-id="8329b-168">Examples of those webpages live in content management systems like [Confluence](https://www.atlassian.com/software/confluence) and [Unily](https://www.unily.com/) or databases that store website content.</span></span>
