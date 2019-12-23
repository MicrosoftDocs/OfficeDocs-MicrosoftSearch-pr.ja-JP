---
title: 電源アプリを統合する
ms.author: dawholl
author: dawholl
manager: kellis
ms.audience: Admin
ms.topic: article
ms.service: mssearch
localization_priority: Normal
search.appverid:
- BFB160
- MET150
- MOE150
ms.assetid: 1fadcba3-4a7f-4a55-8476-d4e64d49a15f
description: Microsoft Search のブックマーク検索結果にブラウザーベースのアプリを含める
ms.openlocfilehash: 7d3dd21758c63da14bbd3896ece1ce67a19c80a2
ms.sourcegitcommit: f4cb37fdf85b895337caee827fb72b5b7fcaa8ad
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/12/2019
ms.locfileid: "39995025"
---
# <a name="integrate-power-apps-in-microsoft-search-bookmarks"></a><span data-ttu-id="10752-103">Microsoft 検索ブックマークでの電源アプリの統合</span><span class="sxs-lookup"><span data-stu-id="10752-103">Integrate Power Apps in Microsoft Search bookmarks</span></span>
   
<span data-ttu-id="10752-104">既存の[Microsoft Power Apps](https://products.office.com/business/microsoft-powerapps)を microsoft 検索ブックマークに統合することにより、休暇時間の入力や経費の報告など、ユーザーがタスクを完了できるようにします。</span><span class="sxs-lookup"><span data-stu-id="10752-104">Help your users complete tasks, like entering vacation time or reporting expenses, by integrating existing [Microsoft Power Apps](https://products.office.com/business/microsoft-powerapps) into your Microsoft Search bookmarks.</span></span> <span data-ttu-id="10752-105">統合された電源アプリがブックマークの結果に表示されるため、別のサイトに移動したり、別のツールを開いたりする必要がなくなり、時間と労力を節約できます。</span><span class="sxs-lookup"><span data-stu-id="10752-105">Integrated Power Apps appear within a bookmark result, eliminating the need to go to a different site or open a separate tool, which saves times and effort.</span></span>
  
## <a name="what-are-power-apps"></a><span data-ttu-id="10752-106">電源アプリとは</span><span class="sxs-lookup"><span data-stu-id="10752-106">What are Power Apps?</span></span>

<span data-ttu-id="10752-107">[Power Apps](https://products.office.com/business/microsoft-powerapps)は、コーディング操作を必要とせずに、ブラウザーまたは電話やタブレットで実行されるビジネスアプリケーションを構築できるようにするサービスです。</span><span class="sxs-lookup"><span data-stu-id="10752-107">[Power Apps](https://products.office.com/business/microsoft-powerapps) is a service that lets you build business apps that run in a browser or on a phone or tablet with no coding experience required.</span></span> <span data-ttu-id="10752-108">詳細については、次の項目を参照してください。</span><span class="sxs-lookup"><span data-stu-id="10752-108">Learn more:</span></span>
  
- [<span data-ttu-id="10752-109">ガイド付き学習</span><span class="sxs-lookup"><span data-stu-id="10752-109">Guided Learning</span></span>](https://docs.microsoft.com/learn/browse/?products=powerapps)
    
- [<span data-ttu-id="10752-110">ドキュメント</span><span class="sxs-lookup"><span data-stu-id="10752-110">Documentation</span></span>](https://docs.microsoft.com/powerapps/)
    
## <a name="add-a-power-app-to-a-bookmark"></a><span data-ttu-id="10752-111">Power App をブックマークに追加する</span><span class="sxs-lookup"><span data-stu-id="10752-111">Add a Power App to a bookmark</span></span>

<span data-ttu-id="10752-112">[Power Apps (https://products.office.com/business/microsoft-powerapps)任意のブラウザーおよび任意のデバイスで作業し、追加する時間は1分未満です。</span><span class="sxs-lookup"><span data-stu-id="10752-112">[Power Apps(https://products.office.com/business/microsoft-powerapps) work in any browser and on any device and take less than a minute to add.</span></span>
  
1. <span data-ttu-id="10752-113">統合する[電源アプリのアプリ ID を検索](https://docs.microsoft.com/powerapps/maker/canvas-apps/get-sessionid#get-an-app-id)します。</span><span class="sxs-lookup"><span data-stu-id="10752-113">[Find the App ID for the Power App](https://docs.microsoft.com/powerapps/maker/canvas-apps/get-sessionid#get-an-app-id) you want to integrate.</span></span>
    
2. <span data-ttu-id="10752-114">Microsoft 365[管理センター](https://admin.microsoft.com)で、[**ブックマーク**] に移動します。</span><span class="sxs-lookup"><span data-stu-id="10752-114">In the Microsoft 365 [admin center](https://admin.microsoft.com), go to **Bookmarks**.</span></span>
    
3. <span data-ttu-id="10752-115">Power App を追加するブックマークを追加するか、既存のブックマークを検索します。</span><span class="sxs-lookup"><span data-stu-id="10752-115">Add a bookmark or find an existing bookmark that you want to add a Power App to.</span></span>
    
4. <span data-ttu-id="10752-116">[ブックマークの設定] で、[ **Power app**] を選択し、[ **Power app の追加**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="10752-116">In the bookmark settings, select **Power App**, and then select **Add a Power App**.</span></span>
    
5. <span data-ttu-id="10752-117">App ID を入力するか貼り付けます。</span><span class="sxs-lookup"><span data-stu-id="10752-117">Enter or paste the App ID.</span></span>
    
    <span data-ttu-id="10752-118">高さと幅は自動的に追加されます。</span><span class="sxs-lookup"><span data-stu-id="10752-118">The height and width are automatically added.</span></span> <span data-ttu-id="10752-119">ブックマークでは、縦向きと横向きの両方の向きはサポートされていますが、現在、サイズを変更することはできません。</span><span class="sxs-lookup"><span data-stu-id="10752-119">Bookmarks can support both portrait and landscape orientations, but currently the size can't be changed.</span></span>
    
6. <span data-ttu-id="10752-120">ブックマークのプレビューは、ブックマークの結果に Power App がどのように表示されるかを示しています。</span><span class="sxs-lookup"><span data-stu-id="10752-120">The bookmark preview shows how the Power App will appear in the bookmark result.</span></span>
    
    <span data-ttu-id="10752-121">プレビューの Power App は、テストと使用が容易になるように完全に機能します。</span><span class="sxs-lookup"><span data-stu-id="10752-121">The Power App in the preview is fully functional to make it easy to test and use.</span></span>
    
7. <span data-ttu-id="10752-122">[**発行**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="10752-122">Select **Publish**.</span></span>
    
<span data-ttu-id="10752-123">承認された Microsoft 検索ユーザーが、任意のブックマークのキーワードまたは予約済みのキーワードを使用して[Bing](https://Bing.com)で検索すると、Power App がブックマークの結果に表示されます。</span><span class="sxs-lookup"><span data-stu-id="10752-123">When an authorized Microsoft Search user searches on [Bing](https://Bing.com) for any of the bookmark's keywords or reserved keywords, the Power App will appear in the bookmark result.</span></span>
