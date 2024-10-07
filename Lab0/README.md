Lab1 環境セットアップ

- [目的とゴール](#目的とゴール)
- [Labの流れ](#labの流れ)
- [Step 1 - (Option) IBM Cloud CLIが利用できる](#step-1---option-ibm-cloud-cliが利用できる)
- [最後に](#最後に)


## 概要とゴール

Code Engineのハンズオンをするための環境のセットアップです

ゴール

* (Option) IBM Cloud CLIが利用できる

## Labの流れ
1. (Option) IBM Cloud CLIが利用できる


## Step 1 - (Option) IBM Cloud CLIが利用できる

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

