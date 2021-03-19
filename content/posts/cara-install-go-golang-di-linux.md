---
title: "Cara install Go/Golang di Linux"
date: 2021-03-19T07:40:17+07:00
draft: false
---

## System Operasi (linux) Saya

- Ubuntu 20.04

## Langkah Installasi

Buka command line (cmd), dan jalankan perintah dibawah ini

```sh
cd ~
wget https://golang.org/dl/go1.16.2.linux-amd64.tar.gz
tar -xf go1.16.2.linux-amd64.tar.gz

# execute and puts the line below to your ~/.bashrc or any bashprofile file
export GOROOT="/home/$USER/go"
export GOPATH="/home/$USER/go/packages"
export PATH=$PATH:$GOROOT/bin:$GOPATH/bin
```

Happy Going! (:

