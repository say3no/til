# try kubanetes
[Kubernetes](https://github.com/kubernetes/kubernetes)触ったこと無いマンなので触ってみる。

## Kubanetesがなにをもたらすか

>同一ホスト内で動くコンテナ同士は、プライベートネットワーク経由でやり取りができますが、ホストの外側とやり取りする場合は NAT (IP Masquerade) を経由する必要があります。
このように、標準の Docker 実行環境では、ホスト間の連携が煩雑になるため、コンテナの数が増えて要求されるリソースが大きくなった時に、容易にスケールアウトすることが出来ません。
この問題を解決するのが Kubernetes です。
Kubernetes によって、複数台のホストから構成される実行環境を **あたかも一台の実行環境のように** 扱うことができるようになります。
>
>[Docker（コンテナ型仮想化）と Kubernetes についての簡単な紹介](https://ubiteku.oinker.me/2017/02/21/docker-and-kubernetes-intro/) - 2017/02/21. @marubinotto 



## 参考

 - [Tutorials - Kubernetes](https://kubernetes.io/docs/tutorials/hello-minikube/) - 公式チュートリアル。Minikube。

 - [Docker for MacでKubernetes インストールからデプロイまで](https://qiita.com/uni-3/items/a4f2afa0973bfc35b498) - 2018/04/22. @uni-3

 - [Docker（コンテナ型仮想化）と Kubernetes についての簡単な紹介](https://ubiteku.oinker.me/2017/02/21/docker-and-kubernetes-intro/) - 2017/02/21. @marubinotto 

