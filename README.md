# 温泉MAP TOKYO（公開用ファイル）

東京の温泉・銭湯マップのWebサイト一式です。GitHub Pages でそのまま公開できます。
公開されるURL: https://cpusakura.github.io/onsen-map-tokyo/

## フォルダの中身

| ファイル／フォルダ | 内容 |
|---|---|
| `index.html` | 地図で探せるメインページ |
| `onsen/` | 施設ごとのページ（78軒） |
| `spring/` | 泉質ごとの一覧ページ |
| `ward/` | 区・市町村ごとの一覧ページ |
| `area/` | 23区・多摩・島しょの一覧ページ |
| `assets/site.css` | 施設ページ用のデザイン |
| `header.jpg` | ヘッダー画像（SNS共有の画像にも使用） |
| `sitemap.xml` / `robots.txt` | 検索エンジン向けの案内 |
| `404.html` | ページが見つからないときの表示 |

## 公開の手順

1. GitHub で **New repository** を押し、名前を `onsen-map-tokyo`、公開設定を **Public** にして作成します。
2. 作ったリポジトリの画面で **uploading an existing file**（または Add file → Upload files）を押します。
3. このフォルダの中身を**2回に分けて**ドラッグします（1回のアップロードは100ファイルまで）。
   - 1回目: `onsen` フォルダ**以外**のすべて（`index.html`、`spring`、`ward`、`area`、`assets`、`header.jpg`、`sitemap.xml`、`robots.txt`、`404.html`、`README.md`）
   - 2回目: `onsen` フォルダ
   - 各回、下の **Commit changes** を押して確定します。
4. **Settings → Pages** を開き、Source を **Deploy from a branch**、Branch を `main` / `/(root)` にして Save します。
5. 数分後、`https://cpusakura.github.io/onsen-map-tokyo/` で公開されます。

## 公開したあとにやること

- **Google Search Console に登録**し、`sitemap.xml` を送信します。検索結果に出るまで数日〜数週間かかります。
- 営業時間などの情報を直したときは、該当する `onsen/` のページと `index.html` の両方を更新します。

## 注意

- 営業時間・定休日・料金などは変更されることがあります。
- お問合せフォームは公開版には含まれていません。
