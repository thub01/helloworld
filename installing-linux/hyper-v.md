# Hyper-V

ここでは、Hypher-Vを使って、Linuxの環境を構築します。

## サービスの無効化

### 1. libvertd

```text
systemctl disable --now libvirtd
```

### 2. firewalld

```text
systemctl disable --now firewalld
```



