
[cloudnativelabs/kube-shell](https://github.com/cloudnativelabs/kube-shell) without local `pip`.

```
docker run --rm -v $HOME/.kube:/home/k/.kube -ti solsson/kube-shell
# or
docker run --rm -v $HOME/.kube/my-specific-cluster-conf-file:/home/k/.kube/config -ti solsson/kube-shell
```

[#42](https://github.com/cloudnativelabs/kube-shell/issues/42) is an issue here.
Actually the reason I was looking for a kubectl wrapper was to
try to improve my workflow w.r.t. namespaces + tab completion.

Alternatives:

 * https://github.com/Mikulas/kubectl-repl/
 * https://github.com/c-bata/kube-prompt/
