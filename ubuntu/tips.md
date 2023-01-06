# 忘れがちなもの

## E: ロック /var/lib/dpkg/lock-frontend が取得できませんでした

以下の処理をさせる

```bash
sudo rm /var/lib/apt/lists/lock
```
```bash
sudo rm /var/lib/dpkg/lock
```
```bash
sudo rm /var/lib/dpkg/lock-frontend
```
## Qt4のインストール

このサイトに従ってやったけどできなかった

https://ubuntuhandbook.org/index.php/2020/07/install-qt4-ubuntu-20-04/

その後以下のコマンドでインストールできた


```bash
sudo apt-get install qt4-dev-tools
```
```bash
sudo apt-get install qtcreator
```
