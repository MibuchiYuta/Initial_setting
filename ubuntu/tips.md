# 忘れがちなもの

## E: ロック /var/lib/dpkg/lock-frontend が取得できませんでした

以下の処理をさせる

```bash
$ sudo rm /var/lib/apt/lists/lock
$ sudo rm /var/lib/dpkg/lock
$ sudo rm /var/lib/dpkg/lock-frontend
```
