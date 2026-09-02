# 阿倍寛 自己紹介ページ

早稲田大学水泳部に所属する阿倍寛の自己紹介ページです。総務省ウェブサイトの雰囲気を参考にしたデザインで作成しています。

## 構成

| ファイル | 内容 |
| --- | --- |
| `index.html` | ページ本体 |
| `assets/style.css` | スタイルシート |
| `.github/workflows/deploy.yml` | GitHub Pages への自動デプロイ |
| `.nojekyll` | Jekyll ビルドの無効化 |

## 公開方法（GitHub Pages）

1. GitHub リポジトリの **Settings > Pages** を開く
2. **Build and deployment** の **Source** を **GitHub Actions** に設定する
3. `main` ブランチへ push すると `deploy.yml` が実行され、自動的に公開される

公開 URL: `https://ayumu-u.github.io/ayu1/`

## ローカルでの確認

```bash
python -m http.server 8000
```

ブラウザで `http://localhost:8000/` を開く。
