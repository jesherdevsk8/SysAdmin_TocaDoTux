### Para ver onde o Shell está
```
which fish
$ /usr/bin/fish

which zsh
$ /usr/bin/zsh

which bash
$ /usr/bin/bash
```
### Mudar Shell
```
chsh -s /usr/bin/fish
  -> obs: após executar o comando, dê exit e entre novamente

```

### Outra forma de mudar o shell é

```
usermod -s /usr/bin/zsh jesher

usermod -s /usr/bin/zsh root

(após isso executando)
cat /etc/passwd     <-- nota-se que foi alterado

feche o terminal e finalize a sessão do usuário / logout
depois de logar execute o terminal novamente
```
