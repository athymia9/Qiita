# Qiita
QiitaCLIで管理するリポジトリー

## Requirements

- VOLTA v1.1.1
- Node.js v20.11.0

## 導入手順

### 1. install volta

1. windowsの場合は[VOLTA公式](https://docs.volta.sh/guide/getting-started)からinstallerをダウンロードしてインストールする

1. Windowsの開発者モードを有効にする

1. WindowsTerminalでPowershellかCommandPromptでinstallされているかを確認する

    ```powershell
    PS > volta
    Volta 1.1.1
    ```

1. node.jsをインストールする

    ```powershell
    PS > volta install node
    > volta install node
    success: installed and set node@20.11.0 (with npm@10.2.4) as default
    ```

1. nodeのVersionを確認する

    ```powershell
    node -v
    v20.11.0
    ```

### 2. Install Qiita CLI

https://github.com/increments/qiita-cli に沿って実行する