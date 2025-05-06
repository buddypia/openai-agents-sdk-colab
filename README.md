# Google Colabで試す OpenAI Agents SDK サンプルコード

このリポジトリでは、[OpenAI Agents SDKのの公式サンプルコード](https://github.com/openai/openai-agents-python/tree/main/examples)をGoogle Colaboratory（Colab）上で実行できるように修正したサンプルを提供しています。

# 事前準備：OpenAI APIキーの登録
Colabのノートブックを実行する前に、OpenAI APIキーを環境変数に登録する必要があります。以下の手順に従って設定してください。
1. OpenAIのウェブサイトでAPIキーを取得します。 まだAPIキーをお持ちでない場合は、[OpenAIのAPIキー管理ページ](https://platform.openai.com/api-keys)で作成してください。
2. ColabノートブックでAPIキーを設定します。 以下の方法でAPIキーを設定できます。
Colabの「ツール」メニューから「シークレット」を選択し、「OPENAI_API_KEY」という名前でAPIキーを登録します。その後、以下のコードで環境変数として読み込むことができます。
<img width="376" alt="openai-api-key" src="https://github.com/user-attachments/assets/fd10d227-e2a0-4e6f-9a55-1d6ec5fc1dd5" />

# サンプルコードの実行
このリポジトリに含まれる各Colabノートブック（.ipynbファイル）を開き、手順に従って実行してください。各ノートブックには、対応するOpenAI Agents SDKのサンプルコードの実行方法や、Colab環境での注意点などが記載されています。

# 注意事項
- OpenAI APIの利用には費用が発生する場合があります。料金体系については、OpenAIの料金ページをご確認ください。
- 提供されているサンプルコードは、OpenAI Agents SDKの機能を理解し、試すためのものです。実際のアプリケーション開発においては、セキュリティやエラーハンドリングなどを考慮した実装が必要になります。
- このリポジトリのコードや情報は、予告なく変更される場合があります。最新の情報は、OpenAI Agents SDKの公式ドキュメントをご確認ください。
