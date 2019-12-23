---
title: Microsoft Search Insights ダッシュボードレポート
ms.author: anfowler
author: adefowler
manager: shohara
ms.audience: Admin
ms.topic: reference
ms.service: mssearch
localization_priority: Normal
search.appverid:
- BFB160
- MET150
- MOE150
ms.assetid: ebce7fdc-e89b-473c-8131-67e659bb3f73
description: Microsoft Search の Insights ダッシュボードから測定値を分析し、コンテンツを管理する
ms.openlocfilehash: 8ed0e13b53f61c699e8cf5628341adba3b96be9c
ms.sourcegitcommit: 26481c00963d836de4ed64a454fb6c5b49c5075d
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/18/2019
ms.locfileid: "40738055"
---
# <a name="microsoft-search-insights-dashboard-reports"></a><span data-ttu-id="bf891-103">Microsoft Search Insights ダッシュボードレポート</span><span class="sxs-lookup"><span data-stu-id="bf891-103">Microsoft Search Insights dashboard reports</span></span>

<span data-ttu-id="bf891-104">Microsoft Search Insights ダッシュボードを使用して、発行された回答の[Bing](https://Bing.com)データを管理できます。</span><span class="sxs-lookup"><span data-stu-id="bf891-104">You can use the Microsoft Search Insights dashboard to manage [Bing](https://Bing.com) data for your published answers.</span></span> <span data-ttu-id="bf891-105">これは、ユーザーがコンテンツを簡単に[見つけられるよう](make-content-easy-to-find.md)にするために必要な手順の1つにすぎません。</span><span class="sxs-lookup"><span data-stu-id="bf891-105">This is just one of the steps needed to [make content easy to find](make-content-easy-to-find.md) for your users.</span></span>

<span data-ttu-id="bf891-106">Microsoft 365[管理センター](https://admin.microsoft.com)で最初に microsoft Search に移動するときは、Insights dashboard に入力します。</span><span class="sxs-lookup"><span data-stu-id="bf891-106">When you first go to Microsoft Search in the Microsoft 365 [admin center](https://admin.microsoft.com), you enter on the Insights dashboard.</span></span>

![Insights-dashboard](media/Insights-dashboard.png)

<span data-ttu-id="bf891-108">次のレポートは、Insights ダッシュボードで利用できます。</span><span class="sxs-lookup"><span data-stu-id="bf891-108">The following reports are available on the Insights dashboard.</span></span>

> [!NOTE]
> <span data-ttu-id="bf891-109">レポート内のデータは、 [Bing](https://Bing.com)データのみを表します。</span><span class="sxs-lookup"><span data-stu-id="bf891-109">The data in the reports only represents [Bing](https://Bing.com) data.</span></span>

## <a name="top-queries"></a><span data-ttu-id="bf891-110">よく使用されるクエリ</span><span class="sxs-lookup"><span data-stu-id="bf891-110">Top queries</span></span>

<span data-ttu-id="bf891-111">このレポートでは、ユーザーが実行する上位の 2000 [Bing](https://Bing.com)検索クエリについての詳細が提供されます。</span><span class="sxs-lookup"><span data-stu-id="bf891-111">This report gives details about the top 2000 [Bing](https://Bing.com) search queries that users run.</span></span> <span data-ttu-id="bf891-112">クエリを**上位のクエリ**に表示するには、クエリは少なくとも3回のクリックを取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bf891-112">For a query to appear in **Top queries**, the query must get at least three clicks.</span></span>

![[上位のクエリ] テーブルヘッダーでレポートします。クエリ、クエリの合計数、およびクリックスルー率。](media/Insights-topqueries.png)

<span data-ttu-id="bf891-114">ユーザーが検索しているものを見つけないことを意味するのは、クリックスルーレート (CTR) です。</span><span class="sxs-lookup"><span data-stu-id="bf891-114">A low click-through rate (CTR) means that users aren’t finding what they’re looking for.</span></span>

<span data-ttu-id="bf891-115">回答の種類に基づいてフィルター処理することで、レポートのさまざまなビューを選択できます。</span><span class="sxs-lookup"><span data-stu-id="bf891-115">You can choose different views of the report by filtering on the type of answer.</span></span> <span data-ttu-id="bf891-116">たとえば、ブックマークの上位のクエリを表示する場合は、レポートの右上隅にあるドロップダウンを選択し、[**ブックマーク**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="bf891-116">For example, if you just want to view the top queries for Bookmarks, select the drop-down in the upper-right corner of the report, and then select **Bookmarks**.</span></span> <span data-ttu-id="bf891-117">既定では、**すべて**の応答の種類が表示されます。</span><span class="sxs-lookup"><span data-stu-id="bf891-117">By default, **All** answer types are shown.</span></span>

![ブックマーク、ユーザー、Q&A、ファイル、グループ、場所、会話、サイトによって上位のクエリレポートをフィルター処理する](media/Insights-topqueries-dropdown.png)

## <a name="impression-distribution"></a><span data-ttu-id="bf891-119">インプレッションの分布</span><span class="sxs-lookup"><span data-stu-id="bf891-119">Impression distribution</span></span>

<span data-ttu-id="bf891-120">このレポートでは、さまざまな回答に関して[Bing](https://Bing.com)でのインプレッション分布が表示されます。</span><span class="sxs-lookup"><span data-stu-id="bf891-120">This report shows impression distribution in [Bing](https://Bing.com) over time for various answers.</span></span> <span data-ttu-id="bf891-121">ブックマーク、ユーザー、Q&A、ファイル、場所、ファイルサイト、グループ、会話などがあります。</span><span class="sxs-lookup"><span data-stu-id="bf891-121">Examples are bookmarks, people, Q&A, files, locations, file sites, groups, and conversations.</span></span>

![期間として90日が選択されたインプレッションレポート。](media/Insights-impressions.png)

<span data-ttu-id="bf891-123">インプレッション配布は、指定された期間中にユーザーが検索する内容を管理者が理解するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="bf891-123">Impression distribution can help admins understand what users look for during a specified period.</span></span>
