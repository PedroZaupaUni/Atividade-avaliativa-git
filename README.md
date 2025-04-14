# Atividade-avaliativa-git
Atividade 14/04

## Integrantes do grupo
- Daniel Yassou
- Jehad Alshoura
- Pedro Zaupa 

## Objetivo
Desenvolver colaborativamente um algoritmo em Portugol de…..

## Etapas realizadas por cada membro

### Pedro Zaupa 
- O repositório foi criado diretamente pelo site do github, compartilhado diretamente pelo e-mail acesso e permissão para edição do repositório.
-  compuni@maker224 MINGW64 ~
$ git config --global user.email pedrozaupa@edu.unifil.br

compuni@maker224 MINGW64 ~
$ git config --global user.name Pedro Zaupa

compuni@maker224 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C pedrozaupa@edu.unifil.br
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:I5Fc0gd08mPqZ4kp7UZh7h2JjDS78lygu3deg6QQtpo pedrozaupa@edu.unifil.br
The key's randomart image is:
+---[RSA 4096]----+
|      .o=..      |
|     . +.+.      |
|    o +  .+      |
|   . oo.oo .     |
|    o.oBSo .     |
|   o ooB==o.     |
|  E . o+B.*.     |
|    .oo+++..     |
|    o=o+o        |
+----[SHA256]-----+

compuni@maker224 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 1396

compuni@maker224 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (pedrozaupa@edu.unifil.br)

compuni@maker224 MINGW64 ~
$ clip <~/.ssh/id_rsa.pub

compuni@maker224 MINGW64 ~
$ ssh -T git@github.com
Hi PedroZaupaUni! You've successfully authenticated, but GitHub does not provide shell access.

- Foi criado após isso o arquivo algoritimo.por com aestrutura inicial de identificação de algoritimo já pronto. Logo apósn foi feito a declaração de senha do usuário, no qual é pedido que digite a senha.

### Jehad Alshoura
 $ ssh -T git@github.com
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
Hi jehh3! You've successfully authenticated, but GitHub does not provide shell access.

- fiz o git pull apos o pedro zaupa fazer a primeira fase do codigo, para incluir a minha parte do codigo.
- modifiquei o codigo incluindo uma condição onde caso a senha esteja errada, o aplicativo emite mensagem de erro e pede a senha novamente para avançar.
 

### Daniel Yassou
compuni@maker38 MINGW64 ~ (master)
$ eval "$(ssh-agent -s)"
Agent pid 1429

compuni@maker38 MINGW64 ~ (master)
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (daniel.rodrigues@edu.unifil.br)

compuni@maker38 MINGW64 ~ (master)
$ clip < ~/.ssh/id_rsa.pub
]
compuni@maker38 MINGW64 ~ (master)
$ ssh -T git@github.com
Hi Daniel-Yassuo! You've successfully authenticated, but GitHub does not provide shell access.

- Fiz o git pull após jehad fazer a segunda parte do código em portugol
- Eu incluí a parte de seleção de opções e saída do menu


## Comandos utilizados
Todos os comandos foram executados via terminal utilizando chave SSH:
### Comandos de Pedro Zaupa 

compuni@maker224 MINGW64 ~/Desktop/Atividade-avaliativa-git (edit-zaupa)
$ git add .
warning: LF will be replaced by CRLF in algoritimo.por.
The file will have its original line endings in your working directory

compuni@maker224 MINGW64 ~/Desktop/Atividade-avaliativa-git (edit-zaupa)
$ git status
On branch edit-zaupa
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   algoritimo.por
compuni@maker224 MINGW64 ~/Desktop
$ git clone git@github.com:PedroZaupaUni/Atividade-avaliativa-git.git
Cloning into 'Atividade-avaliativa-git'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@maker224 MINGW64 ~/Desktop
$ cd Atividade-avaliativa-git

