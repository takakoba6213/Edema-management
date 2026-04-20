# 医学書まとめ — 浮腫（Edema Management）

医学書の内容をすぐに復習できるインタラクティブなHTMLノートです。

---

## 浮腫まとめ

[![Open Summary](https://img.shields.io/badge/%F0%9F%93%96_%E6%B5%AE%E8%85%AB%E3%81%BE%E3%81%A8%E3%82%81%E3%82%92%E9%96%8B%E3%81%8F-blue?style=for-the-badge)](https://takakoba6213.github.io/Edema-management/浮腫まとめ_復習用.html)

[![Open Index](https://img.shields.io/badge/%F0%9F%8F%A0_Index%E3%83%9A%E3%83%BC%E3%82%B8-2c5f7c?style=for-the-badge)](https://takakoba6213.github.io/Edema-management/)

> **注意:** 上のボタンは GitHub Pages を有効にすると機能します。  
> リポジトリの **Settings → Pages → Source** で `main` ブランチを選択してください。

---

### 内容

「総合診療でみのがさない浮腫」（中外医学社）と「Peripheral Edema: Evaluation and Management in Primary Care」（Am Fam Physician 2022）をベースに、以下の4タブで構成されています。

| タブ | 内容 |
|------|------|
| **🔍 鑑別アルゴリズム** | PODCAST法に基づく入力フォーム → Semantic Qualifier自動生成 → スコア順の鑑別候補表示 |
| **📋 チェックリスト** | 12セクションの診療フロー（原則・病態生理・問診・診察・検査・胸腹水・上肢・下肢・全身・薬剤性・治療・ピットフォール） |
| **👁 一目まとめ** | 網羅的カード＆テーブル（4機序・年齢別・緊急疾患・Wells基準・STOP-Bang・SORT推奨・診断アルゴリズム） |
| **📚 参考文献** | DOIリンク付きの文献一覧 |

### 主な特徴

- **PODCAST鑑別アルゴリズム** — Progression / Onset / Duration / Consistency / Aggravating-Alleviating / Setting-Severity / Timing-Trigger の各項目を選択すると、50以上の鑑別疾患からマッチ度順に候補を表示
- **Semantic Qualifier** — 選択した臨床情報から1行の臨床要約文を自動生成（コピー可能）
- **Wells基準 / STOP-Bang** — DVTの検査前確率、閉塞性睡眠時無呼吸のスクリーニングスコア
- **身体所見の尤度比（LR+）** — S3（11.0）、腹部頸静脈逆流（6.4）、JVD（5.1）など
- **インタラクティブチェックリスト** — セッション中のチェック状態を保持、進捗バッジ表示
- **レスポンシブデザイン** — PC・タブレット・スマートフォン対応
- **単一ファイル** — 外部依存なしのスタンドアロンHTML

### 出典

- 総合診療でみのがさない浮腫（中外医学社）
- PODCAST法：小林尭広 著『ただいま登壇中！ Dr.'s Prime Academia すべての主訴に使える！ 問診フローチャート―PODCAST法』（中外医学社）[リンク](https://www.chugaiigaku.jp/item/detail.php?id=4343)
- Patel H, Skok CJ, DeMarco A. Peripheral Edema: Evaluation and Management in Primary Care. *Am Fam Physician*. 2022;106(5):557-564
- Wells PS, et al. *N Engl J Med*. 2003;349(13):1227-1235
- Chung F, et al. *Anesthesiology*. 2008;108(5):812-821

---

### GitHub Pages の有効化手順

1. このリポジトリの **Settings** を開く
2. 左メニューの **Pages** を選択
3. **Source** で `Deploy from a branch` を選択
4. **Branch** で `main` / `/ (root)` を選択して **Save**
5. 数分後に `https://takakoba6213.github.io/Edema-management/` でアクセス可能になります

---

### ファイル構成

```
Edema-management/
├── index.html                  ← ポータルページ（まとめ一覧）
├── 浮腫まとめ_復習用.html       ← 浮腫の包括的まとめ（メインコンテンツ）
└── README.md                   ← このファイル
```

---

*Built with the help of Claude*
