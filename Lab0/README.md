Lab 0 ローカルPCへのCLIインストール

- [目的とゴール](#目的とゴール)
- [Labの流れ](#labの流れ)
- [最後に](#最後に)


## 概要とゴール

Code EngineのハンズオンをするためのローカルPCへのCLIインストールです

ゴール

* IBM Cloud CLIが利用できる



## Labの流れ

1. IBM Cloud CLIが利用できる



## IBM Cloud CLIのインストール

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

