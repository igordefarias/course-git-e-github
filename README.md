# course-git-e-github
My repository of Guanabara's course of Git and GitHub.

Olá, Mundo! Primeiro repositório do curso de Git e GitHub, criado com o propósito de aprender a usar estas duas ferramentas.

Irei atualizar esse repositório , a medida em que aprendo algo novo.

Estou usando o Codespaces. Pelo terminal aprendi a verificar quais arquivos foram modificados, usando o comando "git status". 

Antes de "commitar" é preciso dizer ao Git para salvar as mudanças. Faz-se isto sempre, com o comando "git add nome-do-arquivo". Por exemplo: git add README.md

A seguir irei "commitar", i.e mandar o Git criar uma "fotografia" das minhas alterações. Como ele faz isso? Lembre-se: "commit" diz ao Git para salvar as alterações no servidor local (minha máquina, no caso o Codespace), criando assim um histórico.

O próximo passo é sincronizar o meu histórico local de alterações com o repositório remoto, ou seja, o GitHub. Isto se faz com o comando "git push".

Essa linha eu adicionei pelo editor de texto do próprio GitHub. Isso é considerado pelo Git uma alteração feita no servidor remoto. Darei o "commit" e provavelmente ao entrar no terminal e escrever "git status" haverá uma mensagem para que se faça um pull, isto é puxar a modificação do "remoto" (GitHub) para o "local" (Git). Pelo que entendi, isto é muito útil e usado quando outra pessoa (ou eu mesmo, em outro lugar) altera o código. Portanto, é hora de atualizar o Codespaces para buscar e aplicar as mudanças que estão no repositório remoto, com o comando git pull.

Atualização do passo anterior: após acrescentar o texto acima no remoto, fui no local e pelo terminal escrevi git status. Vi que nda foi avisado sobre esta última mudança, portanto o git não diz o que foi modificado no remoto, embora ao dar git pull ele atualize de fato o arquivo, trazendo a modificação para cá.