# MaryCache – Portfolio Overview (v2.2)

## 1. エンジニアとしての特徴

**「複数のAIモデルを役割ごとに最適配置し、高解像度設計を実装まで落とし込むフルサイクル・エンジニア」**

私は、フロントエンドとバックエンドの両軸にまたがる開発を行いながら、
GPT / Gemini / Claude / IDE AI などの特性の異なるAIモデルを
**“階層的ワークフロー”として活用する独自の開発プロセス**を確立しています。

* 自分自身がプロジェクトの設計思想（Core Vision）を定義し、
* 各AIを **推論・レビュー・実装・検証** のレイヤに分けて指揮することで、
* **個人開発でありながら組織開発級の再現性と品質** を実現しています。

---

## 2. System Design Background（設計力の源泉）

**複雑なTRPGシステム制作**で培った、
「ルール」「例外処理」「フェーズ」「状態遷移」を構造化する能力がベースにあります。

* 複雑な業務ルールを“矛盾のないステートマシン”として記述
* 曖昧な概念を“データ構造”として落とし込む
* 仕様・データフロー・ゲーム性を同時に扱う抽象化能力

この経験が、現在の **要件定義力 / 設計力 / 抽象度の調整力** に直結しています。

---

## 3. Major Works（代表作）

### Flagship: Imadoko Rota v2（高信頼性バレーボール管理システム）

**「5日で作った処女作を、3ヶ月後に“実務アーキテクチャ”でフルリメイク」**

* **リポジトリ**: [https://github.com/MaryCache/imadoko-remake](https://github.com/MaryCache/imadoko-remake)
* **技術**: Next.js 16 / React 19 / TypeScript / Tailwind CSS v4 / dnd-kit / Spring Boot 3.2 / PostgreSQL / Flyway / Docker / OpenAPI
* **主な成果**:

  * **Defense-First Design**
    LocalStorageのバージョン管理・ErrorBoundary・統一エラーレスポンスで
    フロント/バック双方のクラッシュ原因を構造的に排除。
  * **Schema-Driven Development**
    OpenAPIをSSOT（Single Source of Truth）化し、
    バックエンドのJavaインターフェース・フロントの型定義を自動生成。
  * **UI/UX 最適化**
    dnd-kitによるコート操作、Framer Motionによるモーション表現、
    タッチデバイス完全対応の自然な操作感。

### Project A：Gundam TRPG Ecosystem（ルール×ツール連携システム）

* **リポジトリ**: [https://github.com/MaryCache/GUNDAM-TRPG](https://github.com/MaryCache/GUNDAM-TRPG)
* **技術**: Vue.js / VitePress / Node.js / Markdown
* **概要**:

  * Webルールブック（VitePress）
  * ロジック検証ツール
  * TRPG用Discord Bot
    を一元化した“仕様中心エコシステム”。
* **成果**:

  * **Documentation as Code** によりルール仕様をSSOT化
  * 複雑なパーツ依存・計算式の正規化
  * 実装・世界観・仕様がズレない状態での運用が可能に

---

## 4. Tech Stack

### Frontend

* TypeScript（Advanced）
* Next.js 16（App Router）
* React 19
* Tailwind CSS v4
* dnd-kit / Framer Motion / Radix UI

### Backend

* Java 17
* Spring Boot 3（Layered Architecture / Global Exception Handling）
* Spring Data JPA
* Node.js / Express / Discord.js

### Infra / Tooling

* PostgreSQL / H2 / SQLite
* Docker / Docker Compose
* Render / Vercel
* GitHub Actions
* OpenAPI (Swagger), Zod

---

## 5. AI-Orchestrated Development（AI協働開発フロー）

私は AI を“自動生成ツール”として使うのではなく、
**役割分担させた“チームメンバー”として配置したワークフロー**を組んでいます。

### High-Level（抽象・推論・設計）

**GPT-5.1**

* 抽象的な構想を論理化
* 要件整理 / 仕様策定 / 設計レビュー
* ベクトル管理（方向性の保持）

### Mid-Level（解析・監査・安定化）

**Gemini 3 Pro**

* リポジトリ横断レビュー
* 依存関係解析・整合性評価
* 二次レビュー（Audit）

**Claude Sonnet 4.5**

* 出力文章の安定化
* 自然言語の整形
* リスク分析

### Low-Level（実装・修正・テスト）

**IDE AI（Cursor / Copilot）**

* 実装の高速化
* 変更差分の提案
* 自動リファクタリング

**Gatekeeper（別モデル）**

* 生成コードの妥当性検証
* バグ混入の最終チェック

人間である私は、これらのAIを束ね、
**方向性の決定・品質基準の設定・最終承認**を担当しています。

---

## 6. Future Goals

* **Cloud Native / IaC**
  AWS・GCPを用いたスケーラブルなクラウド構築（Terraform等）
* **Team Leadership**
  AI指揮で得た「コンテキスト統制能力」を、人間チーム開発にも展開
* **DDDの深掘り**
  複雑な業務ロジックを美しく表現するためのモデル化技術の強化

---

## Summary

**「ロジック（式）が正しく設計されていれば、実装は速く・正確に進む」**

私は

* 解像度の高い仕様策定
* AIを活用した構造的なレビュー
* 堅牢で説明できるアーキテクチャ設計
  を重視し、最終的に**ユーザー体験としての価値**を届けることを目指しています。
