# cloud-workflows-samples


## ファイル
- sample.workflow.yml

とりあえずAPIを叩いてみるためのサンプル


## デプロイ、実行(例)

```
gcloud workflows deploy sample --source=sample.workflow.yml
gcloud workflows run sample --data='{"since":"2021-03-24"}'
```

