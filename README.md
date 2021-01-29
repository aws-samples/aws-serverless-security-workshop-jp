# サーバーレスセキュリティワークショップ

このワークショップでは、サーバーレスアプリケーションを保護するためのテクニックを学びます。AWS Lambda、Amazon API Gateway、およびRDS Auroraで構築されたサーバーレスアプリケーションのセキュリティを向上させるために、以下の５つのドメインで利用できる AWS のサービスと機能を説明します。 

1. アイデンティティとアクセス管理 
1. インフラストラクチャ
1. データ
1. ソースコード
1. ロギングとモニタリング

このワークショップは、サーバーレスアプリケーションの構築から始まります。このアプリケーションは、サードパーティ企業がWild Rydes の人気を活用して自社ブランドを販売できるものです。サードパーティ企業がユニコーンのカスタマイズを送信できる機能と、Wild Rydesが広告収入を受け取る機能を備えてます。

サーバレスアプリケーションは、下記のような構成になっています。

![architecture-diagram](docs/00-initial-setup/images/00-base-architecture.png)

ただし、この単純なサーバーレスアプリケーションはあまり安全ではないため、このサーバーレスAPIを攻撃者から保護するための対策を実装する必要があります。 

ワークショップのモジュールを行うことで、さまざまなセキュリティの側面を改善し、このサーバーレスアプリケーションのセキュリティを向上させることができます。 

## プレゼンテーションスライド

プレゼンテーションスライドは、このGitリポジトリの`slides`ブランチの`presentation/`フォルダーにあります。 

## ワークショップ モジュール

**注**：このワークショップは、すべてのモジュールを順番に行う必要がないように設計されています。ただし、**モジュール0は、他のモジュールの作業前に行う必要があります**。 

以下のモジュール0のリンクをクリックして、ワークショップで使用するサーバーレスアプリケーションのセットアップを開始してください！ 

<a href="docs/00-initial-setup/"><img src="docs/images/module0.png" alt="module 1" height="90" width="140" width="150" width="185"></a>

このワークショップのモジュールの概要と、それらがセキュリティのどの領域にマッピングされるかを以下に示します。 

<table style="text-align:center width:100%" align="center" >
  <tr>
    <th rowspan="3" width="20%"> 
    	アイデンティティとアクセス管理  ⚔ <br> 
    	<a href="docs/01-add-authentication/"><img src="docs/images/moduel1.png" alt="module 1" height="90" width="140" width="150" width="185"></a>
	 </th>
    <th width="60%">
    	<span style="font-weight:bold">ソースコード 🏰</span> <br> 
    	<a href="docs/02-add-secrets-manager/"><img src="docs/images/module2.png" alt="module 2" height="90" width="140" width="150" width="185"></a>
    	<a href="docs/03-input-validation/"><img src="docs/images/module3.png" alt="module 3" height="90" width="140" width="150" width="185"></a>
    	<a href="docs/07-dependency-vulnerability/"><img src="docs/images/module7.png" alt="module 3" height="90" width="140" width="150" width="185" ></a>
    </th>
    <th width="20%" colspan="3" rowspan="3">ロギングとモニタリング 🕶
    	<a href="docs/08-xray/"><img src="docs/images/module8.png" alt="module 3" height="90" width="140" width="150" width="185"></a>
</th>
  </tr>
  <tr >
    <td align="center" width="60%">
    	<span style="font-weight:bold">データ 🏆</span><br> 	    
    	<a href="docs/04-ssl-in-transit/"><img src="docs/images/module4.png" alt="module 4" height="90" width="140" width="150" width="185"></a>
    </td>
  </tr>
  <tr>
    <td align="center" width="60%"><span style="font-weight:bold">インフラストラクチャ 🛡</span><br> 
 		<a href="docs/05-usage-plan/"><img src="docs/images/module5.png" alt="module 5" height="90" width="140" width="150" width="185"></a>
  		<a href="docs/06-waf/"><img src="docs/images/module6.png" alt="module 6" height="90" width="140" width="150" width="185"></a>
	</td>
    </tr>
</table>

## リソースのクリーンアップ

 以下をクリックして、リソースのクリーンアップ手順に進みます。 

<a href="docs/10-resource-cleanup/"><img src="docs/images/cleanup.png" alt="module 2" height="90" width="140" width="150" width="185"></a>



## ライセンスについて

The documentation is made available under the Creative Commons Attribution-ShareAlike 4.0 International License. See the LICENSE file.

The sample 
within this documentation is made available under a modified MIT license. See the LICENSE-SAMPLECODE file.