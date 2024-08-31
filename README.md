# 简介
本项目用于简单验证 Argo CD 与 k8s 结合效果

# 安装 argocd cli

## macos

```bash
brew install argocd
```

## linux

```bash
curl -sSL -o argocd-linux-amd64 https://github.com/argoproj/argo-cd/releases/latest/download/argocd-linux-amd64
sudo install -m 555 argocd-linux-amd64 /usr/local/bin/argocd
rm argocd-linux-amd64
```

