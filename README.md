# LogiEval

**「日報」を「キャリアの資産」へ。**
エンジニアの日常をAIが構造化し、最高の考課面談を実現するキャリア管理ツール。

---

## 💡 Why LogiEval?
エンジニアにとって、日々の業務は「点」でしかありません。しかし、人事評価面談ではそれらを「線（実績）」として語る必要があります。多くのエンジニアが抱える「日報作成の苦痛」と「評価でのアピール不足」という課題を、AIが解決します。

**LogiEvalは、あなたの記録を「評価される実績」へと自動変換します。**

## 🎯 Features

### 1. スマート入力エンジン
- **構造化された入力フォーマット:** Top Task, メモ, 課題, 連絡事項を効率的に記録。
- **マルチデバイス対応:** スマホ・PCからシームレスにアクセス。

### 2. AIインサイト分析
- **自動集約:** 深夜バッチで日報データを収集・分析。
- **評価軸のタグ付け:** 「技術的困難の克服」「ビジネスインパクト」など、面談で評価されやすい軸で成果を自動抽出。
- **面談用台本生成:** 評価を最大化するためのエピソード構成をAIが提案。

### 3. キャリアの資産化
- **Human-in-the-loop:** 翌朝、AIが生成したまとめをユーザーが確認・修正するUI設計。
- **自動ポートフォリオ生成:** 数年分の記録から、半年ごとの成果をまとめたポートフォリオを自動生成。

## 🛡 Security & Privacy
- **機密保持:** 入力フォームでの機密情報検知バリデーションを実装。
- **データ保護:** API利用時のAI学習拒否設定を徹底し、入力データのプライバシーを担保。

## 🛠 Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | Next.js (TypeScript), Tailwind CSS |
| **Backend** | FastAPI (Python) |
| **Database** | Supabase |
| **AI/LLM** | OpenAI API (GPT-4o / GPT-4o-mini) |

## 🚀 Roadmap

- [ ] **Phase 1: MVP Development**
    - 日報入力機能およびAI要約ロジックの構築
- [ ] **Phase 2: Automation & Integration**
    - GitHub/Calendar連携による入力負荷の低減
- [ ] **Phase 3: Beta Testing & Validation**
    - ユーザーテストを通じた月額課金価値の検証
- [ ] **Phase 4: Business Launch**
    - 事業所得としての運用開始、正式リリース

## 💰 Monetization
**月額1,000円のキャリア投資**
面談準備を0にし、年収アップを支援するツールとして、高い費用対効果を提供します。

## ⚖️ License
This project is licensed under the MIT License.
