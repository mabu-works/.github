# mabu-works

まぶが個人開発する **Web サービス** の組織です。
すべてのサービスは Vercel で公開していて、ブラウザだけで動きます（登録不要・無料）。

- 🌐 個人サイト（全サービスまとめ）: https://mabu.vercel.app
- 💬 まぶ鯖公式サイト: https://mabusaba.vercel.app
- 👤 開発者: [@i-mabu](https://github.com/i-mabu)
- 🤖 Bot の組織: [@mabu-bots](https://github.com/mabu-bots)

## サービス一覧

### 防災・生活

| サービス | 内容 |
|---|---|
| [AEGIS Web（bosai）](https://bosai.vercel.app) | 地震・津波・天気を地図でひと目で確認できる防災情報 |
| [通学ダッシュボード公開ページ（densha）](https://densha.vercel.app/info/) | 高崎線・湘南新宿ライン・上野東京ラインの運行情報 |
| [サーバーステータス（sabasute）](https://sabasute.vercel.app) | まぶの Bot 群の稼働状況を公開するページ |

### 画像メーカー

| サービス | 内容 |
|---|---|
| [Make It a Quote（miaq）](https://miaq.vercel.app) | 発言を引用画像風に仕上げるメーカー |
| [Fake Tweet（nisetsui）](https://nisetsui.vercel.app) | ツイート風の画像を作るメーカー |

### ツール・学習

| サービス | 内容 |
|---|---|
| [話題ガチャ（wadaiya）](https://wadaiya.vercel.app) | 雑談の話題をランダムで出すガチャ（109話題） |
| [タイピング練習（taipingu）](https://taipingu.vercel.app) | 日本語ローマ字タイピングの練習 |
| [謎解き・暗号（nazoya）](https://nazoya.vercel.app) | シーザー暗号などの変換と問題カード作成 |
| [集中タイマー（shuchuya）](https://shuchuya.vercel.app) | ポモドーロ式の集中タイマーと記録グラフ |
| [架空プロフィール生成（kakupro）](https://kakupro.vercel.app) | 創作向けの架空プロフィールをランダム生成 |

### 遊び・息抜き

| サービス | 内容 |
|---|---|
| [あみだくじ（amidaya）](https://amidaya.vercel.app) | あみだくじメーカー（結果アニメーション・画像保存） |
| [ルーレット（ruletto）](https://ruletto.vercel.app) | 汎用ルーレット（候補の共有リンク対応） |
| [環境音ミキサー（otoya）](https://otoya.vercel.app) | 雨・波・風・焚き火・電車・夜の虫を重ねて流せる環境音 |
| [診断メーカー（shindanya）](https://shindanya.vercel.app) | 名前と日付で結果が決まる診断（6テーマ） |
| [おみくじ（mikuji）](https://mikuji.vercel.app) | 1日1回の運勢と30日分の履歴 |
| [ミニゲーム集（chibigame）](https://chibigame.vercel.app) | 反応速度・色当て・数字記憶の3ゲーム |

## 技術メモ

- 静的サイトを中心に、サーバーレス関数（Vercel Functions）を組み合わせた構成
- 全サービス PWA 対応（ホーム画面に追加して使えます）
- リポジトリは原則公開しています
