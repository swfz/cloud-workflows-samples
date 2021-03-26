# cloud-workflows-samples


## ファイル
- sample.workflow.yml

とりあえずAPIを叩いてみるためのサンプル

- argument.workflow.yml

ランタイム引数を扱うサンプル

run時に`--data={"first_name":"piyo"}`というように引数を渡す

- now.workflow.yml

sys.now

- log-output.workflow.yml

ログ出力

- subworkflow.workflow.yml

サブワークフロー

## デプロイ、実行(例)

```
gcloud workflows deploy sample --source=sample.workflow.yml
gcloud workflows run sample --data='{"since":"2021-03-24"}'
```

