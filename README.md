# neo4j-trial

## memo
※ 以下、情報まとめ。正確ではないので参考程度で

### 使用タイプ
Community、Enterpirse、Aura(DBaaS)の３タイプ

#### 参考ページ
* [Neo4j Licensing](https://neo4j.com/licensing/)

#### Community
* フリー。
* 組織内利用、個人利用なら`closed source`でもＯＫっぽい？
* create databaseとかできない。dockerでアプリごとにコンテナ建てるとかで対応。
* 表示時に区分けできるような"テーブルっぽい"ものはあり
* ユーザ追加や権限設定もなさげ？
* 管理者以外はアプリ経由で利用みたいな感じ？

#### Enterpirse
##### Commercial License
* たぶん、有料。
* 公式に価格表記はなさげ
* 使う場合は、コンタクト

##### Developer License
* フリー。
* Neo4j Desktopが前提？
* Neo4j Desktopがコントロール？
* ローカルや開発中のアプリで使える模様

#### Aura
* GCP上？
* 最安構成で６～７千円
* https://neo4j.com/aura/

### official drivers
[About the official drivers ](https://neo4j.com/aura/?ref=subscription)

公式ドライバは以下の４つ
* .NET(C#)
* Java
* JavaScript
* Python

## links
- https://hub.docker.com/_/neo4j
- https://neo4j.com/docs/getting-started/4.0/
- https://neo4j.com/docs/driver-manual/4.0/get-started/#driver-get-started-about
