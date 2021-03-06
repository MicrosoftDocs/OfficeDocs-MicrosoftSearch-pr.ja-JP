---
title: Microsoft Search で頭字語の回答を管理する
ms.author: rakkum
author: rakeshMSFT
manager: jeffkizn
ms.audience: Admin
ms.topic: article
ms.service: mssearch
localization_priority: Normal
search.appverid:
- BFB160
- MET150
- MOE150
description: Microsoft Search で頭字語の回答を作成および更新する
ms.openlocfilehash: 013510da28599f41c9dc4bf74da99efa2f6c3e97
ms.sourcegitcommit: 62cb7b8c6a311760cc728f2c70a9a22ca76e977e
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/29/2021
ms.locfileid: "51408716"
---
# <a name="manage-acronyms-answers-in-microsoft-search"></a>Microsoft Search で頭字語の回答を管理する

ユーザーは、組織やチームで使用されている頭字語や略語に慣れていないことがよくあります。 組織またはチームに固有の用語は、チーム間を移動したり、社内パートナーと共同で作業する人、または組織の新人には新しい場合があります。  

組織の標準的な用語には、常に単一の参照があるとは限りません。 1 つの参照がない場合、これらの頭字語の定義を見つけるのは難しです。 Microsoft Search は、頭字語の問題を解決します。

## <a name="what-users-experience"></a>ユーザーのエクスぺリエンス

