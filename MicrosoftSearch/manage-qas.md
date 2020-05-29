---
title: Q&A の管理
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
ms.assetid: 7e3432e6-5317-4d63-90b0-52da6fddd343
description: 回答を個別に検索して更新するか、利用可能な Microsoft Search のツールを使用して一括ですべての回答を編集します
ms.openlocfilehash: 0877de027b68589e5ba15cd8109ea7edeeae8725
ms.sourcegitcommit: c22e8c3dcc53857da677db98a1a2b7d5ca2c6170
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/04/2020
ms.locfileid: "41721743"
---
# <a name="manage-qas"></a><span data-ttu-id="aada6-103">Q&A の管理</span><span class="sxs-lookup"><span data-stu-id="aada6-103">Manage Q&As</span></span>

<span data-ttu-id="aada6-104">Q&A の作成は、ブックマークの作成と似ています。</span><span class="sxs-lookup"><span data-stu-id="aada6-104">Creating a Q&A is similar to creating bookmarks.</span></span> <span data-ttu-id="aada6-105">Q&A では、Web ページへのリンクを提供するだけではなく、ユーザーの質問に回答することができます。</span><span class="sxs-lookup"><span data-stu-id="aada6-105">Q&A allows you to answer the user's question instead of just providing a link to webpage.</span></span> <span data-ttu-id="aada6-106">利用可能なツールを使用して、回答をリッチ テキスト形式にすることができます。</span><span class="sxs-lookup"><span data-stu-id="aada6-106">You can format the answer in rich text using the available tools.</span></span> <span data-ttu-id="aada6-107">ブックマークと Q&A が同じキーワードを共有している場合は、ブックマークの結果が最初に表示されます。</span><span class="sxs-lookup"><span data-stu-id="aada6-107">If a Bookmark and a Q&A share the same keyword, the Bookmark result is shown first.</span></span> <span data-ttu-id="aada6-108">ブックマークと同様に、Q&A インデックスは Q&A が追加または変更された直後に更新されます。</span><span class="sxs-lookup"><span data-stu-id="aada6-108">Like Bookmarks, the Q&A index is refreshed immediately after a Q&A is added or changed.</span></span>

## <a name="add-or-edit-a-single-qa"></a><span data-ttu-id="aada6-109">1 つの Q&A を追加または編集する</span><span class="sxs-lookup"><span data-stu-id="aada6-109">Add or edit a single Q&A</span></span>

1. <span data-ttu-id="aada6-110">**Microsoft 365 管理センター**に移動します。</span><span class="sxs-lookup"><span data-stu-id="aada6-110">Go to **Microsoft 365 admin center**.</span></span>
1. <span data-ttu-id="aada6-111">ナビゲーション ウィンドウで、**[設定]** に移動して、**[Microsoft Search]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="aada6-111">In the navigation pane, go to **Settings** and select **Microsoft Search**.</span></span>
1. <span data-ttu-id="aada6-112">**[Q&A]** タブを選択します。既定では、最初のタブ (**ブックマーク**) が選択されています。</span><span class="sxs-lookup"><span data-stu-id="aada6-112">Select **Q&A** tab. By default, the first tab (**Bookmarks**) is selected.</span></span>
1. <span data-ttu-id="aada6-113">Q&A を追加するには、**[新規追加]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="aada6-113">To add a Q&A, select **Add new**.</span></span>
<span data-ttu-id="aada6-114">Q&A を編集するには、関連する Q&A の一覧で Q&A を選択します。</span><span class="sxs-lookup"><span data-stu-id="aada6-114">To edit a Q&A, select the Q&A in the relevant Q&A list.</span></span>
1. <span data-ttu-id="aada6-115">情報を追加または編集すると、プレビューが自動的に更新されます。</span><span class="sxs-lookup"><span data-stu-id="aada6-115">As you add or edit the information, the preview automatically updates.</span></span>
1. <span data-ttu-id="aada6-116">変更内容を保存します。</span><span class="sxs-lookup"><span data-stu-id="aada6-116">Save your changes.</span></span>

