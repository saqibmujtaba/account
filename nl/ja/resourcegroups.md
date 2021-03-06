---



copyright:

  years: 2017, 2018
lastupdated: "2018-02-08"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:new_window: target="_blank"}

# リソース・グループの管理
{: #rgs}

リソース・グループは、カスタマイズ可能なグループにアカウント・リソースを編成するための方法で、これにより、複数リソースへのアクセス権限をユーザーに一度に素早く割り当てることができます。 {{site.data.keyword.Bluemix}} Identity and Access Management (IAM) のアクセス制御を使用して管理されるすべてのアカウント・リソースは、アカウント内のリソース・グループに属します。 Cloud Foundry サービスは組織とスペースに割り当てられたままで、リソース・グループには追加できません。

リソース・グループの管理を開始するには、{{site.data.keyword.Bluemix}} コンソールで**「管理」**&gt;**「アカウント」**&gt;**「リソース・グループ」**と進みます。 そこから、リソース・グループの表示、名前変更、および新規作成を行えます。

## リソース・グループ内のリソースの表示

1 つのリソース・グループ内に含まれるリソースを簡単に表示するには、ダッシュボードからリソース・グループでフィルタリングします。

## リソース・グループの作成

従量課金 (PAYG) またはサブスクリプションのアカウントの場合、複数のリソース・グループを作成して、 割り当て量の管理とリソース・セットの課金使用量の表示を簡単に行うことができます。 また、リソースをグループにまとめて、複数インスタンスへのアクセス権限を一度に簡単にユーザーに割り当てられるようにすることも可能です。

ライト・アカウントまたは 30 日間のトライアルを使用している場合、追加のリソース・グループは作成できませんが、デフォルト・リソース・グループを名前変更できます。 

各リソース・グループは無料ですが、リソース・グループと Cloud Foundry 組織またはスペース間の接続は、アカウント割り当て量に数えられます。 詳しくは、『[別名とは?](/docs/cfapps/connecting_apps.html#what_is_alias)』を参照してください。
{: tip}

1. **「管理」**&gt;**「アカウント」**&gt;**「リソース・グループ」**に移動します。
2. **「リソース・グループの作成」**をクリックします。
3. リソース・グループの名前を入力します。
4. **「追加」**をクリックします。

## リソース・グループの名前変更

最初のリソース・グループは、`Default` という名前で自動で作成されています。 このグループ、または自分で作成した他のグループの名前は更新することができます。

1. **「管理」**&gt;**「アカウント」**&gt;**「リソース・グループ」**に移動します。
2. **「名前変更」**をクリックします。
3. 固有の名前を入力して**「保存」**をクリックします。

## {{site.data.keyword.Bluemix_notm}} CLI を使用したリソース・グループとリソースの管理

{{site.data.keyword.Bluemix_notm}} CLI には、リソース管理をサポートするいくつかのコマンドがあります。 詳しくは、『[リソース・グループとリソースを管理するためのコマンド](/docs/cli/reference/bluemix_cli/bx_cli.html#commands-for-managing-resource-groups-and-resources)』を参照してください。

## リソース・グループへのアクセス権限の管理

Cloud IAM では、アカウント内のリソースへのきめ細かいユーザー・アクセス権限を柔軟に付与できます。 リソース・グループ内のすべてのリソース、リソース・グループ内の単一サービス・タイプ、またはアカウント内の個別のサービス・インスタンスへのユーザー・アクセス権限を付与するポリシーを、Cloud IAM でユーザーに割り当てられます。 リソース・グループ内のリソースへのアクセス権限をユーザーに付与しても、リソース・グループ自体を管理する権限は付与されません。 実際のリソース・グループの表示、編集、管理について、アクセス権限を別個に設定できます。

リソース・グループへのアクセス権限の管理について詳しくは、『[IAM アクセス権限の管理](/docs/iam/mngiam.html#iammanidaccser)』を参照してください。
