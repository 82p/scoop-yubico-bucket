# scoop bucket of yubico tools

This repository is unrelated Yubico AB.

## Getting Started

```ps1
Set-ExecutionPolicy RemoteSigned -scope CurrentUser 
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
scoop bucket add sgk-bucket https://github.com/82p/scoop-yubico-bucket.git
```

```ps1
> scoop install yubikey-personalization-tool
```

```ps1
> ykinfo -s
serial: xxxxxxx
```

## update bucket

```ps1
> git clone https://github.com/82p/scoop-yubico-bucket.git
> .\autoupdate.ps1
```
