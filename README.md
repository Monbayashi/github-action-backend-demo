# GitHub Action

## env

環境変数

## secrets

非公開変数

リポジトリの Settings > Actions secrets で設定できる。

```yml
    env:
      MONGODB_CLUSTER_ADDRESS: demo-cluster
      MONGODB_USERNAME: ${{ secrets.MONGODB_USERNAME }}
      MONGODB_PASSWORD: ${{ secrets.MONGODB_PASSWORD }}
```