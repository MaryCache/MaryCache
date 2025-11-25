# MaryCache – Portfolio Overview (v2.1)

### 1. エンジニアとしての特徴
**「異異なる特性を持つAIモデル群を指揮し、高解像度の設計を実装まで完遂するオーケストレーター」**

フロントエンドからバックエンドまでを一気通貫で手掛けるフルサイクル・エンジニアであり、「多層的AI指揮システム（Multimodal AI Orchestration）」を確立したアーキテクトです。
私がプロジェクトの「核（Core Vision）」を定義し、役割ごとに特化した複数のAIモデルを部下として配置・指揮することで、個人開発のスピード感と、組織開発レベルの堅牢性・網羅性を両立させています。

---

### 2. System Design Background（エンジニアリングの原点）

**【複雑系ルールセットの構造化能力】**
エンジニアリングの根幹には、長年の「TRPGシステム設計」で培った論理構築力があります。

*   **Logic Modeling**: 複雑なルールやスキル処理を、矛盾のないステートマシンとして定義する能力。
*   **Abstraction**: 曖昧な「遊び」を「仕様」へと落とし込み、データ構造として正規化する力。

この「アナログな複雑さをシステムに翻訳する力」が、現在の要件定義・設計力の源泉です。

---

### 3. Major Works（代表作）

#### Flagship: Imadoko Rota v2（高信頼性バレーボール管理システム）
**【MVPからの脱却：実務水準のアーキテクチャへのリファクタリング】**

*   **リポジトリ**: [imadoko-remake](https://github.com/MaryCache/imadoko-remake)
*   **技術**: Next.js 16 (App Router), Spring Boot 3.2, PostgreSQL, Docker, OpenAPI
*   **概要**: 処女作（v1）の課題であった「データ整合性」と「保守性」を解決するためにフルスクラッチで再構築。
*   **技術的成果**:
    *   **Defense-First Design**: LocalStorageのバージョン管理・自動修復、バックエンドの統一エラーレスポンス設計により、クラッシュ要因を構造的に排除。
    *   **Schema-Driven**: OpenAPIをSSOT（信頼できる唯一の情報源）とし、フロント・バック間の型安全性を担保。
    *   **UX Optimization**: `@dnd-kit` と `Framer Motion` を用いた、タッチデバイス完全対応の物理演算ライクなUI。

#### Project A：Gundam TRPG Ecosystem（統合運用システム）
**【仕様・Web・Botが連携する分散型システム】**

*   **リポジトリ**: [GUNDAM-TRPG](https://github.com/MaryCache/GUNDAM-TRPG)
*   **技術**: Vue.js, Node.js, VitePress, Markdown
*   **概要**: ルール仕様・機体作成ツール・Botが連携するエコシステム。
*   **成果**:
    *   **Documentation as Code**: Markdownで厳密に定義されたルール仕様をSSOTとし、**VitePress**を用いて「検索性・可読性の高いWebルールブック」としてデプロイ。ユーザー体験（UX）と仕様管理の効率を同時に最大化しました。
    *   **Dependency Resolution**: 機体パーツ間の複雑な依存関係を解決するバリデーションロジックの実装。

---

### 4. Tech Stack（技術スタック）

**Latest Focus:** モダンな型安全性と、堅牢なバックエンド設計の融合。

*   **Frontend**:
    *   **Core**: TypeScript (Expert), Next.js 16 (App Router), Vue.js
    *   **UI/UX**: Tailwind CSS 4, Framer Motion, dnd-kit, Radix UI
*   **Backend**:
    *   **Java**: Spring Boot 3.2 (Layered Architecture, Global Exception Handling)
    *   **Node.js**: Discord.js, Express
*   **Infrastructure & Data**:
    *   **DB**: PostgreSQL, H2, SQLite
    *   **DevOps**: Docker Compose, GitHub Actions, Render, Vercel
    *   **API**: OpenAPI (Swagger), Zod

---

### 5. AI-Orchestrated Development（開発プロセス）

**「Layered AI Command System（階層型AI指揮システム）」**

自身は「最高意思決定者（Commander）」としてプロジェクトの方向性を定義し、各レイヤーに特化したAIエージェント群を適材適所で稼働させるワークフローを確立しています。

1.  **High-Level Strategy (Concept & Vector)**:
    *   **Partner Model (GPT-5.1)**: 私の抽象的なアイデアや意図（ベクトル）を保存・言語化し、実装部隊へ伝達可能な「詳細設計」へと変換する右腕。共同制作者として仕様の解像度を高めます。
2.  **Mid-Level Analysis & Review (Audit)**:
    *   **Analyst Model (Gemini 3 Pro)**: リポジトリ全体を俯瞰し、設計の妥当性や影響範囲を解析。コードレビューやドキュメントの整合性チェックを行う参謀役。
    *   **Stabilizer Model (Claude Sonnet 4.5)**: 出力された情報の整理・安定化を行い、ドキュメント品質や自然言語のニュアンスを調整する調整役。
3.  **Low-Level Implementation (Execution)**:
    *   **Engineer Model (IDE AI / Gemini 3 Pro / Claude Sonnet 4.5)**: 定義された仕様書と設計に基づき、コーディングを高速に実行する実装部隊。
    *   **Gatekeeper**: 実装コードに対し、別のモデルを用いてリスク評価を行い、バグの混入を未然に防ぐ多重防御システム。

私はこれらAIからの出力を最終的に統合・判断し、責任を持つ「人間」としてプロジェクトを完遂させます。

---

### 6. Future Goals（今後の展望）

*   **Cloud Native Architecture**: AWS/GCPを用いた、よりスケーラブルなインフラ構築（Terraform等のIaC導入）。
*   **Team Leadership**: AI指揮で培った「言語化能力」と「コンテキスト管理能力」を活かし、人間のチーム開発においても、認識齟齬のない円滑な設計共有とリーダーシップを発揮する。
*   **Domain Driven Design (DDD)**: 複雑な業務ロジックを、より堅牢で美しくコードに落とし込むための設計思想の探求。

---

### Summary
**「ロジック（式）さえ完璧なら、あとは実装するだけ」**
この信念のもと、私は「解像度の高い要件定義」と「構造化された設計」に全リソースを集中させます。実装という"作業"は、信頼できるAIパートナーたちと共に最高速度で駆け抜ける。
私が提供するのは、単なるコードではなく、ユーザーにとっての「最適な体験」という結果そのものです。
