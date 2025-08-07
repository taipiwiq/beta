# 教育機関向けクイズ管理・解答アプリ（開発中）
> 現場の先生が本当に使いやすい作問・解答管理ツールを目指して開発中。

このアプリケーションは、学校や学習塾などの教育現場向けに設計された、クイズの作成・実施・成績管理を一元化するWebアプリです。  
Flask + PostgreSQL + Bootstrap で構築しており、ユーザー認証、ロール制御、作問・解答・履歴表示などの基本機能を備えています。

---

## デモ環境

- プレイヤー用（生徒向け）：  
  https://test-k3vp.onrender.com/

- 管理者用（教員・作問者向け）：  
  https://testcode-elzz.onrender.com/

---

## ログイン情報（サンプル）

※ユーザーを作成してもらってもOKです。管理画面では権限がないと開くことができません。

### 生徒（プレイヤー）用：
- ユーザー名：`0000`  
- パスワード：`0000`

### 管理者用：
- ユーザー名：`0000`  
- パスワード：`0000`

---

## 使用技術一覧

<p style="display: inline">
  <!-- フロントエンド -->
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=for-the-badge">
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=for-the-badge">
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white&style=for-the-badge">
  <!-- バックエンド -->
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge">
  <img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white&style=for-the-badge">
  <img src="https://img.shields.io/badge/Flask--Login-000000?style=for-the-badge&logo=lock&logoColor=white">
  <img src="https://img.shields.io/badge/Werkzeug-308446?style=for-the-badge&logo=werkzeug&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white&style=for-the-badge">
  <!-- デプロイ・インフラ -->
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?logo=github&style=for-the-badge&logoColor=white">
</p>

---

## 主な機能（現時点）

- [x] ユーザー認証（ログイン・サインアップ・ログアウト）
- [x] ユーザーの権限制御（管理者／プレイヤー）
- [x] 問題作成（ジャンル・単元ごと）
- [x] 問題解答・時間計測
- [x] 解答履歴表示（スコア・履歴一覧）
- [x] 問題編集・削除機能（管理者）
- [x] モバイル端末対応（レスポンシブ一部対応）

---

## 開発中・今後追加予定の機能

- [ ] ランキング表示（学年別・単元別）
- [ ] スタンプ報酬／称号システム（モチベーション支援）
- [ ] クイズの難易度管理
- [ ] スマートフォン向けUI最適化
- [ ] 通知機能（メール・アプリ内）
- [ ] 管理者のユーザー管理画面の強化
- [ ] 自動出題（問題のランダム化）

---

## ディレクトリ構成（簡易）

```
project/
├── quiz_app/              # 生徒用アプリ（Flask Blueprint）
│   ├── routes.py
│   ├── templates/
│   └── static/
├── admin_app/             # 管理者用アプリ（Flask Blueprint）
│   ├── routes.py
│   ├── templates/
│   └── static/
├── shared/                # DB接続・ユーザー認証など共通処理
│   ├── db.py
│   ├── auth.py
│   ├── models/
│   └── templates/         # 共通テンプレート
├── run_quiz.py            # 生徒用アプリ起動スクリプト
├── run_admin.py           # 管理者用アプリ起動スクリプト
├── requirements.txt       # Python依存パッケージ定義
└── README.md              # このプロジェクトの説明ファイル

```

---

## 想定利用シーン

- 学校の授業における小テストや、課題の電子化
- 塾での単元別演習問題の提供
- 教員による生徒の成績把握とフィードバック支援
- モチベーション支援のためのスタンプ報酬機能（開発中）

---

## 開発者

- **名前**：  たいぴー ( taip )
- **GitHub**： [https://github.com/taipiwiq]  
- **ポートフォリオ**： []

---

## お問い合わせ

ご質問・改善提案・導入希望などあれば下記まで、お気軽にお問い合わせください。

メール　：  taip250802@gmail.com 
インスタ：　 
　　X　 ：　@taip0802

---


