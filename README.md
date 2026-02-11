# Az Social Insurance Labor Consultant Office Website

アズ社会保険労務士事務所のウェブサイトプロジェクトです。

## 別のPCで作業する方法

### 1. 準備（初回のみ）
自宅のPCなどにGitをインストールし、このリポジトリをダウンロード（クローン）します。

1.  Gitをインストールします（まだの場合）。
2.  ターミナル（PowerShellやコマンドプロンプト）を開きます。
3.  作業したいフォルダに移動し、以下のコマンドを実行します：
    ```bash
    git clone https://github.com/watarant/as-sr-office.git
    ```

### 2. 作業を始めるとき
作業を始める前に、必ず最新の状態を取得してください。

```bash
git pull origin main
```

### 3. 作業が終わったら
変更を保存してGitHubにアップロードします。

```bash
git add .
git commit -m "変更内容のメモ"
git push origin main
```
