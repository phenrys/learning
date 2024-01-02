## Localização no terminal

### pwd

O comando `pwd` serve para informar o caminho absoluto que o terminal se encontra.

```bash
pwd

/Users/tkovs/dev/learning
```

### ls

  O comando `ls` serve para listar o arquivo de uma pasta.

Se você não informar a pasta,os arquivos das pastas atuais serão listados.

```bash
ls

bash
```

O ponto é um atalho para pasta atual.

```bash
ls .

bash
```

Dois pontos é um atalho para voltar um nivel de diretorio.

```bash
ls ..

learning
```

O `~` é um atalho que leva diretamente para pasta do usuario 

```bash
pwd

/Users/tkovs/dev/learning

cd ~

pwd

/Users/tkovs
```

### cd

O comando `cd` serve para navegar nas pastas do computador.

```bash
pwd

/Users/tkovs/dev/learning

cd ..

pwd

/User/tkovs/dev

cd .

pwd

/users/tkovs/dev

cd ~

pwd

/users/tkovs

cd /

pwd

/
```

### touch

O comando `touch` serve para criar um arquivo na pasta. Pode ser criado mais de um arquivo com mesmo comando. 

```
touch papel.txt

touch papel.txt  anime.txt
```
### rm

O comando `rm` serve para deletar o arquivo na pasta. Pode ser deletado mais de um arquivo com o mesmo comando 

```
rm papel.txt

rm papel.txt  anime.txt
```



