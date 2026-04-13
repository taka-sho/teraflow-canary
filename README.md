# teraflow-canary
teraflow のリリース前検証用カナリア環境です。

## 用途
- teraflow の feature ブランチ修正を本番リリース前に E2E 検証する
- taka-sho/teraflow-check は本番テスト用、このリポは開発中機能の検証用

## E2E テスト実行
bash scripts/e2e-discovery.sh --version vX.X.X --repo taka-sho/teraflow-canary
