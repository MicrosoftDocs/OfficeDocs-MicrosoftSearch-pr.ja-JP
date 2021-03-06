---
title: コネクタの結果クラスター
ms.author: manusi
author: manusi
manager: ruppala
ms.audience: Admin
ms.topic: article
ms.service: mssearch
localization_priority: Normal
search.appverid:
- BFB160
- MET150
- MOE150
description: コネクタの結果クラスター エクスペリエンスの詳細
ms.openlocfilehash: ae5528f2e12c9e331b66e821f2a9c03947d788df
ms.sourcegitcommit: 5df252e6d0bd67bb1b4c59418aceca8369f5fe42
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/23/2021
ms.locfileid: "51031775"
---
# <a name="graph-connectors-result-cluster"></a>グラフ コネクタの結果クラスター

## <a name="overview-of-the-graph-connectors-result-cluster-preview"></a>Graph コネクタの結果クラスターの概要 (プレビュー)  

Graph コネクタの結果クラスターを使用すると、企業は既定のビューでサード パーティのデータ ソースからコンテンツを検索できます。[すべて] タブ (SharePoint、Office.com、および Bing の Microsoft Search)。

結果クラスターは、ユーザーがすべてのサード パーティコンテンツを 1 か所で検出するのに役立ちます。 結果クラスターに表示される結果は、検索の垂直方向の構成に基づいてグループ化されます。

## <a name="how-connector-results-are-selected-and-displayed"></a>コネクタの結果を選択して表示する方法

結果クラスターで提供されるコネクタの結果は、コネクタ コンテンツを含む個々の検索バーティカルから派生します。 各検索バーティカルは、候補の結果クラスターとなる関連する結果のセットを提供します。 関連する結果は、各アイテムの "title" プロパティと "content" プロパティに基づいて選択されます。 content プロパティは、スキーマで *isContent=true* としてマークされます。

検索バーティカルからのコンテンツの検出を確実に行う場合は、アイテムに意味のあるタイトルを提供することをお勧めします。 これは、結果クラスター候補の調停と、結果クラスターにコンテンツが表示される可能性にプラスの影響を与える。 たとえば、ユーザーがコンテンツを検索するために ID を使用しない限り、プロパティ "title" の値として ID を使用しないようにします。

結果クラスターが表示される頻度は、構成する検索バーティカルの数やコンテンツの種類などの要因によって異なります。 結果クラスターを操作または無視することで、ユーザーは時間の間にトリガーを調整するヒントを暗黙的に提供します。

結果クラスターに表示されるコネクタ アイテムの検索結果エクスペリエンスでは、ユーザーが定義 [した結果の種類](./customize-search-page.md#create-your-own-result-type) を使用します。 結果の種類が構成されていない場合は、 [システムによって生成されたレイアウトが](./customize-search-page.md#default-search-result-layout) 使用されます。 

検索結果のタイトルとして "title" プロパティ、検索の説明として "content" プロパティを使用することをお勧めします。 これにより、結果クラスターの正確なトリガーとクラスター内の最も関連性の高い結果を通じて、ユーザーにとって最適なエクスペリエンスが提供されます。 

## <a name="enable-result-clusters"></a>結果クラスターを有効にする
  
結果のクラスター エクスペリエンスは既定で無効になっています。  

組織レベルでエクスペリエンスを有効にする手順は次のとおりです。

1. Microsoft [365 管理センターで、[](https://admin.microsoft.com)バーティカル] [**に移動します**](https://admin.microsoft.com/Adminportal/Home#/MicrosoftSearch/verticals)。
2. [すべての垂直 **] を** 選択し、[コネクタの **結果を表示する] を有効にします**。 


SharePoint サイト レベルでエクスペリエンスを有効にする手順は次のとおりです。

1. 結果クラスター エクスペリエンスが必要な SharePoint サイトで、[設定] に **移動します**。
2. [サイト情報 **] [** > **すべてのサイト設定を表示する] に移動します**。
3. [Microsoft Search] セクションに移動し、[このサイト コレクション **の Microsoft Search の構成] を選択します**。
4. ナビゲーション ウィンドウで、[カスタム エクスペリエンス] に **移動し**、[垂直] **を選択します**。
5. [すべての垂直 **] を** 選択し、[コネクタの **結果を表示する] を有効にします**。

## <a name="view-the-result-cluster-experience-after-it-is-enabled"></a>有効にした後で、結果クラスター エクスペリエンスを表示する

結果クラスター エクスペリエンスを有効にした後、表示には最大で 12 時間かかる場合があります。 エクスペリエンスがすぐに必要な場合は、sharePoint の URL に *cacheClear=true* を追加し、Office。