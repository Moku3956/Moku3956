# こんにちは、Moku3956です。

### 🚀 自己紹介 / About Me
現在(2026/04)、大学3回生です。主に **[Python, Go言語, TypeScript, JavaScript]** を中心に、Webアプリケーションの開発に取り組んでいます。

---

### 🛠 技術スタック / Tech Stack
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)

---

---

### 🏆 注力リポジトリ / Featured Projects

#### 1. [習慣クエスト](リポジトリ: https://github.com/Moku3956/daily-routine)
- **概要:** その日の「体力・やる気」に合わせて、ロジックが習慣の優先順位や目標値を自動調整する、RPG感覚の習慣管理アプリ。
- **現状:** まだまだ製作途中です。設計、アーキテクチャ選定などを終えているが、実装途中。
- **使用技術(予定):**
  - **バックエンド:** Go, Gin, GORM, PostgreSQL
  - **フロントエンド:** Next.js (App Router), TypeScript, Tailwind CSS, TanStack Query
- **こだわった点:** **「変更に強くテストが容易なバックエンド設計」**
  - **設計思想:** **ヘキサゴナルアーキテクチャ**を採用し、ビジネスロジックをフレームワークやDBから完全に分離しました。
  - **技術的工夫:** インターフェースを用いた依存注入（手動DI）を徹底し、外部依存をアダプター層に閉じ込めることで、保守性とテストのしやすさを向上させています。
  - **ドキュメント:** 開発効率と品質向上のため、ER図、シーケンス図、OpenAPIによるAPI定義 を事前に完備して開発を進めています。

#### 2. [学内道案内アプリ](リポジトリ: https://github.com/Moku3956/guide-to-shop)
- **概要:** 学園祭の来場者向けに、現在地から目的地までの最短ルートをリアルタイムで案内するWebアプリ。
- **アプリURL:** https://ritsumei-noji-collection.vercel.app
- **使用技術:**
  - **バックエンド:** Python (FastAPI)
  - **フロントエンド:** JavaScript (Vanilla JS)
- **こだわった点:** **「低スペック端末でもサクサク動く軽量な経路探索」**
  - **課題:** 実行時の全地点（約50箇所）の距離再計算による処理の重さと、アルゴリズムの実装難易度。
  - **工夫:** 主要ルートをノードとエッジの辞書形式で事前定義。さらに、ルートから一定距離外れた時のみ再検索するロジックを実装。
  - **結果:** 低負荷な動作を実現し、学園祭当日のスムーズな運営と来場者の利便性向上に貢献しました。


