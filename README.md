# 🐒 mandalamonchy — Monta, the Mandara Maker

**QQ #012 / QuestQueries Series / Mandala Coach**

> 「考える前に、手を動かしてみようか。」

---

## これは何？

モンタは、**マンダラチャートを対話しながら作るコーチアプリ**です。

マンダラチャートは9×9（81マス）のフレームワーク。  
中心に目標を置き、8つの柱と64のアクションで埋めていきます。  
年間目標だけじゃなく、課題整理やブレインストーミングにも使えます。

モンタが先に「叩き台」を出すので、ゼロから考える必要はありません。  
詰まったら「どうした？じゃあ僕が書いてみるよ」と手を動かしてくれます。

---

## 使い方

### 1. APIキーを設定する
[Anthropic Console](https://console.anthropic.com/settings/keys) でAPIキーを取得。  
アプリを開いたらモーダルに入力 → 保存。  
キーはブラウザのlocalStorageにのみ保存されます。

### 2. モンタと話す
進め方を選ぶところから始まります。

- **提案型**（おすすめ）— モンタが先に叩き台を出す。選んで調整するだけ。
- **対話型** — 一つずつ、じっくり一緒に考える。

### 3. チャートを育てる
- Step 1 → 進め方の確認
- Step 2 → 心の温度確認（嬉しかったこと・もやもや・自分らしさ）
- Step 3 → 中心目標を3案から選ぶ
- Step 4 → 8つの柱を決める
- Step 5 → 各柱の行動を決める（「残りはおまかせ」も可）
- Step 6 → 確認・調整
- Step 7 → 完成 → HTMLで保存

### 4. 保存する
チャート完成後、プレビューカードが表示されます。  
「HTMLを保存」ボタンでそのまま手元に。ズーム・印刷対応済み。

---

## ポイント

- **全部埋めなくていい** — 空欄は伸び代
- **後で変えればいい** — 作って終わりじゃなく、日々更新するもの
- **「おまかせ」「スキップ」が使える** — 疲れたらモンタに任せよう

---

## キャラクター

| | |
|---|---|
| 名前 | mandalamonchy — Monta, the Mandara Maker |
| 愛称 | モンタ 🐒 |
| 口癖 | 「考える前に、手を動かしてみようか」 |
| 詰まったとき | 「どうした？じゃあ僕が書いてみるよ」 |
| 性格 | 飄々としてるけど、手だけは異様に速い職人サル |

---

## 技術スタック

- Vanilla JS / Single HTML file
- Anthropic Claude API（`claude-sonnet-4-20250514`）
- Google Fonts: Zen Kaku Gothic New / Space Mono
- ダーク/ライトモード対応（`prefers-color-scheme`）
- APIキー: localStorage保存

---

## QuestQueries シリーズ

セナリ学院発、AIを使った一人一枚のアプリ集。  
「モヤモヤを結晶化する」をコンセプトに、シンプルで壊れないHTMLアプリを作っています。

GitHub: [MonoMonoMonozu](https://github.com/MonoMonoMonozu)

---

*mandalamonchy — Monta, the Mandara Maker / QQ #012 / QuestQueries*
