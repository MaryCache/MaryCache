# MaryCache – Portfolio Overview

### 1. エンジニアとしての特徴
**「設計から実装までを一気通貫で完遂する、システム志向のエンジニア」**

**Findy Skill Score: TypeScript 68.4 (上位数%)**
TypeScriptを中心とした堅牢な型定義をベースに、Vue.jsによる複雑なUI構築（フロントエンド）と、Node.js/Javaを用いたバックエンドロジックの実装を両軸で行います。
最大の特徴は、コーディング前の「要件定義と設計」への徹底したこだわりです。AI（LLM）を単なる生成ツールではなく「実装パートナー」として指揮・監督し、自身の設計を高速かつ高品質にコードへ変換する独自の開発フローを確立しています。

---

### 2. System Design Background（エンジニアリングの原点）

**【アナログゲーム設計による論理構築経験】**
プログラミング習得以前より、TRPGのルールシステム構築を行ってきました。これは単なる創作ではなく、**「言語化された仕様書（ルール）に基づき、矛盾なく処理を実行する論理システム」**の設計経験です。

*   **State Machine Design**: 戦闘処理におけるフェーズ遷移（準備→実行→終了）の厳密な定義。
*   **Async / Sync Control**: 複数プレイヤーの入力待機と、同期的な一斉処理のフロー構築。
*   **Data Modeling**: キャラクターやスキルを「プロパティ」と「メソッド」を持つオブジェクトとして構造化。

この経験により、**「複雑な業務ロジックのシステム化」**を得意としています。

---

### 3. Major Works（開発実績）

#### Project A：Gundam TRPG Ecosystem（統合運用システム）
**【仕様策定・Web・Botが連携する分散型システム】**

単一のアプリではなく、仕様（ルール）・入力（Web）・処理（Bot）が連携するエコシステムを構築しました。

*   **Core Logic ([GUNDAM-TRPG](https://github.com/MaryCache/GUNDAM-TRPG))**:
    Markdownによる厳密な仕様策定。システム全体のSingle Source of Truth（信頼できる唯一の情報源）。
*   **Frontend ([ms-builder](https://github.com/MaryCache/ms-builder))**:
    Vue.js + TypeScript。「積載量」や「コスト」など、パーツ間の複雑な依存関係（Dependency）とトレードオフを解決する機体作成ツール。
*   **Backend ([gbs-bot](https://github.com/MaryCache/gbs-gundam-battlesystem-bot))**:
    Node.js + Discord.js。Webアプリが出力したJSONデータを読み込み、ゲーム進行を管理する実行環境。共通のデータスキーマを定義し、完全なデータ互換性を実現。

#### Project B：Imadoko Rotate（試合進行管理システム）
**【Java / Spring Boot によるバックエンド構築と高速開発】**

*   **リポジトリ**: [imadoko-rotate](https://github.com/MaryCache/imadoko-rotate)
*   **技術**: Java 17, Spring Boot, Vue.js, SQLite
*   **概要**: バレーボールの複雑なローテーションルールとスコア整合性を管理するシステム。
*   **成果**: 学習開始5日目でプロトタイプを完成。依存関係（Dependency Hell）の解消や、フロント・バック間のAPI通信実装を通じて、未知の技術領域への適応力を証明しました。

#### Project C：Cthulhu Support Bot（UX特化型Bot）
**【プラットフォーム制約の突破とUX最適化】**

*   **リポジトリ**: [Call-of-Cthulhu-bot](https://github.com/MaryCache/Call-of-Cthulhu-bot)
*   **概要**: 外部サイトデータ連携とリアルタイムステータス更新機能を備えたBot。
*   **技術的挑戦**:
    *   **Data Integration**: 外部サイトの出力データを解析・変換して取り込むインポート機能。
    *   **Stateful UX**: Discord APIを活用し、メッセージを「追記」するのではなく「編集」することで、ログを汚さずにステータスを可視化するリアルタイム更新処理。

---

### 4. Tech Stack（技術スタック）

フロントエンドのUI設計から、型安全なロジック実装、バックエンドのAPI構築まで対応可能です。

*   **Languages**: TypeScript (Main / Findy 68.4), JavaScript, Java, HTML5, CSS3
*   **Frontend**: Vue.js (Composition API / Script Setup), TailwindCSS
*   **Backend**: Node.js, Discord.js, Spring Boot (Basic)
*   **Tools**: Git/GitHub, VS Code, Vite, Figma/ClipStudio (UI Design)

---

### 5. AI-Augmented Development（開発プロセス）

**「AIに思考を丸投げせず、仕様を完全に支配した上で実装させる」**
自身はPM兼テックリードとして振る舞い、AIをエンジニアとして稼働させるフローを採用しています。

1.  **Requirement Definition (Human)**: 解決すべき課題の特定と「あるべきユーザー体験」の定義。
2.  **Logic Design (Human)**: アルゴリズムとデータ構造の確定。AIに推測の余地を与えないレベルまで仕様を詰める。
3.  **Implementation (AI + Human)**: GitHub Copilot / ChatGPTを活用し、高速コーディング。生成されたコードは必ず自身でレビューし、ロジックの整合性を担保する。
4.  **Refactoring (Human + AI)**: 可読性と保守性（コンポーネント分割など）の観点からコードを最適化。

---

### 6. Future Goals（今後の目標）

*   **テスト駆動開発（TDD）の導入**: Jest/Vitestを用いたテスト自動化により、リファクタリング耐性の高いコードベースを構築する。
*   **より堅牢なバックエンド連携**: Node.jsだけでなく、Java/Spring BootやRDB（PostgreSQL等）を用いた本格的なデータ永続化層の設計・実装に挑戦する。
*   **ユーザー体験からの逆算**: 技術はあくまで手段と捉え、「ユーザーにとって最高の体験は何か」というゴールから逆算した技術選定・設計を続ける。

---

### Summary
**「ロジック（式）さえ完璧なら、あとは実装するだけ」**
この信念のもと、要件定義と設計にリソースを集中させるスタイルで開発を行っています。TRPG制作で培った論理的思考力と、AIを活用した実装力を掛け合わせ、複雑な業務課題を解決するシステムを高速に構築できるエンジニアです。
