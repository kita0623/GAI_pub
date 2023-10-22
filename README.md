# GAI_pub

## Qita
### LangChainでCognitive SearchのベクトルDBを構築する (https://qiita.com/tmiyata25/items/cf417c51aad2660f2c42)
- 分割したテキストをベクトル化して、Cognitive Searchのインデックスとして登録
- ハイブリッド検索もあり  

### Azure OpenAIで独自データ追加機能(Add your data)を試してみた (https://qiita.com/tmiyata25/items/75a370154c28ee6c6983)
- [Azure OpenAI Studio]のチャットを開くとアシスタントのセットアップのウィンドウに「Add your data」が追加されています。
- この機能を使うことで独自のデータとGPTモデルを簡単に連携させることができ、GPTが知らない独自のデータを参照して回答を生成できるようになる
- 回答のソースを独自データに限定することもできる
- Add your dataで連携させたプレイグラウンドはWebアプリとしてデプロイできます。

### Microsoft が Azure Cognitive Search による RAG システムの定量評価結果を公表 (https://qiita.com/nohanaga/items/95a4780757e89b29e93e)
- Azure Cognitive Search 独自の検索機能である、セマンティックハイブリッド検索（ハイブリッド＋セマンティックランカー）が最も高い品質を示すことが分かりました

## LlamaIndex公式ドキュメント
### SubQuestionQueryEngine (https://gpt-index.readthedocs.io/en/latest/examples/query_engine/sub_question_query_engine.html)
### Azure Cognitive Search (https://gpt-index.readthedocs.io/en/latest/examples/vector_stores/CognitiveSearchIndexDemo.html#basic-example)
### Azure OpenAI (https://gpt-index.readthedocs.io/en/latest/examples/customization/llms/AzureOpenAI.html)