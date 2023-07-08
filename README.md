# minikube

minikube 用の設定手順、動作検証用の manifest やなどを保存しておく repository

#### シングルノードで環境を構築する

以下のコマンドを実行する。失敗する場合はコマンドの install からやり直すと良い

```bash
$ minikube start --driver=docker
```

`--driver` オプションをつけない場合は default で VM を利用して kubernetes が起動する。上記は docker を run time として利用する場合の実行コマンド

#### マルチノードで環境を構築する

立ち上げ時に指定する方法

```bash
$ minikube start --nodes 2
```

立ち上げ後に node を追加する

```bash
❯ minikube node add --worker
```

#### dashboard を利用する

```bash
$ minikube dashboard
```

# Document

- [minikube start](https://minikube.sigs.k8s.io/docs/start/)
