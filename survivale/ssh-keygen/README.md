# ssh-keygen

`ssh-keygen` pozwoli Tobie utworzyć klucz prywatny i publiczny, dzięki któremu będziesz mógł, dla przykładu, aktualizować repozytoria [git](../git/README.md).

## Survival

Najprościej utworzyć klucze SSH wpisując komendę `ssh-keygen` i wciskając enter kilka razy.

```console
$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/root/.ssh/id_rsa):
Created directory '/root/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /root/.ssh/id_rsa
Your public key has been saved in /root/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:XAaehwKWFWTeNzu2ZR8lhN5MWaPABnKqdxsk5PENqEk root@95968e0160c8
The key's randomart image is:
+---[RSA 3072]----+
|    o+==o+o. ..+.|
|   ..Eo+*+ooo.+ .|
|    . =+=oBo =. .|
|     o.oo= o. oo |
|     . .So+ o .  |
|      . ..o= . . |
|         ..   .  |
|                 |
|                 |
+----[SHA256]-----+
```

Ta komenda utworzy:

- katalog `.ssh` w lokalizacji albo `cd ~/.ssh`
- plik `~/.ssh/id_rsa`. To jest klucz prywatny. Nikomu nigdy go nie dawaj!
- plik `~/.ssh/id_rsa.pub`. To jest klucz publiczny. Ten plik (jego zawartość) będziesz umieszczać w githubie i innych miejscach, gdzie będzie to potrzebne.

![ssh-keygen](ssh-keygen.gif)
