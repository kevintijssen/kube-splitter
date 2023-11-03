# kube-splitter

a lightweight application to seperates a single Kubernetes YAML file in multiple files based-on there kind.

## Install

### [Download the latest binary](https://github.com/kevintijssen/kube-splitter/releases/latest)

### wget
Use wget to download:

For instance, VERSION=v0.0.1

#### Plain binary

```bash
wget https://github.com/kevintijssen/kube-splitter/releases/download/${VERSION}/kube-splitter -O /usr/bin/kube-splitter &&\
    chmod +x /usr/bin/kube-splitter
```

#### Latest version

```bash
wget https://github.com/kevintijssen/kube-splitter/releases/latest/download/kube-splitter -O /usr/bin/kube-splitter &&\
    chmod +x /usr/bin/kube-splitter
```