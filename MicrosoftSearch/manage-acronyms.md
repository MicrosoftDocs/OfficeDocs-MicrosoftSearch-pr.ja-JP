---
title: Microsoft Search で頭字語の回答を管理する
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
description: Microsoft Search で頭字語の回答を作成および更新する
ms.openlocfilehash: af5b82aa2c578fde67a36980cfceef131f605b4e
ms.sourcegitcommit: d4f49d51fa7d07b3bfd9ba93ed14f4c46d310154
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/29/2020
ms.locfileid: "44412677"
---
# <a name="manage-acronyms-answers-in-microsoft-search"></a><span data-ttu-id="2ae18-103">Microsoft Search で頭字語の回答を管理する</span><span class="sxs-lookup"><span data-stu-id="2ae18-103">Manage Acronyms answers in Microsoft Search</span></span>

<span data-ttu-id="2ae18-104">ユーザーは、組織やチームによって使用される見慣れない頭字語や略語を使用することがよくあります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-104">Users often run into unfamiliar acronyms and abbreviations used by their organization or team.</span></span> <span data-ttu-id="2ae18-105">組織またはチームに固有の用語は、チーム間の移行、社内パートナーと連携しているユーザー、または組織にとって新しいユーザーにとって新しいものである場合があります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-105">Terms that are specific to organizations or teams might be new to people who move from one team to another, those who work with internal partner teams, or are new to the organization.</span></span>

<span data-ttu-id="2ae18-106">組織では、標準的な用語を常に参照することはありません。</span><span class="sxs-lookup"><span data-stu-id="2ae18-106">Organizations don't always have a single reference for their standard terminology.</span></span> <span data-ttu-id="2ae18-107">単一の参照がないと、これらの略語の定義や拡張を見つけるのが困難になります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-107">Lack of a single reference makes it hard to find definitions or expansions for these acronyms.</span></span> <span data-ttu-id="2ae18-108">Microsoft Search は、頭字語に問題があることを解決します。</span><span class="sxs-lookup"><span data-stu-id="2ae18-108">Microsoft Search solves that problem with Acronyms.</span></span>

