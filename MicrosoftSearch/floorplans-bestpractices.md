---
title: Microsoft 検索フロアプランのベストプラクティス
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
description: Microsoft 検索フロアプランのベストプラクティス
ms.openlocfilehash: 47eb46df48f1871f6d34d4b00787cf11ccbac1ea
ms.sourcegitcommit: 6b1c6a4e502d95b42a030a963f9452c387d8a5cd
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/20/2020
ms.locfileid: "43571016"
---
<!-- markdownlint-disable no-inline-html -->
# <a name="best-practices-for-microsoft-search-floor-plans"></a><span data-ttu-id="3555c-103">Microsoft 検索フロアプランのベストプラクティス</span><span class="sxs-lookup"><span data-stu-id="3555c-103">Best practices for Microsoft Search floor plans</span></span>

<span data-ttu-id="3555c-104">Microsoft 検索フロアプランを正常に実装するには、3つのデータを調整する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3555c-104">To successfully implement Microsoft Search floor plans, you need to coordinate three pieces of data:</span></span>

- <span data-ttu-id="3555c-105">**場所データの作成**: 形式と追加方法を教えてください。</span><span class="sxs-lookup"><span data-stu-id="3555c-105">**Building location data**: What format and how to add?</span></span>
- <span data-ttu-id="3555c-106">**DWG 形式のフロアプランマップ**: 最大成功のために、どのようなデータを含める必要があるかを表示します。</span><span class="sxs-lookup"><span data-stu-id="3555c-106">**Floor plan map in DWG format**: How to view and what data should it contain for maximum success?</span></span>
- <span data-ttu-id="3555c-107">**Azure Active Directory 内の従業員のオフィスの場所[(azure AD)](https://azure.microsoft.com/services/active-directory/)**: 使用する形式と追加する方法</span><span class="sxs-lookup"><span data-stu-id="3555c-107">**Employee office location in [Azure Active Directory (Azure AD)](https://azure.microsoft.com/services/active-directory/)**: What format to use and how to add?</span></span> <br>

<span data-ttu-id="3555c-108">Microsoft 検索フロアプランを展開するためのベストプラクティスについても、以下のセクションで説明します。</span><span class="sxs-lookup"><span data-stu-id="3555c-108">The best practices for deploying Microsoft Search floor plans are also described in the following sections.</span></span>

## <a name="building-location-data"></a><span data-ttu-id="3555c-109">場所データの作成</span><span class="sxs-lookup"><span data-stu-id="3555c-109">Building location data</span></span>

<span data-ttu-id="3555c-110">フロアプランを追加する前に、Microsoft の検索場所に建物を追加する必要があります。</span><span class="sxs-lookup"><span data-stu-id="3555c-110">Before you add floor plans, you need to add your buildings to Microsoft Search locations.</span></span> <span data-ttu-id="3555c-111">次の必要な建築データを提供します。</span><span class="sxs-lookup"><span data-stu-id="3555c-111">Provide the following required building data:</span></span>

|<span data-ttu-id="3555c-112">データを作成する必要がある</span><span class="sxs-lookup"><span data-stu-id="3555c-112">Required building data</span></span>  |<span data-ttu-id="3555c-113">例</span><span class="sxs-lookup"><span data-stu-id="3555c-113">Example</span></span>  |
|---------|---------|
|<span data-ttu-id="3555c-114">名前</span><span class="sxs-lookup"><span data-stu-id="3555c-114">Name</span></span>     |    <span data-ttu-id="3555c-115">建物1、ニューヨーク市</span><span class="sxs-lookup"><span data-stu-id="3555c-115">Building 1, New York City</span></span>     |
|<span data-ttu-id="3555c-116">番地</span><span class="sxs-lookup"><span data-stu-id="3555c-116">Street address</span></span>     |     <span data-ttu-id="3555c-117">123任意の方法、ニューヨーク、NY 10118</span><span class="sxs-lookup"><span data-stu-id="3555c-117">123 Any Avenue, New York, NY 10118</span></span>  |
|<span data-ttu-id="3555c-118">緯度-経度 (省略可能)</span><span class="sxs-lookup"><span data-stu-id="3555c-118">Latitude-longitude  (optional)</span></span>   |    <span data-ttu-id="3555c-119">40.760539、-73.975341</span><span class="sxs-lookup"><span data-stu-id="3555c-119">40.760539, -73.975341</span></span>      |
|<span data-ttu-id="3555c-120">キーワード</span><span class="sxs-lookup"><span data-stu-id="3555c-120">Keywords</span></span>     |    <span data-ttu-id="3555c-121">ニューヨークオフィス、建物1、本社、本社</span><span class="sxs-lookup"><span data-stu-id="3555c-121">New York Office, Building 1, main office, headquarters</span></span>     |

<span data-ttu-id="3555c-122">一度に1つの場所を追加するのではなく、[**場所**] タブの [**インポート**] 機能を使用して、多くの建物を一度に追加することができます。</span><span class="sxs-lookup"><span data-stu-id="3555c-122">You can add many buildings at a time by using the **Import** feature in the **Locations** tab instead of adding locations one at a time.</span></span> <span data-ttu-id="3555c-123">**インポート**機能を使用すると、緯度-経度を指定できます。</span><span class="sxs-lookup"><span data-stu-id="3555c-123">With the **Import** feature, you can specify the latitude-longitude.</span></span> <span data-ttu-id="3555c-124">詳細については、「[場所を管理](manage-locations.md)する」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3555c-124">For more information, see [Manage locations](manage-locations.md).</span></span>

## <a name="floor-plan-map-in-dwg-format"></a><span data-ttu-id="3555c-125">DWG 形式のフロアプランマップ</span><span class="sxs-lookup"><span data-stu-id="3555c-125">Floor plan map in DWG format</span></span>

<span data-ttu-id="3555c-126">Microsoft Search でマップを作成するには、フロアプランを DWG 形式で、特定の情報と共にアップロードする必要があります。</span><span class="sxs-lookup"><span data-stu-id="3555c-126">To build maps in Microsoft Search, you need to upload floor plans in DWG format with specific information.</span></span> <span data-ttu-id="3555c-127">DWG 形式のファイルを作成して表示する方法については、「 [Dwg ビューアー](https://www.autodesk.in/products/dwg)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3555c-127">To learn how to create and view DWG-formatted files, see [DWG Viewers](https://www.autodesk.in/products/dwg).</span></span>

<span data-ttu-id="3555c-128">フロアプランマップは4つの要素を表示します。</span><span class="sxs-lookup"><span data-stu-id="3555c-128">Floor plan maps display four elements:</span></span>

1. <span data-ttu-id="3555c-129">**部屋番号**: 次の例では、部屋番号は**B1 1001**および**b1 1002**として定義されています。</span><span class="sxs-lookup"><span data-stu-id="3555c-129">**Room numbers**: In the following example, room numbers are defined as **B1 1001** and **B1 1002**.</span></span> <span data-ttu-id="3555c-130">**B1**は建物コードです。 **1001**には、フロア番号**1**とオフィス番号**001**が含まれています。</span><span class="sxs-lookup"><span data-stu-id="3555c-130">**B1** is the building code, and **1001** contains the floor number **1** and the office number **001**.</span></span>
1. <span data-ttu-id="3555c-131">**部屋のレイアウト**: 複数のユーザーが1つのオフィスを共有しているときに詳細をわかりやすくするために、椅子や机などのレイアウトを定義できます。</span><span class="sxs-lookup"><span data-stu-id="3555c-131">**Room layouts.**: To help clarify details when multiple users share an office, you can define layouts like chairs and desk.</span></span>
1. <span data-ttu-id="3555c-132">**部屋の種類**: 例には、office、corridor、open area、およびトイレットがあります。</span><span class="sxs-lookup"><span data-stu-id="3555c-132">**Room types**: Some examples include office, corridor, open area, and toilet.</span></span>
1. <span data-ttu-id="3555c-133">**資産情報**: ユーザーが空き領域内にいる場合は、どの机に座っているかを示すことができます。</span><span class="sxs-lookup"><span data-stu-id="3555c-133">**Asset info**: If users are in an open space, you can denote which desk they sit at.</span></span> <span data-ttu-id="3555c-134">この例では、机は**TB1**および**TB2**によって示されています。</span><span class="sxs-lookup"><span data-stu-id="3555c-134">In this example, the desks are denoted by **TB1** and **TB2**.</span></span>

![部屋番号、資産、および会議室の種類のラベル付け方法を示す簡単な office マップ](media/Floorplans-LayoutwithCallouts.png)

<span data-ttu-id="3555c-136">この図では、会議室番号は最も重要なアイテムです。</span><span class="sxs-lookup"><span data-stu-id="3555c-136">In this diagram, room numbers are the most important item.</span></span> <span data-ttu-id="3555c-137">次の図に示すように、ユーザーアカウントのユーザーのオフィスの場所にマップされています。</span><span class="sxs-lookup"><span data-stu-id="3555c-137">They're mapped to a person’s office location on their user account as shown in the following image.</span></span>

![ユーザーの詳細情報 (office の場所を含む) を示す people 検索結果カードの [概要] タブ](media/floorplans-peoplecard.png)

<span data-ttu-id="3555c-139">この情報は、 **Physicaldeliveryofficename**プロパティの[Azure AD](https://azure.microsoft.com/services/active-directory/)に格納されています。</span><span class="sxs-lookup"><span data-stu-id="3555c-139">This information is stored in [Azure AD](https://azure.microsoft.com/services/active-directory/) in the **PhysicalDeliveryOfficeName** property.</span></span> <span data-ttu-id="3555c-140">Microsoft 365[管理センター](https://admin.microsoft.com)では、 **Office**プロパティと呼ばれ、**アクティブなユーザー**に追加することができます。</span><span class="sxs-lookup"><span data-stu-id="3555c-140">In the Microsoft 365 [admin center](https://admin.microsoft.com), it’s called the **Office** property and can be added in **Active users**.</span></span>

### <a name="dwg-files"></a><span data-ttu-id="3555c-141">DWG ファイル</span><span class="sxs-lookup"><span data-stu-id="3555c-141">DWG files</span></span>

<span data-ttu-id="3555c-142">Microsoft Search では、DWG プランファイルが必要です。これは、 [AutoCAD](https://www.autodesk.com/autocad)図面形式です。</span><span class="sxs-lookup"><span data-stu-id="3555c-142">Microsoft Search requires floor plan files in DWG, which is an [AutoCAD](https://www.autodesk.com/autocad) drawing format.</span></span> <span data-ttu-id="3555c-143">ファイルには、**レイアウト**と**ラベル**のデータが含まれている必要があります。</span><span class="sxs-lookup"><span data-stu-id="3555c-143">The files must contain **layout** and **label** data.</span></span> <span data-ttu-id="3555c-144">**部屋番号**は、フロアプランにとって最も重要なラベルです。</span><span class="sxs-lookup"><span data-stu-id="3555c-144">**Room numbers** are the most important labels for floor plans.</span></span>

<span data-ttu-id="3555c-145">次の表に示す完全一致の方法で office の番号付けシステムを作成することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="3555c-145">We recommend that you create your office numbering system with the exact-match method shown in the following table.</span></span> <span data-ttu-id="3555c-146">しかし、そのラベル付けだけに制限はありません。</span><span class="sxs-lookup"><span data-stu-id="3555c-146">But you aren't limited to that labeling.</span></span> <span data-ttu-id="3555c-147">たとえば、 [AZURE AD](https://azure.microsoft.com/services/active-directory/)内のユーザーのオフィスの場所が**B1 1001**の場合、DWG ファイルの部屋番号には、次のいずれかのオプションを指定してラベルを付けることができます。</span><span class="sxs-lookup"><span data-stu-id="3555c-147">For example, if the user's office location in [Azure AD](https://azure.microsoft.com/services/active-directory/) is **B1 1001**, you can label the room number in the DWG file with any of the options that follow.</span></span>

|<span data-ttu-id="3555c-148">Match</span><span class="sxs-lookup"><span data-stu-id="3555c-148">Match</span></span>  |<span data-ttu-id="3555c-149">レイアウト</span><span class="sxs-lookup"><span data-stu-id="3555c-149">Layout</span></span>  |
|---------|---------|
|<span data-ttu-id="3555c-150">Office の場所を正確に一致させる (推奨)</span><span class="sxs-lookup"><span data-stu-id="3555c-150">Exact match to office location (Recommended)</span></span> <br> <span data-ttu-id="3555c-151">**B1 1001**</span><span class="sxs-lookup"><span data-stu-id="3555c-151">**B1 1001**</span></span> <br> <span data-ttu-id="3555c-152">コードを作成する: B1</span><span class="sxs-lookup"><span data-stu-id="3555c-152">Building code: B1</span></span><br><span data-ttu-id="3555c-153">床: 1</span><span class="sxs-lookup"><span data-stu-id="3555c-153">Floor: 1</span></span> <br><span data-ttu-id="3555c-154">会議室番号: 001</span><span class="sxs-lookup"><span data-stu-id="3555c-154">Room number: 001</span></span>    |    ![オフィス番号が "B1 1001" の単一オフィスのフロアプラン](media/floorplans-layoutexactmatch.png)     |
|<span data-ttu-id="3555c-156">フロアと部屋番号を照合する</span><span class="sxs-lookup"><span data-stu-id="3555c-156">Match floor and room number</span></span> <br> <span data-ttu-id="3555c-157">**1001**</span><span class="sxs-lookup"><span data-stu-id="3555c-157">**1001**</span></span><br><span data-ttu-id="3555c-158">床: 1</span><span class="sxs-lookup"><span data-stu-id="3555c-158">Floor: 1</span></span> <br><span data-ttu-id="3555c-159">会議室番号: 001</span><span class="sxs-lookup"><span data-stu-id="3555c-159">Room number: 001</span></span>    |   ![オフィス番号が "1001" の単一オフィスのフロアプラン](media/floorplans-layoutfloorroom.png)   |
|<span data-ttu-id="3555c-161">会議室番号のみを照合する</span><span class="sxs-lookup"><span data-stu-id="3555c-161">Match room number only</span></span> <br> <span data-ttu-id="3555c-162">**1**</span><span class="sxs-lookup"><span data-stu-id="3555c-162">**1**</span></span><br><span data-ttu-id="3555c-163">部屋番号: 1</span><span class="sxs-lookup"><span data-stu-id="3555c-163">Room number: 1</span></span>        |    ![オフィス番号が "1" の単一オフィスフロアマップ](media/floorplans-layoutroomonly.png)     |

## <a name="user-account-office-location"></a><span data-ttu-id="3555c-165">ユーザーアカウントのオフィスの場所</span><span class="sxs-lookup"><span data-stu-id="3555c-165">User account office location</span></span>

<span data-ttu-id="3555c-166">従業員の場所をマップするために、DWG ファイルの部屋番号は、 [AZURE AD](https://azure.microsoft.com/services/active-directory/)のユーザーアカウント内のオフィスの場所にマップされます。</span><span class="sxs-lookup"><span data-stu-id="3555c-166">To map an employee’s location, the room numbers in DWG files are mapped to office locations in the user’s account in [Azure AD](https://azure.microsoft.com/services/active-directory/).</span></span> <span data-ttu-id="3555c-167">**Office location**プロパティは、DWG ファイルのオフィスの場所情報と一致している必要があります。</span><span class="sxs-lookup"><span data-stu-id="3555c-167">The **Office location** property needs to match the office location information in the DWG file.</span></span>

<span data-ttu-id="3555c-168">次の表では、場所データのマッピングのベストプラクティスについて説明します。</span><span class="sxs-lookup"><span data-stu-id="3555c-168">The following table explains best practices for mapping location data:</span></span>

|<span data-ttu-id="3555c-169">ベスト プラクティス</span><span class="sxs-lookup"><span data-stu-id="3555c-169">Best practice</span></span>  |<span data-ttu-id="3555c-170">説明</span><span class="sxs-lookup"><span data-stu-id="3555c-170">Explanation</span></span> |
|---------|---------|
|<span data-ttu-id="3555c-171">建物のコード、フロア、および部屋番号を含めます。</span><span class="sxs-lookup"><span data-stu-id="3555c-171">Include building code, floor, and room number.</span></span>     |   <span data-ttu-id="3555c-172">このデータを使用すると、正確な一致を得ることができます。</span><span class="sxs-lookup"><span data-stu-id="3555c-172">This data gives you the best chance to make exact matches.</span></span>     |
|<span data-ttu-id="3555c-173">コードとフロアを構築した後に、区切り記号を含めます。</span><span class="sxs-lookup"><span data-stu-id="3555c-173">Include a separator after building codes and floors.</span></span>     |  <span data-ttu-id="3555c-174">次の例に示されているように、フロア番号と部屋番号を別々に作成するコードを区切ります。</span><span class="sxs-lookup"><span data-stu-id="3555c-174">Separate building codes from floor and room numbers with a separator or a space, as in these examples:</span></span><br> <span data-ttu-id="3555c-175">B1 1001</span><span class="sxs-lookup"><span data-stu-id="3555c-175">B1 1001</span></span><br> <span data-ttu-id="3555c-176">B1/1001</span><span class="sxs-lookup"><span data-stu-id="3555c-176">B1/1001</span></span> <br> <span data-ttu-id="3555c-177">B1-1001</span><span class="sxs-lookup"><span data-stu-id="3555c-177">B1-1001.</span></span>   |
|<span data-ttu-id="3555c-178">部屋番号は、コード、翼、床面の情報の作成に常に従います。</span><span class="sxs-lookup"><span data-stu-id="3555c-178">Room number always follows building code, wing, and floor information.</span></span>     |  <span data-ttu-id="3555c-179">部屋番号が**1001**の場合は、オフィスの場所を**b1 1001**、 **b1/1001**、または**b1-1001**に設定します。</span><span class="sxs-lookup"><span data-stu-id="3555c-179">If the room number is **1001**, then set the office location to **B1 1001**, **B1/1001**, or **B1-1001**.</span></span> <br> <span data-ttu-id="3555c-180">会議室番号が**f1-001**の場合は、office の場所を**b1 F1-001**または**b1/f1-001**に設定します。</span><span class="sxs-lookup"><span data-stu-id="3555c-180">If the room number is **F1-001**, then set the office location to **B1 F1-001** or **B1/F1-001**.</span></span> <br> <span data-ttu-id="3555c-181">会議室番号が**1**の場合、 [Azure AD](https://azure.microsoft.com/services/active-directory/)の場所を**b1 1001**、 **b1/1001**、または**b1-F1-001**に設定します。</span><span class="sxs-lookup"><span data-stu-id="3555c-181">If the room number is **1**, then set the [Azure AD](https://azure.microsoft.com/services/active-directory/) location to **B1 1001**, **B1/1001**, or **B1-F1-001**.</span></span>       |
|

## <a name="next-steps"></a><span data-ttu-id="3555c-182">次の手順</span><span class="sxs-lookup"><span data-stu-id="3555c-182">Next steps</span></span>

[<span data-ttu-id="3555c-183">場所の管理</span><span class="sxs-lookup"><span data-stu-id="3555c-183">Manage locations</span></span>](manage-locations.md)<br>
[<span data-ttu-id="3555c-184">フロアプランを管理する</span><span class="sxs-lookup"><span data-stu-id="3555c-184">Manage floor plans</span></span>](manage-floorplans.md)
