# WBS
---

## 目次
- [概要](#概要)
- [WBS](#WBS)
- [改版履歴](#改版履歴)

## 概要
プロジェクトで必要となる各開発種別ドキュメントの作成をブレイクダウンして、ドキュメントに落とし込む。<br>
GitHubの起票issue等の定義、起票されたissueの対応ブランチを定義する。

## WBS

**WBS表のNoは、対応の優先順として記述。**

|No|種別|工程|TASK名|作業内容|起票issue|対応ブランチ|
|:---|:---|:---|:---|:---|:---|:---|
|1|root|要件定義|要件定義書作成|要件定義書を作成する。|ROOT：要件定義 #1|ROOT: Requirements Definition #1|
|2|infra|要件定義|要件定義書作成|要件定義書を作成する。|INFRA：要件定義 #2|INFRA: Requirements Definition #1|
|3|infra|WBS|WBS作成|WBSを作成する。|INFRA：要件定義 #2|INFRA: Requirements Definition #1|
|4|api|要件定義|要件定義書作成|要件定義書を作成する。|API：要件定義 #3|API: Requirements Definition #1|
|5|api|WBS|WBS作成|WBSを作成する。|API：要件定義 #3|API: Requirements Definition #1|
|6|client|要件定義|要件定義書作成|要件定義書を作成する。|CLIENT：要件定義 #4|CLIENT: Requirements Definition #1|
|7|client|WBS|WBS作成|WBSを作成する。|CLIENT：要件定義 #4|CLIENT: Requirements Definition #1|

## 改版履歴

|Ver|修正者|日付|
|:---|:---|:---|
|1|2024/08/06|yukishi24|