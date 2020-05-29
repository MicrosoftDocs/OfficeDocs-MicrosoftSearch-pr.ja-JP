---
title: 場所の管理
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
ms.assetid: 8ab9aa00-cd74-405f-8410-9a1c3cfacdb9
description: 時間の経過と共に、場所の情報の状態やコンテンツを更新して、関連性の高い状態を維持することが必要になる場合があります。
ms.openlocfilehash: bb229086f7dd8c1b8d17a0b8335bb618850106be
ms.sourcegitcommit: 063fec4a336b6b3118d4769a4bd0cc2d568ea7e2
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/25/2020
ms.locfileid: "42276990"
---
# <a name="manage-locations"></a><span data-ttu-id="c3f7d-103">場所の管理</span><span class="sxs-lookup"><span data-stu-id="c3f7d-103">Manage locations</span></span>

## <a name="location"></a><span data-ttu-id="c3f7d-104">場所</span><span class="sxs-lookup"><span data-stu-id="c3f7d-104">Location</span></span>

<span data-ttu-id="c3f7d-105">場所は、道順やナビゲーションとともに、オフィス、キャンパス、建物の正確な場所を提供することで、ユーザーが組織の建物の住所と場所を検索するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-105">Location helps your users find addresses and locate your organization's buildings by providing an accurate location for offices, campuses, and buildings, along with directions and navigation.</span></span> <span data-ttu-id="c3f7d-106">管理者は、組織に関するすべての重要な場所を追加する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-106">Administrators should add all important locations of your organization.</span></span> <span data-ttu-id="c3f7d-107">ブックマークや Q&A とは異なり、インデックスはすぐに更新されないため、新しい場所や変更された場所が検索結果に表示されるまでに数時間かかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-107">Unlike Bookmarks and Q&A, the index is not refreshed immediately, and it can take several hours for new or changed locations to appear in search results.</span></span>

### <a name="add-or-edit-a-single-location"></a><span data-ttu-id="c3f7d-108">1 つの場所を追加または編集する</span><span class="sxs-lookup"><span data-stu-id="c3f7d-108">Add or edit a single location</span></span>

1. <span data-ttu-id="c3f7d-109">**Microsoft 365 管理センター**に移動します。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-109">Go to **Microsoft 365 admin center**.</span></span>
1. <span data-ttu-id="c3f7d-110">ナビゲーション ウィンドウで、**[設定]** に移動して、**[Microsoft Search]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-110">In the navigation pane, go to **Settings** and select **Microsoft Search**.</span></span>
1. <span data-ttu-id="c3f7d-111">**[場所]** タブを選択します。既定では、**[Microsoft Search]** ページで **[ブックマーク]** タブが選択されています。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-111">Select **Locations** tab. By default, the **Bookmarks** tab is selected on the **Microsoft Search** page.</span></span>
1. <span data-ttu-id="c3f7d-112">新しい場所を追加するには、**[新規追加]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-112">To add a new location, select **Add new**.</span></span>
1. <span data-ttu-id="c3f7d-113">場所を編集するには、関連する場所の一覧で場所を選択します。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-113">To edit a location, select the location in the relevant locations list.</span></span>
1. <span data-ttu-id="c3f7d-114">情報を追加または編集すると、プレビューが自動的に更新されます。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-114">As you add or edit the information, the preview automatically updates.</span></span>
1. <span data-ttu-id="c3f7d-115">変更内容を保存します。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-115">Save your changes.</span></span>

### <a name="bulk-add-or-edit-locations"></a><span data-ttu-id="c3f7d-116">場所を一括して追加または編集する</span><span class="sxs-lookup"><span data-stu-id="c3f7d-116">Bulk add or edit locations</span></span>

<span data-ttu-id="c3f7d-117">管理者は、インポート機能またはエクスポート機能を使用して、場所の一括作成または一括編集が行えます。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-117">Administrators can use the Import or Export feature to bulk add or edit locations.</span></span>

<span data-ttu-id="c3f7d-118">インポート/エクスポート機能を使用して、次のことが実行できます。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-118">Use the import/export feature to:</span></span>

1. <span data-ttu-id="c3f7d-119">場所の一括追加 - 場所テンプレート ファイルに詳細を追加して、インポートします。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-119">Bulk add location - Add details in the location template file, and then import it.</span></span>
1. <span data-ttu-id="c3f7d-120">場所の一括編集 - 場所を .csv ファイルにエクスポートし、エクスポートされた .csv ファイルの場所の詳細を編集してから、更新された .csv ファイルをインポートします。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-120">Bulk edit locations - Export locations to a .csv file, then edit the location details in the exported .csv file, and then import the updated .csv file.</span></span>
1. <span data-ttu-id="c3f7d-121">バックアップの場所: 既存の場所を .csv ファイルにエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-121">Backup locations – Export existing locations to a .csv file.</span></span>