## <a name="what-users-experience"></a><span data-ttu-id="2ae18-109">ユーザーの作業</span><span class="sxs-lookup"><span data-stu-id="2ae18-109">What users experience</span></span>
<span data-ttu-id="2ae18-110">Microsoft 検索ユーザーは、 [Bing](https://Bing.com)で頭字語を使用して定義を取得できます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-110">Microsoft Search users can get definitions with Acronyms in [Bing](https://Bing.com).</span></span> <span data-ttu-id="2ae18-111">**検索**ボックスには、次の例のようなクエリが入力されます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-111">In the **Search** box, users enter queries like these examples:</span></span>

- <span data-ttu-id="2ae18-112">*機能*DNN</span><span class="sxs-lookup"><span data-stu-id="2ae18-112">*What is* DNN</span></span>
- <span data-ttu-id="2ae18-113">を*定義*するDNN</span><span class="sxs-lookup"><span data-stu-id="2ae18-113">*Define* DNN</span></span>
- <span data-ttu-id="2ae18-114">DNN*定義*</span><span class="sxs-lookup"><span data-stu-id="2ae18-114">DNN *definition*</span></span>
- <span data-ttu-id="2ae18-115">*展開*DNN</span><span class="sxs-lookup"><span data-stu-id="2ae18-115">*Expand* DNN</span></span>
- <span data-ttu-id="2ae18-116">DNN*拡張*</span><span class="sxs-lookup"><span data-stu-id="2ae18-116">DNN *expansion*</span></span>
- <span data-ttu-id="2ae18-117">*の意味*DNN</span><span class="sxs-lookup"><span data-stu-id="2ae18-117">*Meaning of* DNN</span></span>
- <span data-ttu-id="2ae18-118">DNN*は*</span><span class="sxs-lookup"><span data-stu-id="2ae18-118">DNN *means*</span></span>

<span data-ttu-id="2ae18-119">結果には、ユーザーの組織内に存在する DNN のすべての意味が含まれます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-119">The result includes all the meanings of DNN that are present within the user’s organization.</span></span>

> [!NOTE]
> <span data-ttu-id="2ae18-120">ユーザーは、頭字語の指定された*キーワード*を含むクエリを入力して、対応する回答をトリガーする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-120">Users must enter a query that includes the acronym’s specified *keywords* to trigger its corresponding answers.</span></span> <span data-ttu-id="2ae18-121">頭字語のクエリでは大文字と小文字は区別されません。</span><span class="sxs-lookup"><span data-stu-id="2ae18-121">Acronym queries are not case sensitive.</span></span> 

## <a name="set-up-acronyms-answers"></a><span data-ttu-id="2ae18-122">頭字語の回答を設定する</span><span class="sxs-lookup"><span data-stu-id="2ae18-122">Set up Acronyms answers</span></span>
<span data-ttu-id="2ae18-123">Microsoft 365[管理センター](https://admin.microsoft.com)で、[microsoft Search の**設定**] に移動し、[頭字語の  >  **Microsoft Search**  > **Acronyms\*\*\*\*追加**] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2ae18-123">In the Microsoft 365 [admin center](https://admin.microsoft.com), go to **Settings** > **Microsoft Search** >**Acronyms**, and then select **Add acronyms**.</span></span> 

<span data-ttu-id="2ae18-124">Microsoft Search では、ユーザーの検索に頭字語の回答を提供するために2つのデータソースをクエリします。</span><span class="sxs-lookup"><span data-stu-id="2ae18-124">Microsoft Search queries two data sources to provide Acronyms answers to users’ searches:</span></span>

1.  <span data-ttu-id="2ae18-125">**編集の略語**</span><span class="sxs-lookup"><span data-stu-id="2ae18-125">**Editorial acronyms**.</span></span> <span data-ttu-id="2ae18-126">[管理センター](https://admin.microsoft.com)の IT 管理者によって提供されます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-126">Provided by IT administrators in the [admin center](https://admin.microsoft.com).</span></span>
2.  <span data-ttu-id="2ae18-127">抽出した**略語**。</span><span class="sxs-lookup"><span data-stu-id="2ae18-127">**Mined acronyms**.</span></span> <span data-ttu-id="2ae18-128">ユーザーの個人電子メールやドキュメントから組織内の一般に利用可能なデータから、Microsoft Search によってマイニングされます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-128">Mined by Microsoft Search from the user’s personal email and documents and publicly available data within the organization.</span></span>

### <a name="set-up-editorial-acronyms"></a><span data-ttu-id="2ae18-129">編集の略語を設定する</span><span class="sxs-lookup"><span data-stu-id="2ae18-129">Set up editorial acronyms</span></span>
<span data-ttu-id="2ae18-130">検索管理者は、 [Microsoft 365 管理センター]( https://admin.microsoft.com)の [[頭字] タブ](https://admin.microsoft.com/Adminportal/Home#/MicrosoftSearch)で編集の略語を設定できます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-130">Search administrators can set up editorial acronyms on the [Acronyms tab](https://admin.microsoft.com/Adminportal/Home#/MicrosoftSearch) in the  [Microsoft 365 admin center]( https://admin.microsoft.com).</span></span> <span data-ttu-id="2ae18-131">任意の内部サイトまたはリポジトリから管理センターに頭字語を追加することができます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-131">You can add acronyms from any internal site or repository to the admin center.</span></span> <span data-ttu-id="2ae18-132">編集の略語は、**発行済み**または**下書き**の状態に追加できます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-132">Editorial acronyms can be added to **Published** or **Draft** state:</span></span>

<span data-ttu-id="2ae18-133">**公開**された状態。</span><span class="sxs-lookup"><span data-stu-id="2ae18-133">**Published state**.</span></span> <span data-ttu-id="2ae18-134">頭字語は、組織の従業員が Microsoft Search を通じて使用できます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-134">Acronyms are available to the organization’s employees through Microsoft Search.</span></span>

> [!NOTE]
> <span data-ttu-id="2ae18-135">発行済みの状態に追加された頭字語が Microsoft Search で利用できるようになるまで、最大で3日かかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-135">It might take up to three days for acronyms added to Published state to become available in Microsoft Search.</span></span>

<span data-ttu-id="2ae18-136">**下書きの状態**です。</span><span class="sxs-lookup"><span data-stu-id="2ae18-136">**Draft state**.</span></span> <span data-ttu-id="2ae18-137">Microsoft Search で使用できるようにする前に、管理者が頭字語の回答を確認する必要がある場合は、略語を下書き状態に追加できます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-137">If admins want to review Acronyms answers before making them available in Microsoft Search, they can add the acronyms to Draft state.</span></span> <span data-ttu-id="2ae18-138">下書き状態に追加された頭字語は、Microsoft Search では使用できません。</span><span class="sxs-lookup"><span data-stu-id="2ae18-138">Acronyms added to Draft state aren’t available in Microsoft Search.</span></span> <span data-ttu-id="2ae18-139">管理者は、略語を公開済み状態に追加して利用できるようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-139">Admins need to add the acronyms to Published state to make them available.</span></span>

<span data-ttu-id="2ae18-140">管理者は、頭文字を個別に追加するか、または CSV ファイルに一括インポートすることができます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-140">Admins can add acronyms individually or bulk import them in a CSV file.</span></span> <span data-ttu-id="2ae18-141">次の表に示すフィールドを使用して CSV ファイルをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="2ae18-141">Upload a CSV file with the fields shown in the following table:</span></span>

| <span data-ttu-id="2ae18-142">頭字語 (必須)</span><span class="sxs-lookup"><span data-stu-id="2ae18-142">Acronym (mandatory)</span></span> | <span data-ttu-id="2ae18-143">拡張 (必須)</span><span class="sxs-lookup"><span data-stu-id="2ae18-143">Expansion (mandatory)</span></span> | <span data-ttu-id="2ae18-144">説明</span><span class="sxs-lookup"><span data-stu-id="2ae18-144">Description</span></span>  | <span data-ttu-id="2ae18-145">ソース</span><span class="sxs-lookup"><span data-stu-id="2ae18-145">Source</span></span> | <span data-ttu-id="2ae18-146">状態 (必須)</span><span class="sxs-lookup"><span data-stu-id="2ae18-146">State (mandatory)</span></span> |
| --------- | --------- | ---------- | --------- |--------- |
| <span data-ttu-id="2ae18-147">*xxx*</span><span class="sxs-lookup"><span data-stu-id="2ae18-147">*XXX*</span></span> | <span data-ttu-id="2ae18-148">*スペルミスの省略形*</span><span class="sxs-lookup"><span data-stu-id="2ae18-148">*Spelled out abbreviation*</span></span> |  | <span data-ttu-id="2ae18-149">*URL*</span><span class="sxs-lookup"><span data-stu-id="2ae18-149">*URL*</span></span> | <span data-ttu-id="2ae18-150">*公開または下書き*</span><span class="sxs-lookup"><span data-stu-id="2ae18-150">*Published or Draft*</span></span> |

### <a name="csv-fields"></a><span data-ttu-id="2ae18-151">CSV フィールド</span><span class="sxs-lookup"><span data-stu-id="2ae18-151">CSV fields</span></span>
<span data-ttu-id="2ae18-152">**頭字語**</span><span class="sxs-lookup"><span data-stu-id="2ae18-152">**Acronym**.</span></span> <span data-ttu-id="2ae18-153">実際の短い形式または頭字語を含みます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-153">Contains the actual short form or acronym.</span></span> <span data-ttu-id="2ae18-154">例として、 *Dnn*が挙げられます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-154">An example is *DNN*.</span></span>

<span data-ttu-id="2ae18-155">**拡張**。</span><span class="sxs-lookup"><span data-stu-id="2ae18-155">**Expansion**.</span></span> <span data-ttu-id="2ae18-156">頭字語の拡張が含まれています。</span><span class="sxs-lookup"><span data-stu-id="2ae18-156">Contains the expansion of the acronym.</span></span> <span data-ttu-id="2ae18-157">例としては、*ディープニューラルネットワーク*があります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-157">An example is *Deep Neural Network*.</span></span>

<span data-ttu-id="2ae18-158">**説明**。</span><span class="sxs-lookup"><span data-stu-id="2ae18-158">**Description**.</span></span> <span data-ttu-id="2ae18-159">頭字語とその拡張の意味をユーザーにすばやく理解できるようにするための、略語の簡単な説明。</span><span class="sxs-lookup"><span data-stu-id="2ae18-159">A brief description of the acronym that gives users quick insight into what the acronym and its expansion mean.</span></span> <span data-ttu-id="2ae18-160">たとえば、*深いニューラルネットワークとは、一定レベルの複雑な、3つ以上のレイヤーを持つニューラルネットワークのニューラルネットワーク*のことです。</span><span class="sxs-lookup"><span data-stu-id="2ae18-160">For example, *A deep neural network is a neural network with a certain level of complexity, a neural network with more than two layers*.</span></span>

<span data-ttu-id="2ae18-161">**ソース**。</span><span class="sxs-lookup"><span data-stu-id="2ae18-161">**Source**.</span></span> <span data-ttu-id="2ae18-162">頭字語の詳細については、ユーザーが移動するページまたは web サイトの URL。</span><span class="sxs-lookup"><span data-stu-id="2ae18-162">The URL of the page or website where you want users to go for more information about the acronym.</span></span>

<span data-ttu-id="2ae18-163">**状態**。</span><span class="sxs-lookup"><span data-stu-id="2ae18-163">**State**.</span></span> <span data-ttu-id="2ae18-164">このフィールドには、次の2つの値を指定できます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-164">This field can take two values:</span></span>

- <span data-ttu-id="2ae18-165">**下書き**。</span><span class="sxs-lookup"><span data-stu-id="2ae18-165">**Draft**.</span></span> <span data-ttu-id="2ae18-166">頭字語を下書き状態に追加します。</span><span class="sxs-lookup"><span data-stu-id="2ae18-166">Adds  the acronym to the Draft state.</span></span>
- <span data-ttu-id="2ae18-167">**発行済み**。</span><span class="sxs-lookup"><span data-stu-id="2ae18-167">**Published**.</span></span> <span data-ttu-id="2ae18-168">頭字語を公開された状態に追加し、Microsoft Search で使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="2ae18-168">Adds the acronym to the Published state and makes it available in Microsoft Search.</span></span>

### <a name="mined-acronyms"></a><span data-ttu-id="2ae18-169">マイニング頭字語</span><span class="sxs-lookup"><span data-stu-id="2ae18-169">Mined acronyms</span></span>
<span data-ttu-id="2ae18-170">管理者が組織内で使用されているすべての略語を回答に追加することが課題となる場合があります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-170">It might be a challenge for admins to add all the acronyms used within an organization to Answers.</span></span> <span data-ttu-id="2ae18-171">この機能は、検索管理者が認識していない略語を見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-171">This feature can find acronyms that search administrators aren’t even aware of.</span></span> <span data-ttu-id="2ae18-172">この作業を行うために、Microsoft Search では、これらのソースからの略語も地雷しています。</span><span class="sxs-lookup"><span data-stu-id="2ae18-172">To do that work, Microsoft Search also mines acronyms from these sources:</span></span>

- <span data-ttu-id="2ae18-173">ユーザーの電子メール。</span><span class="sxs-lookup"><span data-stu-id="2ae18-173">Users’ emails.</span></span>
- <span data-ttu-id="2ae18-174">[SharePoint](https://products.office.com/sharepoint/collaboration)、 [Microsoft OneDrive]( https://onedrive.live.com/about/) 、 [microsoft OneNote](http://www.onenote.com/)のドキュメント。</span><span class="sxs-lookup"><span data-stu-id="2ae18-174">Documents in [SharePoint](https://products.office.com/sharepoint/collaboration), [Microsoft OneDrive]( https://onedrive.live.com/about/) and [Microsoft OneNote](http://www.onenote.com/).</span></span>
- <span data-ttu-id="2ae18-175">ユーザーが SharePoint、OneDrive、または OneNote でアクセスできる組織内のパブリックドキュメント。</span><span class="sxs-lookup"><span data-stu-id="2ae18-175">Public documents within the organization that users have access to in SharePoint, OneDrive, or OneNote.</span></span>

<span data-ttu-id="2ae18-176">Microsoft Search を使用すると、ドキュメントに対するアクセスとアクセス許可を持つユーザーのみが、その文書から抽出された頭字語を表示できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-176">Microsoft Search makes sure that only users with access and permissions to a document can see the acronyms that are mined from it.</span></span> <span data-ttu-id="2ae18-177">頭字語がユーザーのメールボックスからマイニングされる場合、そのユーザーのみがその略語を表示できます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-177">When an acronym is mined from a user's mailbox, only that user can see that acronym.</span></span>

> [!NOTE]
> <span data-ttu-id="2ae18-178">マイニングされた頭字語にはセットアップは必要ありません。</span><span class="sxs-lookup"><span data-stu-id="2ae18-178">No setup is needed for mined acronyms.</span></span>

## <a name="frequently-asked-questions"></a><span data-ttu-id="2ae18-179">よく寄せられる質問</span><span class="sxs-lookup"><span data-stu-id="2ae18-179">Frequently asked questions</span></span>
<span data-ttu-id="2ae18-180">**Q: どのように編集とマイニングされたデータがランク付けされるのですか?**</span><span class="sxs-lookup"><span data-stu-id="2ae18-180">**Q: How is editorial and mined data ranked?**</span></span>

<span data-ttu-id="2ae18-181">**A:** 現在、機能は、抽出された略語の上に編集上の略語をランク付けします。</span><span class="sxs-lookup"><span data-stu-id="2ae18-181">**A:** The feature currently ranks editorial acronyms above mined acronyms.</span></span>

<span data-ttu-id="2ae18-182">**Q: 発行後に編集者の略語が Microsoft Search に表示されるまでにどのくらいの時間がかかりますか?**</span><span class="sxs-lookup"><span data-stu-id="2ae18-182">**Q: How long does it take for editorial acronyms to be visible in Microsoft Search after they’re published?**</span></span>

<span data-ttu-id="2ae18-183">**A:** 発行済みの状態に追加された頭字語が Microsoft Search で利用できるようになるまでに最大3日間かかります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-183">**A:**  It takes up to three days for acronyms added to Published state to become available in Microsoft Search.</span></span> 

<span data-ttu-id="2ae18-184">**Q: ユーザーが頭字語の回答を開始する方法を教えてください。**</span><span class="sxs-lookup"><span data-stu-id="2ae18-184">**Q: How do users trigger Acronyms answers?**</span></span>

<span data-ttu-id="2ae18-185">**A**: 頭字語の回答を取得するには、ユーザーは[Bing](https://bing.com) **検索**ボックスに特定のクエリパターンを入力する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-185">**A**: To get Acronyms answers, users must enter specific query patterns in a [Bing](https://bing.com) **Search** box.</span></span> <span data-ttu-id="2ae18-186">現時点では、 [Office 365](https://Office.com)または[SharePoint](https://products.office.com/sharepoint/collaboration)では、頭字語の回答は使用できません。</span><span class="sxs-lookup"><span data-stu-id="2ae18-186">Currently, Acronym answers aren't available in [Office 365](https://Office.com) or [SharePoint](https://products.office.com/sharepoint/collaboration).</span></span>

<span data-ttu-id="2ae18-187">**Q: 新しい電子メールやドキュメントを受信または送信した後に、マイニングされた頭字語が表示されるまでにどのくらいの時間がかかりますか?**</span><span class="sxs-lookup"><span data-stu-id="2ae18-187">**Q: How long does it take for mined acronyms to appear after you receive or send a new email or document?**</span></span>

<span data-ttu-id="2ae18-188">**A:** 新しい電子メールまたはドキュメントから抽出された略語は、Microsoft 検索結果に表示されるまでに最大7日間かかります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-188">**A:** Mined acronyms from a new email or document take up to seven days to appear in Microsoft Search results.</span></span>

<span data-ttu-id="2ae18-189">**Q: ドキュメントを選択するために、ドキュメントをマイニングの特定の形式にする必要がありますか。**</span><span class="sxs-lookup"><span data-stu-id="2ae18-189">**Q: Do documents need to be in a specific format for mining to pick them up?**</span></span>

<span data-ttu-id="2ae18-190">**A:** 違います。</span><span class="sxs-lookup"><span data-stu-id="2ae18-190">**A:** No.</span></span> <span data-ttu-id="2ae18-191">画像、フォルダー、および zip ファイル以外のすべてのファイルの種類をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="2ae18-191">We support all file types except image, folders, and zip files.</span></span>

<span data-ttu-id="2ae18-192">**Q: Microsoft はすべての言語のドキュメントから頭字語を地雷していますか?**</span><span class="sxs-lookup"><span data-stu-id="2ae18-192">**Q: Will Microsoft mine acronyms from documents in all languages?**</span></span>

<span data-ttu-id="2ae18-193">**A**: Microsoft は、ドキュメントからのマイニングのみを英語でサポートしています。</span><span class="sxs-lookup"><span data-stu-id="2ae18-193">**A**: Microsoft only supports mining from documents in English.</span></span> <span data-ttu-id="2ae18-194">他の言語のサポートは、フェーズで追加されます。</span><span class="sxs-lookup"><span data-stu-id="2ae18-194">Support for other languages will be added in phases.</span></span>

<span data-ttu-id="2ae18-195">**Q: 組織でマイニングされた頭字語を表示したくない場合はどうすればよいですか?抽出された略語が検索結果に表示されないようにすることはできますか?**</span><span class="sxs-lookup"><span data-stu-id="2ae18-195">**Q: What if my organization doesn’t want to show mined acronyms? Can I stop showing mined acronyms in search results?**</span></span>

<span data-ttu-id="2ae18-196">**A**: 検索結果での抽出された略語を表示しないようにするには、「[ビジネス製品についてのサポート](https://docs.microsoft.com/office365/admin/contact-support-for-business-products?redirectSourcePath=%252fen-us%252farticle%252fContact-Office-365-for-business-support-32a17ca7-6fa0-4870-8a8d-e25ba4ccfd4b&view=o365-worldwide&tabs=online#BKMK_call_support)」の手順に従ってカスタマーサポートチケットを作成します。</span><span class="sxs-lookup"><span data-stu-id="2ae18-196">**A**: To turn off showing mined acronyms in search results, create a customer support ticket by following the instructions at [Contact support for business products](https://docs.microsoft.com/office365/admin/contact-support-for-business-products?redirectSourcePath=%252fen-us%252farticle%252fContact-Office-365-for-business-support-32a17ca7-6fa0-4870-8a8d-e25ba4ccfd4b&view=o365-worldwide&tabs=online#BKMK_call_support).</span></span>
<span data-ttu-id="2ae18-197">サポートチケットを作成した後は、検索結果に表示されなくなるまでに最大48時間かかります。</span><span class="sxs-lookup"><span data-stu-id="2ae18-197">After you create a support ticket, it takes up to 48 hours for mined acronyms to stop appearing in search results.</span></span> 

<span data-ttu-id="2ae18-198">**Q: [Office 365](https://Office.com)と[SharePoint Online](https://products.office.com/sharepoint/collaboration)で頭字語の回答が表示されるのはいつですか。**</span><span class="sxs-lookup"><span data-stu-id="2ae18-198">**Q: When will I see Acronyms answers in [Office 365](https://Office.com) and [SharePoint Online](https://products.office.com/sharepoint/collaboration)?**</span></span>

<span data-ttu-id="2ae18-199">**A**: Office 365 と SharePoint Online での頭字語の回答は製品ロードマップの一部ですが、現在、日付または時間枠を提供することはできません。</span><span class="sxs-lookup"><span data-stu-id="2ae18-199">**A**: Acronyms answers in Office 365 and SharePoint Online are part of our product roadmap, but we're currently unable to provide a date or timeframe.</span></span>
