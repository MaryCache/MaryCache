# MaryCache

**フルスタックエンジニア（個人開発）**  
Java / TypeScript / Next.js / Spring Boot / PostgreSQL / AWS / Cloudflare

---

## About

IT企業所属。業務外で継続的に個人開発を続けています。
自身の携わるあらゆるシステムについて、「動けばいい」で終わらせるのは勿体ないので、必ず技術資産に還元するようにしています。
「自身がシステムを理解し、知識のない一般人にそれを分かりやすく説明、プレゼンできる状態」を「完成」と定義しています。

---

## Projects

### [hitohira-nikki](https://github.com/MaryCache/hitohira-nikki)
**AI連携日記アプリ（本番稼働中）**

```
Next.js / Supabase / PostgreSQL / Cloudflare Workers / GitHub Actions
```

日記エントリの記録・分析・感情スコアリングを行うWebアプリです。
Claudeのスキル機能を活用し、簡単な会話から日記のJSONデータを三分で作ることが出来ます。
APIは使わず、Claudeがチャット上で吐き出したJSONをユーザーがフォームへコピペする方式を採用しています。

- Supabase RLSによる認証・アクセス制御の設計と実装
- soft-deleteパターンの設計、論理削除と物理削除の使い分け
- GitHub Actions × OpenNext × Cloudflare Workersによる自動デプロイパイプライン
- JSON形式のデータインポート機能、モバイル対応

内部では11軸の感情スコアリングシステムを持っていますが、ユーザー向けには5カテゴリに抽象化して提供しています。
設計の複雑さをUIに漏らさないことを強く意識していました。
テーマは、AIによる「アナログ概念の定量化」「認知負荷の代替」です。

---

### [imadoko-remake](https://github.com/MaryCache/imadoko-remake)
**バレーボール座席管理アプリ フルリメイク**

```
Next.js / Java 21 / Spring Boot 3.2 / PostgreSQL / Docker / OpenAPI
```

プログラミングを初めて一週間で作成した処女作Webアプリ（SQLite + React + Spring Boot）を3ヶ月後に書き直したものです。

- OpenAPI Specで仕様を一元管理し、フロント・バック双方のコード生成の起点にした
- バリデーション・エラーハンドリングを後付けではなく設計段階で組み込んだ
- Java 21のRecord / Sealed Classを活用した型安全な実装
- DockerによるDB・アプリのコンテナ化

「とにかく動かす」から「設計から入る」への、エンジニアとしてのレベルアップをテーマに開発しました。

---

### [GUNDAM-TRPG](https://github.com/MaryCache/GUNDAM-TRPG)
**オリジナルTRPGシステム統合エコシステム**

```
TypeScript / Vue.js / VitePress / Node.js / Discord.js / PostgreSQL
```

自作TRPGシステム「G.B.S（Gundam Battle System）」のルールブック・キャラ作成Webアプリ・Discord Botを複数リポジトリで構成した統合システムです。

- ルール仕様をMarkdownで一元管理し、Webルールブック・Bot・検証ツールすべての実装基盤にした
- VitePressによるMarkdown駆動のWebルールブック構築（Documentation as Code）
- Discord.js v14のスラッシュコマンド・セレクトUI・Ephemeralメッセージを活用したUX設計
- VueによるWebアプリ構築、CSSを活用した、美麗なUIデザイン設計
- 状態遷移・依存関係・例外処理を設計段階で整理し、矛盾のない仕様を維持した

「ゲームルール」を設計として扱った経験が、今の自分の土台になっています。

---

## Skills

| カテゴリ | 技術 |
|---|---|
| フロントエンド | Next.js / React / Vue.js / TypeScript |
| バックエンド | Java 21 / Spring Boot 3.x / Node.js |
| データベース | PostgreSQL / Supabase / SQLite / Oracle DB |
| インフラ | AWS（EC2 / RDS） / Cloudflare Workers / Docker |
| 設計・開発手法 | OpenAPI / RLS / CI/CD（GitHub Actions） / SSoT設計 |

---

## Development Style

- 実装前にデータ構造・状態遷移・依存関係を整理する
- 仕様・実装・ドキュメントの乖離を構造的に防ぐ（SSOT意識）
- RLS・エラーハンドリング・CI/CDを後付けではなく設計段階に組み込む
- Claude（チャット・スキルエコシステム設計）を開発ワークフローに組み込み、設計・ドキュメント・コード生成・レビュー・自己学習に活用している
- Claudeスキルを活用した自動ワークフローでWebクローリング及びスクレイピングを行い、技術知識を取得する

---

## Contact

GitHub: [@MaryCache](https://github.com/MaryCache)
