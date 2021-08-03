# Ubuntuの初期設定用のメモ

## 基本情報

## デュアルブート

### 時間ずれへの対処方法

```bash
sudo timedatectl set-local-rtc true
timedatectl set-timezone Asia/Tokyo
```

## desktop

### 日本語  Remixをインストール場合

#### 日本語フォルダ名の変更

```bash
LANG=C xdg-user-dirs-gtk-update
```
![image](https://user-images.githubusercontent.com/53966307/127946975-03701b35-c4fc-4f84-af22-c772e4458645.png)

Don't ask me this again を選択し、
Update Names を押下

## VMware

### ssh設定

```bash
sudo apt-get update
sudo apt-get install openssh-server
sudo reboot
ip a
```
