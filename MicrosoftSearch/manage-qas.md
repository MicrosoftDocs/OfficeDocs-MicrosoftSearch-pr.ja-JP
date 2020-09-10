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
description: 回答を個別に検索して更新したり、使用可能な Microsoft 検索ツールを使用して、Q&を一度にすべて編集したりできます。
ms.openlocfilehash: 2a8b0727ef3540a35d617cf6c8bae7b0d99767a8
ms.sourcegitcommit: 988c37610e71f9784b486660400aecaa7bed40b0
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/09/2020
ms.locfileid: "47423002"
---
# <a name="manage-qas"></a>Q&A の管理

Q&A の作成は、ブックマークの作成と似ています。 Q&、web ページへのリンクを提供するだけでなく、ユーザーの質問に答えることができます。 また、リッチテキスト形式で回答の書式を設定することもできます。 ブックマークと Q&A が同じキーワードを共有している場合は、ブックマークの結果が最初に表示されます。 ブックマークと同様に、q&のインデックスは、Q&A が追加または変更された直後に更新されます。

## <a name="add-or-edit-a-single-qa"></a>1 つの Q&A を追加または編集する

1. [Microsoft 365 管理センター](https://admin.microsoft.com)で、 [**Q&A**](https://admin.microsoft.com/Adminportal/Home#/MicrosoftSearch/qnas)に移動します。
1. Q&A を追加するには、[ **追加**] を選択します。
Q&A を編集するには、関連する Q&A の一覧で Q&A を選択します。 情報を追加または編集すると、プレビューが自動的に更新されます。
1. 変更内容を保存します。

### <a name="supported-html-tags"></a>サポートされている HTML タグ

回答 (説明) に既存の HTML コンテンツを使用したり、HTML タグを追加したりできます。 サポート対象外のタグは無視されます。

次の HTML タグがサポートされています。

- blockquote
- div
- em
- h1、h2、h3、h4
- ol、ul、li
- p
- pre
- span
- strong
- table、thead、tbody、tr、th、td
- u
- a
- code
- br
- hr
- img

## <a name="add-or-edit-qas-using-browser-extensions"></a>ブラウザー拡張機能を使用して Q&を追加または編集する

検索管理者は、ブラウザーの拡張機能を使用して検索コンテンツを簡単に作成できます。 ブラウザー拡張機能をインストールし、Q&A を生成するサイトに移動します。 その後、Q&A を作成し、ソースサイトへのリンクを含めることができます。

現在、Microsoft Edge および Chrome ではブラウザー拡張機能を使用できます。

- エッジ (レガシ) の拡張機能をダウンロードするには、 [Microsoft Store](https://www.microsoft.com/p/microsoft-search-content-creator/9nrqdbcbwq55?activetab=pivot:overviewtab)にアクセスしてください。
- 拡張子クロムまたはエッジ (Chromium) をダウンロードするには、 [chrome web store](https://chrome.google.com/webstore/detail/microsoft-search-content/nocnablpaoeecfmfnjoheefkogmleipm)に移動します。

## <a name="bulk-add-or-edit-qas"></a>Q&A を一括して追加または編集する

管理者は、インポートおよびエクスポート機能を使用して、Q&の一括作成または編集を行うことができます。

インポート/エクスポート機能を使用して、次のことを行います。

- [一括追加] q&テンプレートファイルに&追加の詳細を追加して、インポートします。
- 一括編集 Q&エクスポート Q&.csv ファイルとして q&を編集し、エクスポートしたファイルの詳細を編集して、ファイルをインポートします。
- Q&をエクスポートし、.csv ファイルとして&としてバックアップします。

Q&をインポートまたはエクスポートするには、次のようにします。

1. [Q&A] タブの右上隅にある **[インポート]** を選択します。
[ **エクスポート** ] を選択して、.Csv ファイルとしてすべての既存の Q&をダウンロードします。
1. 右側のウィンドウで、.csv ファイルを使用してインポートするオプションを選択します。 テンプレートファイルをダウンロードして、必要なフィールドと詳細のリストを取得します。
1. テンプレートファイルに Q&追加または編集して、コンピューターに保存します。
1. [ **Q&をインポート** する] ウィンドウで、[ **参照**] を選択し、インポートする .csv ファイルを選択します。
1. **[インポート]** を選択します。

重要なテンプレートファイルのヒント:

- 次のフィールドのデータは決して編集しないでください: **ID**、**最終更新日時**、**最終更新者**
- 既存のブックマークの **ID** を含めると、インポート ファイルの情報に置き換えられます。
- 同じタイトルまたは URL を持つ既存のブックマークがある場合、ブックマークはインポートファイルの情報で更新されます。
- テンプレートファイルのすべてのフィールドが必須であるわけではなく、ブックマークの状態によって必須のフィールドが異なる場合があります。
- [ **状態** ] フィールドに基づいて、ブックマークは *下書き*、 *提案*済み、または *スケジュール*済みとして保存されるか、自動的に公開されます。
- 複数の組織を管理するパートナーの場合: ブックマークを1つの組織からエクスポートして、別の組織にインポートすることができます。 ただし、インポートする前に **ID** 列のデータを削除する必要があります。

> [!NOTE]
> テンプレートファイルにエラーがある場合は、Q&をインポートすることはできません。 エラーが発生しないようにするには、インポートファイルが適切に書式設定されていることを確認し、必要な情報をすべて含めるようにします。

エラーを回避する方法の詳細については、「 [インポートエラーの防止](manage-bookmarks.md#prevent-import-errors)」を参照してください。
