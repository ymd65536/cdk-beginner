# cdk_beginner

AWS CDK 入門

## Node のセットアップ

バージョン確認

```bash
node -v
# v16.17.0
```

## ディレクトリを作成

```bash
mkdir hello-cdk && cd hello-cdk
```

## TypeScript セットアップ

npm を実行してプロジェクトを作成する。

```bash
npm install -g typescript
```

## 　AWS CDKインストール

グローバルにインストールする場合は以下のコマンドを実行する。

```bash
npm install -g aws-cdk
```

## AWS CDK のセットアップ

TypeScript用のAWS CDKをセットアップする。

```bash
cdk init app --language typescript
```

Python用のAWS CDKをセットアップする。

```bash
cdk init app --language python
```
