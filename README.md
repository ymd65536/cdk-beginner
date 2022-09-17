# cdk_beginner

AWS CDK 入門

## Node のセットアップ

バージョン確認

```bash
node -v
# v16.17.0
```

## TypeScript セットアップ

TypeScriptをインストールする。

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
cdk init sample-app --language typescript
```

Python用のAWS CDKをセットアップする。

```bash
cdk init sample-app --language python
```

## AWS CDKの使い方

CDKのスタック一覧を表示する。

```bash
cdk ls
```

### VPCの定義を追加する

```ts
import * as ec2 from 'aws-lib/aws-ec2';
```

### S3バケットの定義を追加する

```bash
cdk synth --output ./output
```

### CloudFormation テンプレートを出力する

```bash
cdk synth > template.yml
```

### デプロイ用バケットの作成

```bash
cdk bootstrap --profile XXXX
```

### デプロイ

```bash
cdk deploy --profile XXXX
```

### リソースの削除

```bash
cdk destroy --profile XXXX
```
