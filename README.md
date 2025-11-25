# MaryCache – Portfolio Overview (v3)

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
**役割を明確に割り当てた「マルチAIチーム」として編成し、
人間がその上位レイヤ（指揮・抽象・統合）を担う開発方式**を採用しています。

---

# 👑 Human Layer（Direction / Vector / Integration）

私は各プロジェクトの **最上位レイヤ（意思決定層）** を担当します。

**担当レイヤ**

* 方向性（ベクトル）の定義と維持
* 抽象化・設計の初期化
* 各AIへの役割分配（オーケストレーション）
* 生成物の比較・統合
* リスク評価と最終意思決定

**役割**

* 長期プロジェクトで最も重要な「文脈の保持」を一手に引き受ける
* AI間の齟齬を統合し、一貫したアーキテクチャに収束させる
* AIが苦手な「責務境界」「仕様の固有解」部分を補完
* プロダクトの世界観・品質基準の管理者
* AIの弱みや限界を、「抜け道」「発想の逆転」により補完

AIは強力ですが、**統合・判断・方向付けは人間の責務であり、ここが開発全体の中枢になります。**

---

# 🟣 ChatGPT

**High-Level：抽象・方針・共同設計**

**担当レイヤ**

* 高レイヤ（抽象モデル / 推論 / 仕様設計）

**役割**

* ユーザーの“意図ベクトル”の解読と保持
* 抽象概念の再構築、設計方針の精密化
* 設計案の生成・比較・統合
* GeminiやIDEに渡す指示の最適化（翻訳役）
* 思考整理と壁打ち（認知の補助輪ではなく並走者）

---

# 🔷 Gemini

**Mid-Layer：解析・横断レビュー・一次監査**

**担当レイヤ**

* 中レイヤ（レビュー・解析・特性評価）

**役割**

* Geminiの一次レビュー結果を再監査（Review-of-Review）
* リポジトリなど大きなデータの解析
* 依存関係解析・責務の整合性チェック
* 設計と実装の隙間を埋める監査

---

# 🟤 Claude Sonnet

**High ↔ Mid Layer：安定化・再構成・文章品質**

**担当レイヤ**

* 中〜高レイヤ（日本語整形・論理安定化）

**役割**

* Geminiの一次レビュー結果を再監査（Review-of-Review）
* 長文の論理整合性チェック
* ドキュメントの安定化（読みやすい形へ）
* 文章の自然さ・語彙の整え直し

---

# 🔶 Gemini(Google AI Studio版)

**Meta-Layer：厳めの監査・戦略補助・IDE命令書生成**

**担当レイヤ**

* 中〜高レイヤ（レビュー of レビュー / 戦略）

**役割**

* Geminiの一次レビュー結果を再監査（Review-of-Review）
* 改修フェーズの優先度・ロードマップ提示
* IDE向け「実装プロンプト（指示書）」生成
* プロダクトの実利性・技術選択の合理化

---

# 🟡 IDE AI（Antigravity）

**Low-Layer：実装・検索・ゲートキーパー**

**担当レイヤ**

* 低レイヤ（実装・修正・パッチ適用）

**役割**

* 実装の高速化
* ファイル検索・関連ファイルの特定（司書機能）
* 一次レビュー/二次レビュー用の情報整理
* 実装タスクのエスカレーション（ChatGPTやGeminiへ）

---

# ## 🔧 全体像：マルチAIパイプライン統合

```
Human（私）
 ├─ 抽象・設計・方向性（GPT-5.1）
 ├─ 一次監査・依存関係・構造解析（Gemini）
 ├─ 文章・論理安定化（Claude）
 ├─ サブレビュー・戦略補助（Gemini : Google AI Studio）
 └─ 実装・差分（IDE AI）
```

人間はこの全体を束ね、
**「抽象 → 設計 → 監査 → 実装 → 再設計」** の循環を維持します。

AIは強力だが、
**AI同士の成果物を統合し、責務境界を管理し、品質基準を担保するレイヤは人間だけ。**

私はここを担当しているため、
“AIディレクター / AIオーケストレーター” として機能しています。

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
