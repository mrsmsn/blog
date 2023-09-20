#Hugoのインストール方法

## 環境
Windows + WSL + Ubuntu

## 実行したこと

### Hugoのインストール

1. 使用しているcpuを確認
1. [hugoのリリースページ](https://github.com/gohugoio/hugo/releases)に行って最新版のextendを探す
1. それっぽいのをwgetで入手
1. インストール

```
$sudo uname -m
x86_64

$wget https://github.com/gohugoio/hugo/releases/download/v0.118.2/hugo_extended_0.118.2_linux-amd64.deb

$sudo dpkg -i hugo_extended_0.118.2_linux-amd64.deb

$hugo version
hugo v0.118.2-da7983ac4b94d97d776d7c2405040de97e95c03d+extended linux/amd64 BuildDate=2023-08-31T11:23:51Z VendorInfo=gohugoio
```

