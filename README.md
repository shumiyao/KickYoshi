# 🟢 KickYoshi (v2)
### ⚠️ Low-End Genba Checker: DAWLESS Techno Kick & Rumble Safety Inspector

```text
 🐱‍👓 < "Are you sure this extreme sub-bass is mixed correctly?"
 👷‍♂️ < "YOSHI!! (Looking Good!!)" 👉 [EXPORT]
 💥 (The next day, the club's subwoofers literally exploded.)
```

**KickYoshi** は、作っている最中は「最高！ヨシ！」と思っていたテクノのキックやランブル（低音）が、時間が経ってから「大事故音源」だったと発覚する悲劇を防ぐための、**超軽量・ブラウザ完結型の音響安全確認ツール**です。

---

## 🛡️ クリーンインスコ美学 (Pure DAWLESS Philosophy)
* **PC汚染度：0%** (ただのHTML1枚。インストーラーも、レジストリ書き込みも、常駐プロセスも一切ありません。)
* **100%安全：** Web Audio APIを使ってローカル（ブラウザ内）で波形を解析するため、あなたの大切な音源が外部のサーバーにアップロードされることはありません。完全オフラインでも動作します。

---

## 👷‍♂️ 現場の指差呼称チェック項目 (Safety Checklists)

### 1. 滝の隙間ヨシ！ (Spectrogram Clearance)
* **現象：** 4つ打ちのキックが鳴り止んだ後、次のキックが鳴るまでの間に、画面の一番下（30Hz〜60Hzの重低音エリア）の色がちゃんと暗く（消えて）なっていますか？
* **災害：** ずっと明るい線のままだと、低音の余韻が長すぎてフロアが唸るだけの「低音泥沼災害」が発生します。MPC側のAmp EnvelopeでDecay/Releaseを縮めてください。

### 2. モノラル位相ヨシ！ (Mono Phase Correlation)
* **現象：** `🟢 強制モノラル` のチェックを入れた瞬間、低音のドスドス感が急に弱くなったりスカスカに引っ込んだりしませんか？
* **災害：** 音が消える場合は、リバーブやディレイを広げすぎたことによる「位相崩壊・打ち消し事故」です。クラブのモノラル音響で鳴らした瞬間に無音になります。低域はモノラルに固定してください。

---

## 🚀 現場への導入方法 (How to Use)

1. リポジトリ内の `kick_checker.html` をダウンロードします。
2. ブラウザ（Chrome / Edge / Safari等）にそのファイルをダブルクリックで開きます。
3. MPC等から書き出したWAVファイルを【ドロップ】するか、画面を【クリック】してファイルを選択します。
4. **「再生確認」**を押して、指差呼称でパトロールを開始してください。

---

## 📄 License
This project is deeply inspired by Japanese internet meme "Genba Neko" (Construction Worker Cat by @kumamine). 
This repository contains NO copyrighted image files, 100% raw text and pure web audio technology. Safety First!
