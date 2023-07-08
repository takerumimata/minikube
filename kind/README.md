## kind とは何か

minikube みたいなもので、手元で k8s 環境をお手軽に作れる tool。kubernetes 環境を構築するために docker を利用している点が異なる。

```bash
$ kind create cluster --config kind.yaml --name kindcluster
```

## Reference

- [Quick Start - kind](https://kind.sigs.k8s.io/docs/user/quick-start/)
- [Minikube vs. kind vs. k3s - What should I use?](https://shipit.dev/posts/minikube-vs-kind-vs-k3s.html)
