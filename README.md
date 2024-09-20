# GIT CODES FOR DEVELOPERS
Codigos do git e como usa-los com a minha explicação fudid@
### Tópicos 

- [Logar](#1.)

- [Iniciar repositorio](#2.)

- [Adição](#3.)

- [Status](#4.)
  
- [Status 2](#5.)

- [Commit](#6.)

- [Master-Main](#7.)

- [Remote](#8.)
  
- [Origin](#9.)

- [Origin Error](#10.)
  
- [Commitar modify's](#11.)




## 1.
![1](https://github.com/anabtzz/GITCODES/assets/128055760/332d1b03-eb32-4341-adf8-8fb6cb19d15b)

    git config --global user.name ""
    git config --global user.email ""


Voce "loga" seu usuario ao git
## 2.
![2](https://github.com/anabtzz/GITCODES/assets/128055760/6624a83a-71eb-4dbd-8bc8-f4b526d4edb5)

    git init


Inicial uma conexão com o git da pasta do projeto
## 3.
![3](https://github.com/anabtzz/GITCODES/assets/128055760/03d46665-3ef5-4b46-96f7-5068e18f5cc3)

    git add .


Adiciona todos os codigos e arquivos do projeto na conexão
## 4.
![4](https://github.com/anabtzz/GITCODES/assets/128055760/288186fe-c5e1-4be3-89f2-b8d54c029801)

    git status


Para ver se os arquivos foram aidicionados ou não (codigo muito usado)
## 5.
![5](https://github.com/anabtzz/GITCODES/assets/128055760/fd90027f-f240-4a62-a3ff-107bcb074866)

    git status


Se os git's anteriores foram feitos, todos os aruiquivos devem ficar verdes tanto no terminal (vs code/studio ou no proprio git bash) quanto no software (no exemplo estou usando o vs code)
## 6.
![6](https://github.com/anabtzz/GITCODES/assets/128055760/641d26fd-afc2-44f6-b34b-8bd5c6cdbd8c)

    git commit -m ""


Adiciona um commit na conexão, sendo OBRIGATORIO colocar uma descrição (não precisa de texto so um ponto já vai)
## 7.
![7](https://github.com/anabtzz/GITCODES/assets/128055760/1f94ec37-6a0e-4c69-bf83-64ef610f9a2e)

    git branch -M main


Meio que troca do Master para a Main (por motivos de aline falou que tem que estar na main e por costume, sempre faça)
## 8.
![8](https://github.com/anabtzz/GITCODES/assets/128055760/7c59d7fa-7c91-4e3b-adf1-26d352d25161)

    git remote add origin ()


Linka a "conexão" feita com o repositorio ja criado no Git (isso é feito pois vai pegar todos os arquivos commitados e vai enviar pro Git usando o link do repositorio)
## 9.
![9](https://github.com/anabtzz/GITCODES/assets/128055760/f11bfb74-17e0-4d86-b61f-ee34b356c710)

    git push -u origin main


Vai empurrar todos os arquivos para o repositorio (no exemplo apresenta um erro, mas o comum é aparecer um pop-up na tela falando para logar diretamente no site do Git)
## 10.
![10](https://github.com/anabtzz/GITCODES/assets/128055760/e05c07b6-d91c-4fa1-8d2d-2e83838f8b88)


    git push origin main --force


Um possivel erro que opde acontecer é dar esse problema, duas soluões sao valida que é:

  Passar todos os arquivos para uma pasta nova;
  Dar um push forçado (não recomendado), porem se voce ja estiver feito a descrição e o titulo, tera que fazer de novo.
## 11.
![image](https://github.com/user-attachments/assets/ff473a93-d746-4d81-9b6e-00be8d7ca6ab)


      git add.
      git commit -am ""
      git push


Agora ja feito tudo isso como mandar uma modify que você fez no projeto (clone o repositorio no seu editor de preferencia para o passo a passo dar certo)


