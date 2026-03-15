# 🚀 ゲストハウス wakana サイト - クイックスタート

このファイル一式で、すぐにウェブサイトをGitHub Pagesで公開できます！

---

## ✅ 準備完了している内容

- ✅ Airリザーブ連携済み（https://airrsv.net/guesthouse-wakana/calendar）
- ✅ レスポンシブデザイン（PC・タブレット・スマホ対応）
- ✅ 日英バイリンガル対応
- ✅ 予約カレンダー機能
- ✅ ライトボックスギャラリー
- ✅ スムーズスクロールアニメーション

---

## 📦 ファイル構成

```
guesthouse-wakana/
├── index.html                 メインHTMLファイル
├── README.md                  プロジェクト説明
├── GITHUB_SETUP.md            GitHub Pages公開手順
├── AIR_RESERVE_GUIDE.md       Airリザーブ連携ガイド
└── images/                    画像フォルダ
    ├── hero.jpg              （要差し替え）
    ├── exterior.jpg          （要差し替え）
    ├── room.jpg              （要差し替え）
    ├── bath.jpg              （要差し替え）
    ├── garden.jpg            （要差し替え）
    └── gallery-1〜8.jpg      （要差し替え）
```

---

## 🎯 3ステップで公開

### Step 1: GitHubにアップロード（5分）

1. https://github.com にログイン
2. 右上の **+** → **New repository**
3. Repository name: `guesthouse-wakana`
4. Public を選択 → **Create repository**
5. **uploading an existing file** をクリック
6. すべてのファイルをドラッグ&ドロップ
7. **Commit changes** をクリック

### Step 2: GitHub Pagesを有効化（1分）

1. **Settings** → **Pages**
2. Source: **main** branch, **/ (root)**
3. **Save**

### Step 3: 公開完了！

数分後、以下のURLでアクセス可能：
```
https://あなたのユーザー名.github.io/guesthouse-wakana/
```

---

## 📸 画像の差し替え（後でOK）

1. 実際の写真を以下のファイル名で保存：
   - `hero.jpg` - トップページメイン（推奨: 1920×1080px）
   - `exterior.jpg` - 外観
   - `room.jpg` - 客室
   - `bath.jpg` - ヒノキ風呂
   - `garden.jpg` - 日本庭園
   - `gallery-1.jpg` 〜 `gallery-8.jpg` - ギャラリー

2. GitHubの `images/` フォルダにアップロード

---

## 🔧 カスタマイズポイント

### 情報の変更

`index.html` を編集して変更できる項目：

- **電話番号**: `0235-00-0000` → 実際の番号
- **メールアドレス**: `info@guesthouse-wakana.com`
- **住所**: `山形県鶴岡市高田下村25-2`
- **料金**: `¥8,000` / 泊
- **Googleマップ**: 38.748856, 139.812719

### 予約済み日程の追加

JavaScriptの `bookedDates` 配列を編集：

```javascript
const bookedDates = [
  '2026-03-20','2026-03-21', // 新しい予約を追加
];
```

---

## 📖 詳細ガイド

- **GitHub公開手順**: `GITHUB_SETUP.md` を参照
- **Airリザーブ連携**: `AIR_RESERVE_GUIDE.md` を参照
- **プロジェクト全体**: `README.md` を参照

---

## 💡 次のアクション

- [ ] GitHubにアップロード
- [ ] GitHub Pagesを有効化
- [ ] 公開URLを確認
- [ ] 実際の写真に差し替え
- [ ] 電話番号・住所を変更
- [ ] 予約をテスト

---

## 🆘 困ったときは

**よくある問題**:
- サイトが表示されない → 5〜10分待つ
- 画像が表示されない → ファイル名を確認
- レイアウトが崩れる → ブラウザキャッシュをクリア

詳細は `GITHUB_SETUP.md` のトラブルシューティングを参照

---

**準備はすべて整いました！ 頑張ってください！** 🎉
