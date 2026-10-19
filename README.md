# 水島工場 新事務所｜建築コンセプト・ストーリー

GitHub Pagesへ手動アップロードするためのビルド済みデータです。Node.jsやビルド操作は不要です。

## 公開方法

1. このZIPを展開します。
2. GitHubの公開リポジトリ `os_mizushima_factory` に、展開した「中身」をアップロードします。
   `index.html`、`assets` フォルダー、`data` フォルダーがリポジトリ直下に並ぶようにしてください。ZIPファイル自体をアップロードする方法では動きません。
3. リポジトリの Settings → Pages を開き、Source を「Deploy from a branch」、Branch を「main」、Folder を「/ (root)」にして Save を押します。
4. 配備後、Settings → Pages に表示されるURLから閲覧できます。

通常のURL形式は `https://GitHubユーザー名.github.io/os_mizushima_factory/` です。
`.nojekyll` は付属の空ファイルです。ドットから始まるため見えない場合もあります。
GitHub Actionsの設定や、ライブラリのインストールは必要ありません。

## 起動・操作

45秒・7シーンの自動再生、シーン選択、シーク、カメラ操作、表示設定、PNG保存に対応しています。
効果音は「音付きで再生」をクリックすると有効になります。Hキーで操作UIの表示を切り替えます。

## 更新

更新版を同じ構成でアップロードし、既存ファイルを差し替えてコミットします。
これは配信用データです。形状やコードを修正する場合は別途制作ソースを編集・再ビルドしてください。

## 資料と模型

提供図面・パースの参照画像を含む公開用データです。模型には資料に基づく近似表現を含みます。

## 公式手順

https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