Microsoft Search のユーザーは [Bing](https://Bing.com)、 [SharePoint](https://products.office.com/sharepoint/collaboration)および[Office 365](https://Office.com)の頭字語を使用して、定義を入手できます。 **[検索]** ボックスで、次の例のようにクエリを入力します:

- *What is* DNN
- *Define* DNN
- DNN *definition*
- *Expand* DNN
- DNN *expansion*
- *Meaning of* DNN
- DNN *means*
- DNN *の略*

結果には、ユーザーの組織内に存在する DNN のすべての意味が含まれます。

> [!NOTE]
> ユーザーは、対応する回答をトリガーするために、頭字語で指定された *キーワード* を含むクエリを入力する必要があります。 頭字語のクエリでは、大文字と小文字は区別されません。

## <a name="set-up-acronyms-answers"></a>頭字語の回答を設定する

[Microsoft 365 管理センター](https://admin.microsoft.com)で、[**[頭字語]**](https://admin.microsoft.com/Adminportal/Home#/MicrosoftSearch/acronyms)に移動し、**[頭字語の追加]** を選択します。

Microsoft Search は、2 つのデータ ソースをクエリして、頭字語の回答をユーザーの検索に提供します:

1. **管理者が管理します**。 [管理センター](https://admin.microsoft.com/Adminportal/Home#/MicrosoftSearch/acronyms) の IT 管理者によって提供されます。
2. **System-curated**. ユーザーの電子メールとドキュメント、および組織内で一般に利用可能なデータから Microsoft Search によって検出されます。

### <a name="set-up-admin-curated-acronyms"></a>管理者が指定した頭字語を設定する

検索管理者は、Microsoft Search 管理センターの [[頭](https://admin.microsoft.com/Adminportal/Home#/MicrosoftSearch/acronyms) 字語] タブに頭字語  [を追加できます](https://admin.microsoft.com/Adminportal/Home#/MicrosoftSearch)。 すべての内部サイトまたはリポジトリから管理センターに頭字語を追加することができます。 これらの頭字語は、発行済みまたは下書 **き状態に****追加** できます。

**公開状態**。 頭字語は、Microsoft Search を通じて組織のユーザーが使用できます。

> [!NOTE]
> 公開状態に追加された頭字語が Microsoft Search で利用可能になるまで、最大 3 日かかる場合があります。

**下書き状態**。 Microsoft Search で使用できる前に頭字語を確認する場合は、下書き状態で頭字語を追加できます。 下書き状態の頭字語は検索結果に表示されません。 検索結果に表示するには、頭字語を発行済み状態に移動する必要があります。

**除外された状態**。 Microsoft Search に頭字語が表示されるのを防ぐ場合は、[頭字語を除外する] を使用して追加します。 頭字語が除外されるのを止めるには、除外された頭字語を削除して追加するか、発行済みリストに含める必要があります。

頭字語を個別に追加するか、CSV ファイルに一括インポートできます。 次の表に示すフィールドを使用して CSV ファイルをアップロードします:

| 頭字語 (必須) | 略 (必須) | Url | 説明  | 状態 (必須) | 最終更新日時 | 最終変更者 | Id |
| --------- | --------- | --------- | ---------- | --------- |--------- |--------- |--------- |
| *XXX* | *略語のスペル* | *Source* |  | *公開、下書き、または除外* |  |  |  |

### <a name="csv-fields"></a>CSV フィールド

**頭字語**。 実際の短い形式または頭字語を含みます。 たとえば、*DNN* などです。

**を表します**。 頭字語の定義が含まれる。 たとえば、*Deep Neural Network* などです。

**説明**。 頭字語とその定義に関する詳細情報をユーザーに提供する頭字語の簡単な説明。 たとえば、*deep neural network とは、特定の複雑さを持つニューラル ネットワーク、2 つ以上の層を持つニューラル ネットワークです*。

**ソース**。 頭字語についての詳細情報をユーザーに表示するページまたは Web サイトの URL。

**状態**。 このフィールドには 2 つの値を指定できます:

- **下書き**。 下書き状態に頭字語を追加します。
- **公開**。 公開状態に頭字語を追加して、Microsoft Search で使用できるようにします。
- **除外します**。 頭字語を除外状態に追加し、Microsoft Search に表示されません。

### <a name="system-curated-acronyms"></a>System-curated 頭字語

管理者にとって、組織内で使用されているすべての頭字語を回答に追加するのは難しいかもしれません。 この機能により、検索管理者が認識していない頭字語を見つけることができます。 この作業を行うには、Microsoft Search は次のソースから頭字語を検出してキュレートします。

- ユーザーのメール
- [SharePoint 、Microsoft](https://products.office.com/sharepoint/collaboration) [OneDrive、Microsoft]( https://onedrive.live.com/about/) [OneNote のドキュメント](https://www.onenote.com/)
- SharePoint、OneDrive、または OneNote でユーザーがアクセスできる組織内のパブリック ドキュメント

Microsoft Search では、ドキュメントへのアクセス権とアクセス許可を持つユーザーだけが、ドキュメントから検出された頭字語を確認できます。 ユーザーのメールボックスで頭字語が見つかった場合、その頭字語を表示できるのはそのユーザーのみです。

> [!NOTE]
> システムが指定した頭字語のセットアップは不要です。

## <a name="frequently-asked-questions"></a>よく寄せられる質問

**Q: 管理者が管理するデータとシステムで管理されたデータのランク付け方法**

**A:** 結果のランク付けは、結果が各ユーザーに合わせたものとして、個人ごとに異なる場合があります。 これらのどちらのカテゴリも、常に他のカテゴリよりも優先されます。

**Q: 管理者が指定した頭字語が Microsoft Search で公開された後に表示されるのにどれくらいの時間が必要ですか?**

**A:**  発行済み状態に追加された頭字語が Microsoft Search で使用可能になるには、最大 1 日かかる。

**Q: ユーザーが頭字語の回答をトリガーする方法**

**A**: 頭字語の回答を取得するには [、Bing、SharePoint、](https://bing.com)または [](https://products.office.com/sharepoint/collaboration)[[365](https://Office.com) Search] ボックスに特定のクエリ Office **入力する必要** があります。

**Q: 新しい電子メールまたはドキュメントを受信または送信した後に、システムで指定された頭字語が表示されるのにどのくらいの時間が必要ですか?**

**A:** 新しい電子メールまたはドキュメントで見つかった頭字語は、Microsoft 検索結果に表示されるまで最大 7 日かかっています。

**Q: 頭字語が除外され、公開されている場合は、何が起こりますか?**

**A:** 除外された頭字語が優先され、発行された頭字語が検索結果に表示されません。 公開された頭字語は削除も削除もされません。

**Q: 頭字語が Microsoft 検索結果から除外されるのにどのくらいの時間が必要ですか?**

**A**: 除外された頭字語が検索結果に表示されるのを停止するには、最大で 1 日かかる。

**Q: システムで指定された頭字語の場合、ドキュメントは特定の形式である必要がありますか?**

**A:** いいえ。 画像、フォルダー、zip ファイルを除くすべての種類のファイルをサポートしています。

**Q: Microsoft は、すべての言語のドキュメントから頭字語を検出しますか?**

**A**: Microsoft では、英語、スペイン語、フランス語、イタリア語、ドイツ語、ポルトガル語のドキュメントからのシステムキュアの頭字語のみをサポートしています。 その他の言語のサポートは段階的に追加されます。

**Q: 組織がシステムで指定された頭字語を表示しない場合は、どうしますか。検索結果にこの種類の頭字語が表示されるのを停止できますか?**

**A**: 検索結果にシステムで指定された頭字語を表示するをオフにする場合は、「ビジネス製品のサポートに問い合わせ」の指示に従って、カスタマー サポート [チケットを作成します](/microsoft-365/admin/contact-support-for-business-products)。
サポート チケットを作成した後、システムでキュアされた頭字語が検索結果に表示されるのを停止するには、最大 48 時間かかります。