### <a name="supported-html-tags"></a><span data-ttu-id="aada6-117">サポートされている HTML タグ</span><span class="sxs-lookup"><span data-stu-id="aada6-117">Supported HTML tags</span></span>

<span data-ttu-id="aada6-118">回答 (説明) に既存の HTML コンテンツを使用したり、HTML タグを追加したりできます。</span><span class="sxs-lookup"><span data-stu-id="aada6-118">You can use existing HTML content or add HTML tags to your answer (description).</span></span> <span data-ttu-id="aada6-119">サポート対象外のタグは無視されます。</span><span class="sxs-lookup"><span data-stu-id="aada6-119">Unsupported tags are ignored.</span></span>  
<span data-ttu-id="aada6-120">次の HTML タグがサポートされています。</span><span class="sxs-lookup"><span data-stu-id="aada6-120">The following HTML tags are supported:</span></span>

- <span data-ttu-id="aada6-121">blockquote</span><span class="sxs-lookup"><span data-stu-id="aada6-121">blockquote</span></span>
- <span data-ttu-id="aada6-122">div</span><span class="sxs-lookup"><span data-stu-id="aada6-122">div</span></span>
- <span data-ttu-id="aada6-123">em</span><span class="sxs-lookup"><span data-stu-id="aada6-123">em</span></span>
- <span data-ttu-id="aada6-124">h1、h2、h3、h4</span><span class="sxs-lookup"><span data-stu-id="aada6-124">h1, h2, h3, and h4</span></span>
- <span data-ttu-id="aada6-125">ol、ul、li</span><span class="sxs-lookup"><span data-stu-id="aada6-125">ol, ul, and li</span></span>
- <span data-ttu-id="aada6-126">p</span><span class="sxs-lookup"><span data-stu-id="aada6-126">p</span></span>
- <span data-ttu-id="aada6-127">pre</span><span class="sxs-lookup"><span data-stu-id="aada6-127">pre</span></span>
- <span data-ttu-id="aada6-128">span</span><span class="sxs-lookup"><span data-stu-id="aada6-128">span</span></span>
- <span data-ttu-id="aada6-129">strong</span><span class="sxs-lookup"><span data-stu-id="aada6-129">strong</span></span>
- <span data-ttu-id="aada6-130">table、thead、tbody、tr、th、td</span><span class="sxs-lookup"><span data-stu-id="aada6-130">table, thead, tbody, tr, th, and td</span></span>
- <span data-ttu-id="aada6-131">u</span><span class="sxs-lookup"><span data-stu-id="aada6-131">u</span></span>
- <span data-ttu-id="aada6-132">a</span><span class="sxs-lookup"><span data-stu-id="aada6-132">a</span></span>
- <span data-ttu-id="aada6-133">code</span><span class="sxs-lookup"><span data-stu-id="aada6-133">code</span></span>
- <span data-ttu-id="aada6-134">br</span><span class="sxs-lookup"><span data-stu-id="aada6-134">br</span></span>
- <span data-ttu-id="aada6-135">hr</span><span class="sxs-lookup"><span data-stu-id="aada6-135">hr</span></span>
- <span data-ttu-id="aada6-136">img</span><span class="sxs-lookup"><span data-stu-id="aada6-136">img</span></span>

## <a name="add-or-edit-qas-using-browser-extensions"></a><span data-ttu-id="aada6-137">ブラウザー拡張機能を使用して Q&を追加または編集する</span><span class="sxs-lookup"><span data-stu-id="aada6-137">Add or edit Q&As using browser extensions</span></span>

<span data-ttu-id="aada6-138">検索管理者は、ブラウザーの拡張機能を使用して検索コンテンツを簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="aada6-138">Search administrators can create search content easily by using browser extensions.</span></span> <span data-ttu-id="aada6-139">ブラウザー拡張機能をインストールして、Q&A を生成するサイトに移動します。</span><span class="sxs-lookup"><span data-stu-id="aada6-139">Install the browser extension and then go to the site from which you want to generate a Q&A.</span></span> <span data-ttu-id="aada6-140">その後、Q&A を作成し、ソースサイトへのリンクを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="aada6-140">You can then create the Q&A and include a link to the source site.</span></span>

