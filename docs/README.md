# 概要

## 目的

特定の技術スタックに依らず  
技術を通して「価値を生み出す」ために必要な問題解決の技法をドキュメント化します。

個人的には、これまでに開発PJで得た経験を棚卸して体系化することも目的としています。

## 運用

### docsify

ドキュメントは[docsify](https://docsify.js.org/#/)を利用して記述しています。

#### 編集方法

[公式ドキュメント](https://docsify.js.org/#/quickstart)を参照。

### Vercel

ドキュメントのホスティングは[Vercel](https://vercel.com/)を利用して行なっています。

#### デプロイ方法

> [!NOTE]
> Vercelで設定したのでmainブランチへのコミット時に自動でデプロイが行われます。  
> 以下は手動でのデプロイ方法です。

1. Vercel CLI環境を構築

```bash
npm i -g vercel
```

2. docs配下へ移動

```bash
cd docs
```

3. デプロイコマンドを実行

```bash
vercel --prod
```
