# GitHub

Utilizar o terminal do GitHub -> Git bash

## Exercício 1

a) Crie um repositório no GitHub (no site mesmo)

b) Crie um arquivo de texto e escreva “Olá, mundo!” (no arquivo.txt)

c) Adicione o arquivo à Staging Area 

``git init``

``git add .``

d) Faça o commit com uma mensagem apropriada

``git commit -m "first commit"``

``git branch -M main``

``git remote add origin https://github.com/gabsdnker/Teste``

e) Faça o push do commit

``git push -u origin main``

## Exercício 2

a) Em uma outra pasta, clone o repositório do exercício anterior 

``git clone https://github.com/gabsdnker/Teste``

b) Atualize o arquivo de texto colocando abaixo do “Olá, mundo!” as suas 
comidas favoritas (no arquivo.txt) 

no terminal: 

``cd Teste/``

``git add .``

``git commit -m "atualiza repositorio"``

``git push -u origin main`` 

c) Crie um outro arquivo de texto e coloque uma breve descrição sua (na pasta mesmo, na mão)

d) Faça o push desse novo arquivo
``git push -u origin main``

e) Delete o primeiro arquivo de texto do repositório local e do GitHub (deletar na mão o arquivo)

``git add .``

``git commit -m "deleta arquivo.txt"``

``git push -u origin main``
