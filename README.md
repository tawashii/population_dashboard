# 🇯🇵 日本人口動態分析ダッシュボード

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Plotly](https://img.shields.io/badge/Plotly-5.0+-green.svg)](https://plotly.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 📋 プロジェクト概要

総務省統計局の人口データを活用し、日本の人口動態を多角的に分析・可視化するインタラクティブダッシュボードです。
少子高齢化や地域格差などの社会課題を、データに基づいて客観的に把握できます。

### 🎯 解決する課題
- 人口動態の変化を直感的に理解したい
- 都道府県別の人口トレンドを比較分析したい
- 年齢構成の変化を時系列で把握したい
- データに基づいた政策提言の根拠が欲しい

## ✨ 主な機能

- **📊 都道府県別人口推移**: 主要5都道府県の10年間の人口変化を可視化
- **👥 年齢構成分析**: 年少・生産年齢・高齢者人口の構成比推移
- **📈 人口増減率ランキング**: 2020-2023年の増減率トップ10
- **📉 人口分布ヒストグラム**: 全国の人口分布状況
- **🎨 レスポンシブデザイン**: PC・タブレット・スマホ対応

## 🛠️ 技術スタック

### Backend
- **Python 3.8+**
- **pandas**: データ処理・分析
- **plotly**: インタラクティブグラフ生成

### Frontend
- **HTML5/CSS3**: モダンなUIデザイン
- **JavaScript**: 動的グラフ描画
- **Plotly.js**: リアルタイムデータ可視化

### データソース
- 総務省統計局「住民基本台帳に基づく人口、人口動態及び世帯数」

## 🚀 クイックスタート

### 必要な環境
```bash
Python 3.8以上
```

### インストール
```bash
# リポジトリをクローン
git clone https://github.com/yourusername/japan-population-dashboard.git
cd japan-population-dashboard

# 必要なパッケージをインストール
pip install -r requirements.txt
```

### 実行方法
```bash
# ダッシュボード生成
python population_dashboard.py

# ブラウザでindex.htmlを開く
```

## 📁 プロジェクト構成

```
japan-population-dashboard/
├── population_dashboard.py    # メインスクリプト
├── requirements.txt          # 依存関係
├── index.html               # 生成されるダッシュボード
├── data/                    # 生成されるデータフォルダ
│   ├── real_population_data.csv
│   └── age_composition_data.csv
├── README.md
└── LICENSE
```

## 📊 分析結果のハイライト

- **東京一極集中の継続**: 東京都の人口は2014年から2023年で約60万人増加
- **少子高齢化の加速**: 65歳以上人口比率が25.8%→30.2%へ上昇
- **生産年齢人口の減少**: 15-64歳人口比率が61.3%→58.2%へ低下
- **地域格差の拡大**: 大都市圏と地方の人口格差が拡大傾向

## 🎨 デモ

ブラウザで `index.html` を開くと、以下の機能を持つダッシュボードが表示されます：
- 📊 都道府県別人口推移グラフ（インタラクティブな線グラフ）
- 👥 年齢構成の時系列変化（積み上げエリアチャート）
- 📈 人口増減率ランキング（横棒グラフ）
- 📉 人口分布ヒストグラム（度数分布）

すべてのグラフでマウスオーバー、ズーム、パンなどのインタラクティブ操作が可能です。

## 🤝 コントリビューション

プルリクエストやイシューの報告を歓迎します！

1. このリポジトリをフォーク
2. フィーチャーブランチを作成 (`git checkout -b feature/AmazingFeature`)
3. 変更をコミット (`git commit -m 'Add some AmazingFeature'`)
4. ブランチにプッシュ (`git push origin feature/AmazingFeature`)
5. プルリクエストを作成

## 👨‍💻 作成者

**あなたの名前**
- 🐙 GitHub: [@ytawashii](https://github.com/tawashii)
- 🐦 X (Twitter): [@tawashii_](https://x.com/tawashii_)

## 📚 参考資料

- [総務省統計局](https://www.stat.go.jp/)
- [Plotly Documentation](https://plotly.com/python/)
- [pandas Documentation](https://pandas.pydata.org/docs/)

---

⭐ このプロジェクトが役に立った場合は、スターをつけていただけると嬉しいです！