<span data-ttu-id="aada6-141">現在、ブラウザーの拡張機能は Edge と Chrome で利用できます。</span><span class="sxs-lookup"><span data-stu-id="aada6-141">Currently, browser extensions are available for Edge and Chrome.</span></span>

- <span data-ttu-id="aada6-142">エッジ拡張機能をダウンロードするには、 [Microsoft ストア](https://www.microsoft.com/p/microsoft-search-content-creator/9nrqdbcbwq55?activetab=pivot:overviewtab)に移動して、アプリをダウンロードしてください。</span><span class="sxs-lookup"><span data-stu-id="aada6-142">To download Edge extensions, go to [Microsoft Store](https://www.microsoft.com/p/microsoft-search-content-creator/9nrqdbcbwq55?activetab=pivot:overviewtab) and download the app.</span></span>
- <span data-ttu-id="aada6-143">Chrome 拡張機能をダウンロードするには、 [chrome web store](https://chrome.google.com/webstore/detail/microsoft-search-content/nocnablpaoeecfmfnjoheefkogmleipm)に移動し、アプリをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="aada6-143">To download Chrome extensions, go to [Chrome web store](https://chrome.google.com/webstore/detail/microsoft-search-content/nocnablpaoeecfmfnjoheefkogmleipm) and download the app.</span></span>

## <a name="bulk-add-or-edit-qas"></a><span data-ttu-id="aada6-144">Q&A を一括して追加または編集する</span><span class="sxs-lookup"><span data-stu-id="aada6-144">Bulk add or edit Q&As</span></span>

<span data-ttu-id="aada6-145">管理者は、インポート機能とエクスポート機能を使用して、Q&A の一括作成または一括編集が行えます。</span><span class="sxs-lookup"><span data-stu-id="aada6-145">Administrators can use the Import and Export features to bulk create or edit Q&A.</span></span> <span data-ttu-id="aada6-146">これは、管理者が多数の Q&A を追加または編集する必要がある場合に便利な機能です。</span><span class="sxs-lookup"><span data-stu-id="aada6-146">This is a useful feature when administrators need to add or edit a large number of Q&A.</span></span>

<span data-ttu-id="aada6-147">インポート/エクスポート機能を使用して、次のことが実行できます。</span><span class="sxs-lookup"><span data-stu-id="aada6-147">Use the import/export feature to:</span></span>

1. <span data-ttu-id="aada6-148">Q&A の一括追加 - Q&A テンプレート ファイルに詳細を追加して、インポートします。</span><span class="sxs-lookup"><span data-stu-id="aada6-148">Bulk add Q&A - Add details in the Q&A template file, and then import it.</span></span>
1. <span data-ttu-id="aada6-149">Q&A の一括編集 - Q&A を .csv ファイルにエクスポートし、エクスポートされた .csv ファイルの Q&A の詳細を編集してから、.csv ファイルをインポートします。</span><span class="sxs-lookup"><span data-stu-id="aada6-149">Bulk edit Q&A - Export Q&A to a .csv file, then edit the Q&A details in the exported .csv file, and then import the .csv file.</span></span>
1. <span data-ttu-id="aada6-150">Q&A のバックアップ - Q&A を .csv ファイルにエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="aada6-150">Backup Q&A - Export Q&A to a .csv file.</span></span>

<span data-ttu-id="aada6-151">Q&A をインポートまたはエクスポートするには:</span><span class="sxs-lookup"><span data-stu-id="aada6-151">To import or export Q&A:</span></span>

1. <span data-ttu-id="aada6-152">[Q&A] タブの右上隅にある **[インポート]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="aada6-152">In the upper-right corner of the Q&A tab, select **Import**.</span></span>
<span data-ttu-id="aada6-153">.csv ファイル内の既存の Q&A をすべてダウンロードするには、**[エクスポート]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="aada6-153">Select **Export** to download all the existing Q&A in a .csv file.</span></span>
1. <span data-ttu-id="aada6-154">右側のウィンドウで、.csv ファイルを使用してインポートするオプションを選択します。</span><span class="sxs-lookup"><span data-stu-id="aada6-154">In the right pane, choose the option to import using a .csv file.</span></span>
<span data-ttu-id="aada6-155">必要なフィールドと詳細の一覧については、テンプレート ファイルをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="aada6-155">Download the template file for a list of the required fields and details.</span></span>
1. <span data-ttu-id="aada6-156">テンプレート ファイルの Q&A の詳細を追加または編集して、コンピューターに保存します。</span><span class="sxs-lookup"><span data-stu-id="aada6-156">Add or edit Q&A details in the template file and save it on your computer.</span></span>
1. <span data-ttu-id="aada6-157">**[Q&A のインポート]** ウィンドウで、**[参照]** を選び、インポートする .csv ファイルを選択します。</span><span class="sxs-lookup"><span data-stu-id="aada6-157">In the **Import Q&A** pane, select **Browse**, and then the .csv file that you want to import.</span></span>
1. <span data-ttu-id="aada6-158">**[インポート]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="aada6-158">Select **Import**.</span></span>

<span data-ttu-id="aada6-159">以下に、テンプレート ファイルに関する重要な点をいくつか紹介します。</span><span class="sxs-lookup"><span data-stu-id="aada6-159">Here are some important points regarding the template file:</span></span>

- <span data-ttu-id="aada6-160">次のフィールドのデータは決して編集しないでください: *ID*、*最終更新日時*、*最終更新者*</span><span class="sxs-lookup"><span data-stu-id="aada6-160">Never edit data in these fields: *Id*, *Last Modified*, and *Last Modified By*</span></span>
- <span data-ttu-id="aada6-161">既存のブックマークの *ID* を含めると、インポート ファイルの情報に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="aada6-161">If you include the *Id* of an existing bookmark, it will be replaced with the information in the import file.</span></span>
- <span data-ttu-id="aada6-162">同じタイトルまたは URL を持つ既存のブックマークがある場合は、そのブックマークはインポート ファイル内の情報で更新されます。</span><span class="sxs-lookup"><span data-stu-id="aada6-162">If there is an existing bookmark with the same title or URL, the bookmark will be updated with information in the import file.</span></span>
- <span data-ttu-id="aada6-163">テンプレート ファイルのすべてのフィールドが必要なわけではなく、ブックマークの状態によって必要なフィールドは変わります。</span><span class="sxs-lookup"><span data-stu-id="aada6-163">Not all fields in the template file are required and required fields vary depending on the bookmark state.</span></span>
- <span data-ttu-id="aada6-164">状態フィールドに基づいて、ブックマークは、下書き、おすすめ、スケジュール済みとして保存されるか、自動的に公開されます。</span><span class="sxs-lookup"><span data-stu-id="aada6-164">Based on the State field, bookmarks will be saved as draft, suggested, scheduled, or they will be published automatically.</span></span>
- <span data-ttu-id="aada6-165">複数の組織を管理するパートナーは、1つの組織からブックマークをエクスポートして、別の組織にインポートすることができます。</span><span class="sxs-lookup"><span data-stu-id="aada6-165">For partners who manage multiple organizations, you can export your bookmarks from one org and import them into another.</span></span> <span data-ttu-id="aada6-166">ただし、インポートする前に *ID* 列のデータを削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="aada6-166">But you must remove the data in the *Id* column before you import.</span></span>

<span data-ttu-id="aada6-167">**注:** テンプレート ファイルにエラーがある場合は、Q&A をインポートすることはできません。</span><span class="sxs-lookup"><span data-stu-id="aada6-167">**Note:** You cannot import Q&A if there are any errors in the template file.</span></span> <span data-ttu-id="aada6-168">エラーを回避するには、インポート ファイルが正しく書式設定されていて、必要な情報がすべて含まれていることを確認してください。</span><span class="sxs-lookup"><span data-stu-id="aada6-168">To prevent errors, make sure your import file is properly formatted and include all the required information.</span></span>

<span data-ttu-id="aada6-169">エラーを回避する方法の詳細については、「[インポート エラーを回避する](manage-bookmarks.md#prevent-import-errors)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="aada6-169">For more information on how to prevent error, see [Prevent import errors](manage-bookmarks.md#prevent-import-errors).</span></span>