<span data-ttu-id="c3f7d-122">場所をエクスポートまたはインポートするには:</span><span class="sxs-lookup"><span data-stu-id="c3f7d-122">To export or import locations:</span></span>

1. <span data-ttu-id="c3f7d-123">**[場所]** タブの右上隅にある **[インポート]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-123">In the upper-right corner of the **Locations** tab, select **Import**.</span></span>
<span data-ttu-id="c3f7d-124">.csv ファイル内の既存の場所をダウンロードするには、**[エクスポート]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-124">Select **Export** to download the existing locations in a .csv file.</span></span>
1. <span data-ttu-id="c3f7d-125">右側のウィンドウで、.csv ファイルを使用してインポートするオプションを選択します。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-125">In the right pane, choose the option to import using a .csv file.</span></span>
<span data-ttu-id="c3f7d-126">必要なフィールドと詳細の一覧については、テンプレート ファイルをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-126">Download ehe template file for a list of the required fields and details.</span></span>
1. <span data-ttu-id="c3f7d-127">テンプレート ファイルの場所の詳細を追加または編集してから、コンピューターに保存します。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-127">Add or edit location details in the template file, and then save it on your computer.</span></span>
1. <span data-ttu-id="c3f7d-128">**[場所のインポート]** ウィンドウで、**[参照]** を選び、インポートする .csv ファイルを選択します。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-128">In the **Import** locations pane, select **Browse**, and then the .csv file that you want to import.</span></span>
1. <span data-ttu-id="c3f7d-129">**[インポート]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-129">Select **Import**.</span></span>

<span data-ttu-id="c3f7d-130">以下に、テンプレート ファイルに関する重要な点をいくつか紹介します。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-130">Here are some important points regarding the template file:</span></span>

- <span data-ttu-id="c3f7d-131">次のフィールドのデータは決して編集しないでください: *ID*、*最終更新日時*、*最終更新者*</span><span class="sxs-lookup"><span data-stu-id="c3f7d-131">Never edit data in these fields: *Id*, *Last Modified*, and *Last Modified By*</span></span>
- <span data-ttu-id="c3f7d-132">既存の場所の*Id*を指定すると、インポートファイルの情報に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-132">If you include the *Id* of an existing location, it will be replaced with the information in the import file.</span></span>
- <span data-ttu-id="c3f7d-133">同じ名前の既存の場所がある場合、その場所はインポートファイルの情報で更新されます。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-133">If there is an existing location with the same name, the location will be updated with information in the import file.</span></span>
- <span data-ttu-id="c3f7d-134">テンプレートファイルのすべてのフィールドが必須であるわけではなく、場所の状態によって必須のフィールドが異なる場合があります。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-134">Not all fields in the template file are required and required fields vary depending on the location state.</span></span>
- <span data-ttu-id="c3f7d-135">[*状態*] フィールドに基づいて、場所が下書き、提案済み、スケジュール済み、または自動的に公開されるように保存されます。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-135">Based on the *State* field, locations will be saved as draft, suggested, scheduled, or they will be published automatically.</span></span>
- <span data-ttu-id="c3f7d-136">複数の組織を管理するパートナーは、1つの組織からの場所をエクスポートして、別の組織にインポートすることができます。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-136">For partners who manage multiple organizations, you can export your locations from one org and import them into another.</span></span> <span data-ttu-id="c3f7d-137">ただし、インポートする前に *ID* 列のデータを削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-137">But you must remove the data in the *Id* column before you import.</span></span>

<span data-ttu-id="c3f7d-138">**注:** テンプレート ファイルにエラーがある場合は、場所をインポートすることはできません。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-138">**Note:** You cannot import Locations if there are any errors in the template file.</span></span> <span data-ttu-id="c3f7d-139">エラーを回避するには、インポート ファイルが正しく書式設定されていて、必要な情報がすべて含まれていることを確認してください。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-139">To prevent errors, make sure your import file is properly formatted and include all the required information.</span></span>

<span data-ttu-id="c3f7d-140">エラーを回避する方法の詳細については、「[インポート エラーを回避する](manage-bookmarks.md#prevent-import-errors)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c3f7d-140">For more information on how to prevent error, see [Prevent import errors](manage-bookmarks.md#prevent-import-errors).</span></span>
