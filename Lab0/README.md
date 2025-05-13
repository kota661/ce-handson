Lab1 環境セットアップ

- [目的とゴール](#目的とゴール)
- [Labの流れ](#labの流れ)
- [Step 1 - (Option) IBM Cloud CLIが利用できる](#step-1---option-ibm-cloud-cliが利用できる)
- [最後に](#最後に)


## 概要とゴール

Code Engineのハンズオンをするための環境のセットアップです

ゴール

* ハンズオンオーナー: (Option) メンバーのIBM Cloudへの招待＋権限設定を行い、ハンズオン参加者が環境を利用できるようにする
* ハンズオン参加者：(Option) IBM Cloud CLIが利用できる



## Labの流れ

1. ハンズオンオーナー: (Option) メンバーのIBM Cloudへの招待＋権限設定
1. ハンズオン参加者：(Option) IBM Cloud CLIが利用できる



## ハンズオンオーナー: (Option) メンバーのIBM Cloudへの招待＋権限設定

パターン１（すでに各サービスにアクセス可能なアクセスグループがある場合）

* ハンズオン参加メンバーをアクセスグループに招待してください

パターン２（新たにアクセスグループをご用意される場合）

* ハンズオン参加メンバーに対して、以下サービスへのアクセス権限を付与してください
  * Code Engine
  * Container Registry
  * リソース・グループ



## ハンズオン参加者：(Option) IBM Cloud CLIのインストール

1. CLIのインストール
   * Mac の場合、以下のコマンドを端末にコピー・アンド・ペーストして実行します。
    ```
    curl -fsSL https://clis.cloud.ibm.com/install/osx | sh
    ```
   * Windows™ の場合は、以下のコマンドを Windows™ PowerShell 5 端末コンソールにコピー＆ペーストして実行します：
    ```
    iex (New-Object Net.WebClient).DownloadString('https://clis.cloud.ibm.com/install/powershell')
    ```
2. 動作確認
    ```
    ibmcloud version
    ```
3. Code Engine のPluginをインストール
   ```
   ibmcloud plugin install code-engine
   
   ```



参考情報[スタンドアロン IBM Cloud CLI のインストール](https://cloud.ibm.com/docs/cli?topic=cli-install-ibmcloud-cli&locale=ja)




## 最後に
お疲れ様でした！、次の[Lab 1](../Lab1)に進んでください

