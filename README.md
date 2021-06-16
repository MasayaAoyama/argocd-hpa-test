# overview

ArgoCDとApplicationのインストール

```
sh install-argocd.sh
```

このまま放置した場合、HPAがdegratedになります（正確にはDeploymentもDegratedになります）。
HPAのDegratedを回避するには、 `install-argocd.sh` のコメントアウトを外し、 `patched-argocd-cm.yaml` を適用してください。

