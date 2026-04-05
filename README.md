# devopscamp-amplify-sample

DevOps Camp Amplifyハンズオンで使用するサンプルのタスク管理アプリケーションです。

## 機能

- タスクの追加・完了・削除
- フィルタリング（すべて / 未完了 / 完了済み）
- LocalStorageによるデータ保存（バックエンドAPI不要）

## 環境変数

| 変数名 | 説明 | デフォルト値 |
|--------|------|-------------|
| `NEXT_PUBLIC_APP_TITLE` | アプリケーションのタイトル | タスク管理アプリ |

## ローカルでの起動

```bash
npm install
npm run dev
```

ブラウザで http://localhost:3000 にアクセスしてください。