compuni@maker224 MINGW64 ~/Desktop/Atividade-avaliativa-git (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 1.96 KiB | 83.00 KiB/s, done.
From github.com:PedroZaupaUni/Atividade-avaliativa-git
   508b4b6..db7c81d  main       -> origin/main
Updating 508b4b6..db7c81d
Fast-forward
 README.md | 79 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 79 insertions(+)

compuni@maker224 MINGW64 ~/Desktop/Atividade-avaliativa-git (main)
$ git checkout -b edit-zaupa
Switched to a new branch 'edit-zaupa'

compuni@maker224 MINGW64 ~/Desktop/Atividade-avaliativa-git (edit-zaupa)
$ git commit -m "Primeira parte do código feita
> "
[edit-zaupa 0820ef6] Primeira parte do código feita
 1 file changed, 21 insertions(+)

compuni@maker224 MINGW64 ~/Desktop/Atividade-avaliativa-git (edit-zaupa)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

compuni@maker224 MINGW64 ~/Desktop/Atividade-avaliativa-git (main)
$ git merge edit-zaupa
Updating db7c81d..0820ef6
Fast-forward
 algoritimo.por | 21 +++++++++++++++++++++
 1 file changed, 21 insertions(+)

compuni@maker224 MINGW64 ~/Desktop/Atividade-avaliativa-git (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 686 bytes | 686.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:PedroZaupaUni/Atividade-avaliativa-git.git
   db7c81d..0820ef6  main -> main


### Comandos de Jehad Alshoura
$ git pull
remote: Enumerating objects: 12, done.
remote: Counting objects: 100% (12/12), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 9 (delta 1), reused 3 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (9/9), 4.57 KiB | 83.00 KiB/s, done.
From github.com:PedroZaupaUni/Atividade-avaliativa-git
   db7c81d..b7a7e54  main       -> origin/main
Updating db7c81d..b7a7e54
Fast-forward
 README.md      | 86 +++++++++++++++++++++++++++++++++++++++++++++++++++++++---
 algoritimo.por | 21 ++++++++++++++
 2 files changed, 103 insertions(+), 4 deletions(-)

compuni@maker37 MINGW64 ~/Atividade-avaliativa-git (main)
$ git checkout -b edit-jehad
Switched to a new branch 'edit-jehad'

compuni@maker37 MINGW64 ~/Atividade-avaliativa-git (edit-jehad)
$ git add .

compuni@maker37 MINGW64 ~/Atividade-avaliativa-git (edit-jehad)
$ git status
On branch edit-jehad
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   algoritimo.por


compuni@maker37 MINGW64 ~/Atividade-avaliativa-git (edit-jehad)
$ git commit -m "modificação jehad"
[edit-jehad 63a8e6f] modificação jehad
 1 file changed, 4 insertions(+), 1 deletion(-)

compuni@maker37 MINGW64 ~/Atividade-avaliativa-git (edit-jehad)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

compuni@maker37 MINGW64 ~/Atividade-avaliativa-git (main)
$ git merge edit-jehad
Updating b7a7e54..63a8e6f
Fast-forward
 algoritimo.por | 5 ++++-
 1 file changed, 4 insertions(+), 1 deletion(-)

compuni@maker37 MINGW64 ~/Atividade-avaliativa-git (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 444 bytes | 444.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:PedroZaupaUni/Atividade-avaliativa-git.git
   b7a7e54..63a8e6f  main -> main


### Comandos de Daniel Yassou
compuni@maker38 MINGW64 ~ (master)
$ git clone git@github.com:PedroZaupaUni/Atividade-avaliativa-git.git
Cloning into 'Atividade-avaliativa-git'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@maker38 MINGW64 ~ (master)
$ cd Atividade-avaliativa-git

compuni@maker38 MINGW64 ~/Atividade-avaliativa-git (main)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 1.42 KiB | 39.00 KiB/s, done.
From github.com:PedroZaupaUni/Atividade-avaliativa-git
   63a8e6f..6ecf673  main       -> origin/main
Updating 63a8e6f..6ecf673
Fast-forward
 README.md | 58 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 58 insertions(+)

compuni@maker38 MINGW64 ~/Atividade-avaliativa-git (main)
$ git checkout -b edit-dani
Switched to a new branch 'edit-dani'


compuni@maker38 MINGW64 ~/Atividade-avaliativa-git (edit-dani)
$ git add .

compuni@maker38 MINGW64 ~/Atividade-avaliativa-git (edit-dani)
$ git status
On branch edit-dani
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   algoritimo.por


compuni@maker38 MINGW64 ~/Atividade-avaliativa-git (edit-dani)
$ git commit -m "modificação Daniel"
[edit-dani e8e03f8] modificação Daniel
 1 file changed, 6 insertions(+)

compuni@maker38 MINGW64 ~/Atividade-avaliativa-git (edit-dani)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

compuni@maker38 MINGW64 ~/Atividade-avaliativa-git (main)
$ git merge edit-dani
Updating 6ecf673..e8e03f8
Fast-forward
 algoritimo.por | 6 ++++++
 1 file changed, 6 insertions(+)

compuni@maker38 MINGW64 ~/Atividade-avaliativa-git (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 403 bytes | 201.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:PedroZaupaUni/Atividade-avaliativa-git.git
   6ecf673..e8e03f8  main -> main

