### git init

Inicializa um repositório local. Quando um repositório é iniciado uma pasta invisivel `.git` é criada. Está pasta contem informações das alterações do repositório.

### git status

Diz se há mudanças a ser commitada. Informa se as mudanças já estão sendo monitoradas, ou seja se estão na stage area.

### git add

O `git add` serve para adicionar  arquivos para o stage area. Ao fazer um commit apenas essas mudanças serão registradas.

Ao rodar um `git add .` na raiz do repositório, todas as mudanças são adicionadas para a stage area.

### git remote

**O que é um remote?**

É uma plataforma onde fica alocado o repositório.

**Eu posso ter mais de um?**

Sim é possivel ter vários remotes no repositório. E pode utilizar várias plataformas de hospedagens.

**Como adicionar um remote**

Para adicionar um remote é preciso utilizar o comando `git remote add <apelido> <endereço>` 

**Como listar os remotes cadastrados no repositório**

Pra listar os remotes cadastrados é preciso utilizar o comando `git remote`

**Como deletar um remote**

Para deletar um remote é preciso utilizar o comando `git remote remove` 
