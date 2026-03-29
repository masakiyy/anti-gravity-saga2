# Vercelでの公開方法（最終手段）

もし「コマンドが見つからない」と言われてしまう場合、以下の「一番長いけど一番確実なコマンド」を使ってください。

## ステップ 1: ログイン（メール認証）
以下のコマンドをコピーして、ターミナルに貼り付け、**[あなたのメール]** の部分だけ書き換えて実行してください。

```bash
/opt/homebrew/bin/node /opt/homebrew/lib/node_modules/vercel/dist/vc.js login [あなたのメール]
```

例: `/opt/homebrew/bin/node /opt/homebrew/lib/node_modules/vercel/dist/vc.js login masaki@example.com`

**実行すると…**
1. ターミナルに「We sent an email...」と出ます。
2. スマホかPCで、届いたメールを確認します。
3. メール内の **「Verify」** ボタンを押します。
4. 「Success」と出れば、ログイン完了です！

---

## ステップ 2: 公開
ログインできたら、次は以下のコマンドを貼り付けて実行してください。

```bash
/opt/homebrew/bin/node /opt/homebrew/lib/node_modules/vercel/dist/vc.js
```

**質問への答え:**
すべて **Enterキー** を押していけばOKです。
最後に `https://...` というURLが表示されます。
