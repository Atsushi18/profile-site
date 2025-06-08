# 🌟 プロフィールサイト

名刺QRコード用のプロフィールリンクサイト

## 🚀 デプロイ

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/profile-site)

## 🛠️ カスタマイズ

1. `index.html` の以下の項目を編集：
   - 名前
   - 職業・肩書き
   - SNSリンク
   - メールアドレス

## 📱 機能

- レスポンシブデザイン
- アニメーション効果
- ダークモード対応
- SNSアイコン付きリンク

## 🔧 技術スタック

- HTML5
- CSS3
- Vanilla JavaScript
- Vercel (ホスティング)

## 📊 分析・改善

### Google Analytics追加
`index.html` の `<head>` セクションに以下を追加：

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🔄 継続的デプロイ

GitHubにプッシュすると自動的にVercelにデプロイされます：

```bash
# 変更をコミット・プッシュ
git add .
git commit -m "プロフィール情報を更新"
git push origin main
```